import React, { useState } from "react";

export default function LibraryManagement() {
  // Initial book list
  const [books, setBooks] = useState([
    { id: 1, title: "1984", author: "George Orwell" },
    { id: 2, title: "The Great Gatsby", author: "F. Scott Fitzgerald" },
    { id: 3, title: "To Kill a Mockingbird", author: "Harper Lee" },
  ]);

  // States for search and form inputs
  const [search, setSearch] = useState("");
  const [newTitle, setNewTitle] = useState("");
  const [newAuthor, setNewAuthor] = useState("");

  // Add new book
  const handleAddBook = () => {
    if (newTitle.trim() && newAuthor.trim()) {
      const newBook = {
        id: Date.now(),
        title: newTitle,
        author: newAuthor,
      };
      setBooks([...books, newBook]);
      setNewTitle("");
      setNewAuthor("");
    }
  };

  // Remove book
  const handleRemoveBook = (id) => {
    setBooks(books.filter((book) => book.id !== id));
  };

  // Filtered list based on search
  const filteredBooks = books.filter(
    (book) =>
      book.title.toLowerCase().includes(search.toLowerCase()) ||
      book.author.toLowerCase().includes(search.toLowerCase())
  );

  return (
    <div
      style={{
        backgroundColor: "white",
        color: "black",
        fontFamily: "Arial, sans-serif",
        minHeight: "100vh", // full height
        width: "100vw",     // full width → removes black areas
        padding: "20px",
        boxSizing: "border-box",
      }}
    >
      <h2 style={{ textAlign: "center" }}>Library Management</h2>

      {/* Search */}
      <input
        type="text"
        placeholder="Search by title or author"
        value={search}
        onChange={(e) => setSearch(e.target.value)}
        style={{
          width: "100%",
          marginBottom: "15px",
          padding: "10px",
          border: "1px solid black",
          fontSize: "14px",
          backgroundColor: "white",
          color: "black",
        }}
      />

      {/* Add book form */}
      <div
        style={{
          display: "flex",
          gap: "10px",
          marginBottom: "15px",
          flexWrap: "wrap",
        }}
      >
        <input
          type="text"
          placeholder="New book title"
          value={newTitle}
          onChange={(e) => setNewTitle(e.target.value)}
          style={{
            padding: "10px",
            border: "1px solid black",
            fontSize: "14px",
            flex: "1 1 200px",
            backgroundColor: "white",
            color: "black",
          }}
        />
        <input
          type="text"
          placeholder="New book author"
          value={newAuthor}
          onChange={(e) => setNewAuthor(e.target.value)}
          style={{
            padding: "10px",
            border: "1px solid black",
            fontSize: "14px",
            flex: "1 1 200px",
            backgroundColor: "white",
            color: "black",
          }}
        />
        <button
          onClick={handleAddBook}
          style={{
            padding: "10px 15px",
            backgroundColor: "white",
            color: "black",
            border: "1px solid black",
            cursor: "pointer",
            flexShrink: 0,
          }}
        >
          Add Book
        </button>
      </div>

      {/* Book list */}
      <div>
        {filteredBooks.map((book) => (
          <div
            key={book.id}
            style={{
              border: "1px solid black",
              padding: "12px",
              marginBottom: "10px",
              display: "flex",
              justifyContent: "space-between",
              alignItems: "center",
              backgroundColor: "white",
              color: "black",
            }}
          >
            <span>
              <strong>{book.title}</strong> by {book.author}
            </span>
            <button
              onClick={() => handleRemoveBook(book.id)}
              style={{
                padding: "6px 12px",
                backgroundColor: "white",
                color: "black",
                border: "1px solid black",
                cursor: "pointer",
              }}
            >
              Remove
            </button>
          </div>
        ))}
      </div>
    </div>
  );
}
