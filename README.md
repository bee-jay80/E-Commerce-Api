# E-Commerce API

This is a Django-based backend project for an E-Commerce platform. It provides APIs for managing products, user authentication, shopping carts, and other e-commerce functionalities. The project is structured into multiple Django apps for modularity and scalability.

## Project Structure

## Features

- **Authentication**: User authentication and authorization using Django's built-in authentication system.
- **Product Management**: APIs for managing product data.
- **Shopping Cart**: Functionality for adding, removing, and managing items in a shopping cart.
- **REST API**: Built using Django REST Framework for easy integration with frontend applications.
- **CORS Support**: Configured with `django-cors-headers` to allow cross-origin requests.
- **Admin Panel**: Enhanced admin interface using `django-jazzmin`.

## Installation

1. Clone the repository:
   ```bash
   git clone <repository-url>
   cd E_commerce_Api
   ```

2. Create a virtual environment and activate it:
   ```python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```

3. Install dependencies:
   ```pip install -r requirements.txt
   ```

4. Apply migrations:
   ```python manage.py migrate
   ```

5. Run the development server:
   ```python manage.py runserver
   ```