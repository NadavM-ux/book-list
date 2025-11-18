
  # 📚 Book List API
  _First Git Project – SCE · 2nd Year_

  A simple FastAPI project that manages a list of books in memory.
  This project was created as part of learning Git, branching, and pull requests.

  ## Features
  - Get all books
  - Get a single book by ID
  - Add new books
  - Delete books
  - Uses in-memory data (no database)

  ## 📁 Project Structure
    book-list/
      main.py            # FastAPI app code
      requirements.txt   # Dependencies
      README.md          # Project documentation

  ## 🛠 Installation

  ### 1. Clone the repository
    git clone https://github.com/<your-username>/book-list.git
    cd book-list

  ### 2. Install dependencies
    pip install -r requirements.txt

  ## ▶️ Running the Server
  Start the FastAPI server:
    uvicorn main:app --reload

  Open in your browser:
  - http://127.0.0.1:8000
  - http://127.0.0.1:8000/docs

  ## 📘 API Endpoints

  ### Get all books
    GET /books

  ### Get book by ID
    GET /books/{book_id}

  ### Add a new book
    POST /books
    Body:
      {
        "title": "Some Title",
        "author": "Some Author"
      }

  ### Delete a book
    DELETE /books/{book_id}

  ## Example Data
    [
      { "id": 1, "title": "Nadav Magen's Book", "author": "Nadav Magen" },
      { "id": 2, "title": "C+ Book", "author": "Boring Man!" },
      { "id": 3, "title": "Java Book", "author": "Cool Man!" }
    ]

  ## What I Learned
  - Creating branches
  - Committing changes
  - Pull requests
  - Merging (including no-fast-forward)
  - Basic FastAPI usage

  ## License
  MIT License
