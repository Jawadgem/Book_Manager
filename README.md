# Book Collection Manager

## Overview
The **Book Collection Manager** is a Python-based command-line application that helps users store, organize, and manage their personal book collections. Users can add, update, delete, search for books, and track their reading progress.

## Features
- 📖 **Add New Books** – Store book details including title, author, publication year, genre, description, and reading status.
- ❌ **Remove Books** – Delete books from the collection by title.
- 🔍 **Search Books** – Find books by title or author.
- ✏️ **Update Book Details** – Modify book information.
- 📚 **View All Books** – List all books with details.
- 📊 **Track Reading Progress** – View statistics on read vs. unread books.
- 💾 **Persistent Storage** – Books are saved in a `books_data.json` file.

## Installation & Usage
### Prerequisites
Ensure you have **Python 3.6+** installed.

### Install Dependencies
No external libraries are required; Python's built-in `json` module is used.

### Run the Application
1. Clone or download the repository.
2. Navigate to the project folder in the terminal.
3. Run the script:
   ```sh
   python main.py
   ```

### Menu Options
1️⃣ Add a new book  
2️⃣ Remove a book  
3️⃣ Search for books  
4️⃣ Update book details  
5️⃣ View all books  
6️⃣ View reading progress  
7️⃣ Exit  

## File Structure
```
📂 BookCollectionManager
 ├── 📄 main.py   # Main application script
 ├── 📄 books_data.json   # Storage file for book collection
 ├── 📄 README.md         # Documentation
```

## How It Works
- When the script runs, it loads books from `books_data.json`.
- Users interact with the menu to manage their book collection.
- All changes are saved automatically.

## Future Improvements
- ✅ Add support for CSV export.
- 📊 Visualize reading progress with graphs.
- 🖥️ Convert into a GUI-based application.

## License
This project is open-source and available under the **MIT License**.

---
✉️ **Feedback?** Feel free to suggest improvements!

