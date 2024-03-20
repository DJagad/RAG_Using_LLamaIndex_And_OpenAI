## RAG_USING_LLAMAINDEX_AND_OPENAI

# Retrieval Augmented Generation

This Python script demonstrates the implementation of Retrieval Augmented Generation (RAG) using OpenAI's API for natural language processing. The code utilizes various functionalities from the `llama_index` library for document indexing and querying.

## Prerequisites
- Python 3.10.x
- `dotenv` library
- `llamaindex` library 
- `openai` library
- `pypdf` library
- OpenAI API key

## Setup
1. Store your OpenAI API key in a `.env` file at the root of the project directory.
2. Ensure that your document data is stored in a directory named "data".

## Usage
1. Run the script.
2. The script initializes the OpenAI API using the provided key.
3. It loads documents from the "data" directory and creates a vector index.
4. Queries are performed on the index using the RAG model for various topics such as syndication feeds, Ajax applications, and blockchain technology.
5. The script demonstrates how to print and display responses with source information.
6. It also showcases the creation of persistent storage for RAGs on the local system, facilitating faster access to indexed information.

## Additional Notes
- If the persistent storage directory does not exist, the script creates it and indexes documents for future queries.
- Existing storage directories are loaded to provide access to previously indexed information.

## Important
- Ensure proper handling of your OpenAI API key to maintain security.
- Customize the document data directory and storage directory paths as per your project structure.
- Consider the computational and storage requirements for indexing large document collections.

Feel free to explore and modify the script according to your requirements!
