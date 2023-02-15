# Form filling API for Mafia Statistics

## Installation

* Install dependencies
    ```bash
    pip install requirements.txt
    ```
* Set the following environment variables:
    ```text
    DB_USER
    DB_PASSWORD
    DB_HOST
    DB_PORT
    DB_NAME
    ```

## Running

* Run web-server (configure the port if you need)
    ```bash
    gunicorn --bind 0.0.0.0:8000 -w 1 -t 4 api.main:app
    ```
