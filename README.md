
# Assignment 4 - FastAPI Implementation

## Description
This project demonstrates how to create a simple API using FastAPI in Python.

## Features
- GET request to return a Hello World message.
- GET request to retrieve an item using an item ID.
- PUT request to update an item using a Pydantic model.

## Technologies Used
- Python
- FastAPI
- Uvicorn
- Pydantic

## Running the Application
Install the required packages:

pip install fastapi
pip install "uvicorn[standard]"

Start the server:

uvicorn main:app --reload

Open the API documentation:

http://127.0.0.1:8000/docs
