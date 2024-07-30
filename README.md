# Library Management System

This is a Django-based library management system that allows for the management of books, members, and book loans. The project uses HTML and CSS for the front end and SQLite for the database.

## Features

- **Book Management:** Add, update, delete, and view books.
- **Member Management:** Add, update, delete, and view library members.
- **Book Loans:** Issue and return books to members.

## Technologies Used

- **Backend:** Django
- **Frontend:** HTML, CSS
- **Database:** SQLite

## Installation

Follow these steps to set up the project locally:

1. **Clone the Repository:**

    ```sh
    git clone https://github.com/79mohan7981/library-management-system.git
    cd library-management-system
    ```

2. **Create a Virtual Environment (Optional but recommended):**

    ```sh
    python -m venv env
    source env/bin/activate  # On Windows use: env\Scripts\activate
    ```

3. **Install Dependencies:**

    Install the required Python packages using pip:

    ```sh
    pip install -r requirements.txt
    ```

4. **Apply Migrations:**

    Set up the database by applying migrations:

    ```sh
    python manage.py makemigrations
    python manage.py migrate
    ```

6. **Run the Development Server:**

    Start the Django development server:

    ```sh
    python manage.py runserver
    ```

    Open your web browser and go to `http://localhost:8000` to access the application.

## Usage

- **Admin Interface:** Access the Django admin interface at `http://localhost:8000/admin` to manage books and members.
- **User Interface:** Use the web interface to browse books, issue or return books, and manage members.

## Project Structure

