# Langchain RAG Application
## Overview
This repository contains a Flask application designed to provide AI-powered document search and analysis functionalities. The application leverages various language processing and document handling libraries to enable users to interact with PDF documents, extract text, perform queries, and retrieve relevant information.

## Features
- **Document Upload**: Users can upload PDF documents to the server for processing.
- **Document Text Extraction**: Uploaded PDF documents are processed to extract text content for further analysis.
- **Document Vectorization**: Extracted text content is vectorized using the Chroma vector store, allowing for efficient similarity-based document retrieval.
- **Document Retrieval**: Users can query the system for information, and relevant documents are retrieved based on the similarity of their content to the query.
- **AI Response**: The application incorporates a language model (LLM) for generating responses to user queries and providing contextually relevant information.
- **Multiple Endpoints**: The application provides different endpoints for specific functionalities, including uploading documents, querying documents, and interacting with the AI assistant.

## Usage
1. Install dependencies using pip:
   pip install -r requirements.txt
2. Start the Flask application by running the following command:
   python <filename>.py

3. Access the application through the provided endpoints:
- **Document Upload**: POST request to `/pdf`.
- **Document Query**: POST request to `/ask_pdf`.
- **AI Query**: POST request to `/ai`.
4. Follow the API documentation for each endpoint to structure requests and handle responses appropriately.

## Dependencies
- Flask: Web framework for building the application endpoints.
- Langchain libraries: Includes various modules for text splitting, document loading, embeddings, and document chains.
- PDFPlumber: Library for extracting text from PDF documents.
- Other dependencies as specified in the `requirements.txt` file.

## Configuration
- The application can be configured by modifying parameters such as host, port, and debug mode in the `start_app()` function.
- Additional configuration options for specific functionalities can be found within the respective endpoint functions.

## Contributing
Contributions to this project are welcome. You can contribute by:
- Submitting bug reports or feature requests through the issue tracker.
- Forking the repository, making changes, and submitting pull requests for review.

## Acknowledgments
- This project utilizes open-source libraries and frameworks without which it would not be possible.
- Special thanks to the contributors and maintainers of the dependencies used in this project.







 
