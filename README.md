# InsightDB - Conversational SQL Assistant

## InsightDB is an AI-powered SQL assistant that allows users to interact with their MySQL databases using natural language queries. It generates SQL queries based on user input and provides detailed responses by fetching relevant data from the database. This project leverages LangChain, Groq's Mistral-8x7B, and Streamlit to create a seamless database query experience.

## Features

Connect to any MySQL database and retrieve information conversationally.

Automatically generates SQL queries based on user prompts.

Uses Groq's Mistral-8x7B for query generation and response formulation.

Supports OpenAI's GPT models as an alternative to Mistral.

Provides a user-friendly Streamlit interface.

## 1. Database Connection Setup

InsightDB requires a MySQL database connection. Users can provide the following credentials:

Host (e.g., localhost)

Port (default: 3306)

User (e.g., root)

Password

Database Name

## 2. Query Execution Flow

User Query: The user asks a question about the database.

Schema Extraction: The system retrieves table schemas from MySQL.

SQL Query Generation: The AI model (Mistral or OpenAI GPT) generates a SQL query.

Query Execution: The generated SQL query is run on the MySQL database.

Natural Language Response: The AI model interprets the SQL output and provides a human-readable response.

## 3. How to Run the Project
Clone the repository:
```bash
git clone https://github.com/21kNabeelUddin/InsightDB.git
```


Install necessary dependencies: Create a virtual environment and install the required libraries using requirements.txt:
```bash
pip install -r requirements.txt
```

move to directory using
```bash
cd InsightDB
```

run the StreamlitApp
```bash
streamlit run app.py
```

