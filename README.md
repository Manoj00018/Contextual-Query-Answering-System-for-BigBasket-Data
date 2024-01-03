# CSV Query Engine using LLM

This project is a Flask API-based query engine that integrates a Large Language Model (LLM) with a Qdrant vector database, using data from the BigBasketProducts dataset.

## Technology Used

The project utilizes the following technologies:

    Embedding Technique: BERT
    Database: Qdrant
    Language Model: T5
    API Framework: Flask

Data preprocessing was accomplished using pandas, converting data to vectors through BERT embeddings. These vectors were stored in a Qdrant database, hosted on the Qdrant cloud. The Flask app API is designed to manage POST requests for 'get_answer', utilizing the flan-t5-small LLM to find the closest vector match in the database for the query.

## Project Progression

Key development phases included:

    Preprocessing the CSV dataset.
    Generating vector embeddings with BERT.
    Creating a metadata JSON file.
    Establishing and managing the Qdrant database.
    Developing a Flask API and test script.
    Implementing a T5 LLM for query processing.
    
