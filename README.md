# Prompt-2-SQL
Prompt 2 SQL is a web application designed to simplify the process of querying datasets by allowing users to input natural language prompts. The application automatically converts 
these prompts into SQL queries using a pre-trained model and executes them on the uploaded dataset. This project leverages Streamlit for the frontend and the Salesforce/T5-large-SQL model
for generating SQL queries from natural language.

## Features
- Dataset Upload : Users can upload their dataset in CSV format.
- Natural Language Prompt Input : Enter a natural language prompt (e.g., "Show me the first 5 rows" or "Find average sales by region").
- SQL Query Generation : Converts the natural language input into an SQL query using the Salesforce/T5-large-SQL model.
- Query Execution : The generated SQL query is executed on the uploaded dataset, and the results are displayed directly in the app.
- Real-Time Query Results : Users can instantly see the results of their queries on the screen.
- Error Handling : Basic error handling for invalid queries or datasets.

## License
This project is licensed under the MIT License. See the LICENSE file for details.

## Acknowledgements
- Hugging Face for providing the T5-large-SQL model.
- Streamlit for the easy-to-use web app framework.
