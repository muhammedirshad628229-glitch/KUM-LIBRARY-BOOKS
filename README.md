# KUM-LIBRARY-BOOKS
body {
  font-family: Arial, sans-serif;
  background-color: #f4f6f9;
  margin: 0;
  padding: 20px;
}

.container {
  max-width: 900px;
  margin: 0 auto;
  text-align: center;
}

h1 {
  color: #333;
}

.search-box {
  margin-bottom: 25px;
}

input {
  width: 60%;
  padding: 12px;
  font-size: 16px;
  border: 1px solid #ccc;
  border-radius: 5px;
  outline: none;
}

button {
  padding: 12px 20px;
  font-size: 16px;
  background-color: #007bff;
  color: white;
  border: none;
  border-radius: 5px;
  cursor: pointer;
  margin-left: 5px;
}

button:hover {
  background-color: #0056b3;
}

.results-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
  gap: 20px;
}

.book-card {
  background: white;
  padding: 15px;
  border-radius: 8px;
  box-shadow: 0 2px 8px rgba(0, 0, 0, 0.1);
  text-align: left;
}

.book-card img {
  width: 100%;
  height: 200px;
  object-fit: cover;
  border-radius: 5px;
}

.book-card h3 {
  font-size: 16px;
  margin: 10px 0 5px;
}

.book-card p {
  font-size: 14px;
  color: #666;
  margin: 0;
}
