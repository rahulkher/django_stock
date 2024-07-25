
# Stock Portfolio Management System

## Project Description
The Stock Portfolio Management System is a web application designed to help users manage their stock portfolios. Users can add, view, and delete stocks from their portfolio, with real-time stock data fetched from the IEX Cloud API. The application is built with Django on the backend and Bootstrap for the frontend, providing a responsive and user-friendly interface.

## Technology Stack
- **Backend:** Django
- **Frontend:** HTML, Bootstrap
- **Database:** SQLite
- **APIs:** IEX Cloud API for real-time stock data

## Folder Structure
```
__pycache__/
migrations/
templates/
  ├── about.html
  ├── add_stock.html
  ├── base.html
  ├── delete_stock.html
  ├── home.html
__init__.py
admin.py
apps.py
forms.py
models.py
tests.py
urls.py
views.py
stocks/
  ├── __pycache__/
  ├── __init__.py
  ├── asgi.py
  ├── settings.py
  ├── urls.py
  ├── wsgi.py
db.sqlite3
manage.py
```

## Installation and Execution

### Prerequisites
- Python 3.x
- Django
- An API key from IEX Cloud (Replace `pk_a981c459352a4e17abc059d0cef5b16e` with your own API key in `views.py`)

### Installation
1. Clone the repository:
    ```sh
    git clone <repository-url>
    ```
2. Navigate to the project directory:
    ```sh
    cd <project-directory>
    ```
3. Install the required packages:
    ```sh
    pip install -r requirements.txt
    ```

### Execution
1. Apply migrations:
    ```sh
    python manage.py migrate
    ```
2. Run the server:
    ```sh
    python manage.py runserver
    ```
3. Open your web browser and navigate to `http://127.0.0.1:8000/`.

## Usage
- **Home Page:** Displays the current portfolio with real-time data. Enter a stock ticker symbol to get its current details.
- **Add Stock:** Navigate to the "Add Stock" page, enter the stock ticker symbol, and click "Add".
- **Delete Stock:** Navigate to the "Delete Stock" page, select the stock to delete, and confirm deletion.
- **About Us:** Information about the application and its purpose.

## Contributing
If you would like to contribute to this project, please fork the repository and submit a pull request.

## License
This project is licensed under the MIT License - see the LICENSE.md file for details.

## Contact
For any inquiries, please contact [Your Name] at [Your Email].
