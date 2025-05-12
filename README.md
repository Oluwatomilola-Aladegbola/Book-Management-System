# Book-Management-System
A FastAPI project for managing a list of books with endpoints for retrieving, adding, filtering, updating, and deleting books.

**The key features of the project include:**

-- Retrieve all books

-- Get a specific book by ID

-- Add new books

-- Filter books by parameters(i.e author,title)

-- Delete books

-- Borrow and return books

-- Calculate fines for overdue books 

**Tech Stack include:**

-- Language: Python 3

-- Framework: FastAPI

-- Server: Uvicorn

**To run the project:**
1. Install FastAPI and Uvicorn
   - Open the vscode terminal and run:

     		pip install fastapi uvicorn
     
2. Start the FastAPI server
   -In your terminal, run:

   		uvicorn main(name of the file): app --reload

3. Access the API documentation
   - Once the server is running, open the browser and search for the link to the endpoint
   
   - Then copy thrt the endpoint generated and attach /docs behind it in the browser
   
   - An interface (the Swagger UI) is displayed where you can see and test all available routes.
