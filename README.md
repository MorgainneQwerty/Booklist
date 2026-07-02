# Booklist

Entendido. Aqui está a versão limpa, sem nenhum emoji, ideal para um perfil mais minimalista e direto:

Book Catalog REST API with Python
This is a simple REST API project developed to demonstrate my fundamental knowledge of Backend development using Python and FastAPI.

The main goal of this project is to apply essential concepts of API architecture, route management, data validation, and the HTTP protocol.

Technologies Used
Python 3: A robust and versatile programming language.

FastAPI: A modern, high-performance web framework, perfect for building APIs.

Uvicorn: A lightning-fast ASGI server to run the Python application.

Pydantic: Used by FastAPI for rigorous data type validation.

Practical Concepts Applied
HTTP Verbs: Correct usage of GET (reading data) and POST (creating data).

HTTP Status Codes: Implementation of semantic responses (200 OK and 201 Created).

Data Binding & Validation: Using Pydantic Schemas to ensure the API only accepts correct data (preventing bugs).

Automatic Documentation: Native integration with Swagger UI (/docs).

API Routes
1. List Books
Method: GET

URL: [http://127.0.0.1:8000/livros](http://127.0.0.1:8000/livros)

Expected Response (200 OK): An array containing the registered books.

2. Register a New Book
Method: POST

JSON
{
  "titulo": "Dom Casmurro",
  "autor": "Machado de Assis"
}
