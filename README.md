Learn django from Mozilla : https://developer.mozilla.org/zh-TW/docs/Learn/Server-side/Django

# Environment
- python 3.7.9
- sqlite

# Setup
1. Create and activate virtual environment and install library. (windows)
    ```
    py -m venv venv
    .\venv\Scripts\activate
    pip install -r requirements.txt
    ```
2. Migrate
    ```
    py manage.py makemigrations
    py manage.py migrate
    ```
3. Run 
    ```
    py manage.py runserver
    ```
4. Enter http://127.0.0.1:8000/ to see the home page or enter http://127.0.0.1:8000/admin to see the admin page
