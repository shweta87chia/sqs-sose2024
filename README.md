# Flask Web Application

This is a robust web application built with Flask, featuring comprehensive testing and secure, performant interactions with third-party APIs.

## Features

- User Management
- Database Integration with SQLAlchemy
- Third-Party API Interaction
- Comprehensive Testing (Unit, Integration, E2E, Security, Performance)

## Setup

1. **Clone the repository:**

    ```bash 
    https://inf-git.fh-rosenheim.de/studsaxesh6537/python-flask-sqs.git
   
    
    ```

2. **Set up a virtual environment:**

    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows use `venv\Scripts\activate`
    ```

3. **Install the dependencies:**

    ```bash
    pip install -r requirements.txt
    ```



4. **Run the application:**

    ```bash
    flask run
    ```

## Running Tests

- **Unit Tests:**

    ```bash
    pytest tests/
    ```

- **Performance Tests:**

    ```bash
    locust -f locustfile.py
    ```

## Additional Information

For more details on how to use this application and contribute, please refer to the [documentation](docs/).

