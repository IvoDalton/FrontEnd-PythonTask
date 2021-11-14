# FrontEnd-PythonTask
Made some corrections at these positions:
In the __main__.py file,instead of : from task.backend.app import setup_app  line was changed with :from app import setup_app
In the app.py file ADDED at line 3: from flask_cors import CORS(installed CORS) ,at line 11 added: CORS(app)
In the main folder created new __init__.py file.
