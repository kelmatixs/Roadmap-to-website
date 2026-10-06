# Chapter 4: Backend Development and APIs

## 1. Backend development

The backend is the logic and data layer behind a website.

It handles:

- user login
- form submission
- database operations
- API requests
- security

## 2. Common backend languages

- JavaScript / Node.js
- Python
- PHP
- Java
- Ruby

## 3. Backend frameworks

- Express.js (Node.js)
- Django (Python)
- Flask (Python)
- Laravel (PHP)
- Spring Boot (Java)

## 4. What is an API?

An API allows different software systems to communicate.

### Example

```javascript
fetch('https://api.example.com/users')
  .then(response => response.json())
  .then(data => console.log(data));
```

## 5. REST API concepts

- routes
- methods (GET, POST, PUT, DELETE)
- JSON data
- status codes
- requests and responses

## 6. Server concepts

Learn:

- routing
- middleware
- authentication
- authorization
- error handling
- validation

## 7. Example Node.js server

```javascript
const express = require('express');
const app = express();

app.get('/', (req, res) => {
  res.send('Welcome to the backend');
});

app.listen(3000, () => {
  console.log('Server running on port 3000');
});
```

## 8. Final note

The backend powers the website logic behind the scenes and is essential for creating dynamic applications.
