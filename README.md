<link rel="stylesheet" href="style.css">
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}
body {
  font-family: Arial, sans-serif;
  font-size: 16px;
  color: #333;
  background-color: #fafafa;
  line-height: 1.6;
}
h1 { font-size: 2.5rem; font-weight: bold; }
h2 { font-size: 2rem; }
p  { font-size: 1rem; letter-spacing: 0.5px; }
header {
  display: flex;
  justify-content: space-between;
  align-items: center;
  padding: 1rem 2rem;
  background-color: #004466;
  color: white;
}
.content {
  display: grid;
  grid-template-columns: 2fr 1fr;
  gap: 1.5rem;
  padding: 2rem;
}
button {
  background: #0077cc;
  color: white;
  border: none;
  padding: 0.8rem 1.2rem;
  border-radius: 6px;
  transition: background 0.3s ease;
}
button:hover {
  background: #005fa3;
}
