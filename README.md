# AI-ML
Project Assignment

#First, create a new directory for your project and set up a virtual environment
   mkdir fastapi-recommender
   cd fastapi-recommender
   python -m venv venv
   source venv/Scripts/activate  

#Install required dependencies
pip install fastapi uvicorn sqlalchemy sqlite3 openai transformers faiss-cpu redis asyncpg psycopg2

#Define the Data Model
#Populate Product Data
Run this file ->python data_loader.py
#Implement API Endpoints
Run the API->uvicorn main:app --reload
