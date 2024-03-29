# Londonloox E-Commerce Website

Londonloox is an e-commerce website that offers a seamless shopping experience for both registered users and guests. Our goal is to make online shopping easy and secure, providing a wide range of products for your convenience.

[Live App](https://leona05.pythonanywhere.com/)

![Screenshot (78)](https://github.com/LeonaMussie/Project-4-ecommerce/assets/91215248/5d0e46ab-84e4-4bd1-ac92-f9a9da9a3c33)
![Screenshot (79)](https://github.com/LeonaMussie/Project-4-ecommerce/assets/91215248/8cc71343-7641-4f47-b087-32f55f7a969e)
![Screenshot (80)](https://github.com/LeonaMussie/Project-4-ecommerce/assets/91215248/580bf1c2-094b-451b-b1d4-a41cb1b73183)
![Screenshot (82)](https://github.com/LeonaMussie/Project-4-ecommerce/assets/91215248/b0cbc676-e082-4305-a5d0-0200680ff203)


## Table of Contents
- [Technologies](#technologies)
- [Website Features](#website-features)
- [Local Usage](#local-usage)
- [Deployment on PythonAnywhere](#deployment-on-pythonanywhere)

## Technologies
Londonloox is built using the following technologies:
- **HTML5**: For structuring web pages.
- **CSS**: For styling and layout.
- **Bootstrap**: A popular CSS framework for responsive design.
- **Django**: A high-level Python web framework for building web applications.
- **SQLite**: A lightweight database management system.

## Website Features
Londonloox offers a variety of features to enhance your shopping experience:
- **Store Page**: Browse our extensive collection of products.
- **Register Page**: Create an account to access exclusive features and order history.
- **Login Page**: Sign in to your account to view your cart and previous orders.
- **Cart Page**: Review the items in your cart, update quantities, and proceed to checkout.
- **Checkout Page**: Enter shipping information and payment details.
- **Add and Remove Buttons**: Easily manage your cart with the option to add and remove items.
- **PayPal**: Secure payment processing through PayPal.

## Local Usage
To run Londonloox locally, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/londonloox.git
   
2. Navigate to the project directory:
   ```bash
   cd londonloox

3. Create a virtual environment (optional but recommended):
   ```bash
   python -m venv venv

4. Install the project dependencies:
   ```bash
   pip install -r requirements.txt

5. Apply the database migrations:
    ```bash
    python manage.py migrate

6. Create a superuser account (for admin access):
   ```bash
   python manage.py createsuperuser

7. Run the development server:
   ```bash
   python manage.py runserver

8. Access the website in your web browser at `http://localhost:8000`.

## Deployment on PythonAnywhere

Londonloox can be deployed on PythonAnywhere, a popular platform for hosting Python web applications. Follow these steps to deploy your Londonloox project:

1. Sign up for a PythonAnywhere account (if you don't have one).

2. Create a new web app on PythonAnywhere.
  
3. Set up a virtual environment on PythonAnywhere (similar to the local usage steps).

4. Upload your Londonloox project files to your PythonAnywhere account.

5. Install the project dependencies.

6. Apply the database migrations.

7. Configure your PythonAnywhere web app to use the WSGI file from your Londonloox project.

8. Reload your web app, and it should be live at the provided URL.
   
***
Created By: Leona Mussie<br/>
