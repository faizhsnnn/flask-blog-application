## Flask Blog Application

This project is a dynamic blog web application built using Flask. It fetches blog post data from an external API and renders the content using HTML templates.

The application displays a list of blog posts on the homepage and allows users to view individual posts through dynamic routing.

This project demonstrates how backend applications can fetch external data, structure it using Python classes, and render it dynamically in web templates.

This project was built as part of the #90DaysOfCode challenge to practice backend development, API integration, and template rendering using Flask.

---

## Technologies Used

Python  
Flask  
HTML5  
CSS3  
Jinja2 Templating  
Requests  

---

## Key Concepts Demonstrated

Fetching data from external APIs using Requests

Structuring data using Python classes

Dynamic routing in Flask using URL parameters

Template rendering with Jinja2

Passing data from backend to frontend

Building multi-page web applications

Separation of concerns using modular code

---

## Project Structure

```
project/
│
├── main.py
├── post.py
├── templates/
│   ├── index.html
│   └── post.html
├── static/
│   └── css/
│       └── styles.css
```

---

## Application Workflow

1. Fetch blog data from an external API
2. Convert raw JSON data into Python objects
3. Render all posts on the homepage
4. Generate dynamic routes for individual posts
5. Display full blog content when a post is selected

---

## Installation

Install required dependencies

```
pip install flask
pip install requests
```

---

## Run

```
python main.py
```

Open your browser and go to

```
http://127.0.0.1:5000
```

---

## Why This Project Matters

This project demonstrates how backend systems can integrate with external APIs and dynamically render content for users.

It reflects real-world web application patterns where data is fetched, processed, and displayed through a structured frontend.

---

## Author

Faiz Hasan  
Python Automation & Backend Developer
