# AI-ML
Project Assignment

#First, create a new directory for your project and set up a virtual environment

   1.mkdir fastapi-recommender
   
  2. cd fastapi-recommender
   
  3. python -m venv venv
   
   4.source venv/Scripts/activate  

#Install required dependencies

5.pip install fastapi uvicorn sqlalchemy sqlite3 openai transformers faiss-cpu redis asyncpg psycopg2

#Define the Data Model

#Populate Product Data

6.Run this file ->python data_loader.py

#Implement API Endpoints

7.uvicorn main:app --reload
