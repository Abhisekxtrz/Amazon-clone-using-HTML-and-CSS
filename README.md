 The Amazon Clone is a front-end web development project that replicates the user interface of the popular e-commerce platform Amazon using only HTML and CSS. The project focuses on designing a visually appealing, responsive, and structured layout that resembles the original Amazon website while practicing the fundamentals of web development.
🛒 Amazon Clone (Frontend + API Docs)

A simple Amazon-style clone built with HTML and CSS.
This project demonstrates responsive UI design and can be extended with backend APIs for products, cart, and authentication.

🚀 Project Overview

Frontend: Static UI built with HTML5 + CSS3.

APIs (Planned): Product listing, Cart management, User authentication.

Goal: Practice e-commerce front-end + prepare for full-stack integration.

📦 Installation

Clone the repository:

git clone https://github.com/Abhisekxtrz/Amazon-clone-using-HTML-and-CSS/edit/main/README.md


Open index.html in your browser.
(Optional: Serve with Live Server / any static file server).


🔑 Authentication

All secure endpoints use JWT tokens:

Authorization: Bearer <your_token>

📚 API Endpoints
1. Products
GET /products


Fetch all products.
Query Params:

limit (int, optional) – default: 10

category (string, optional)
