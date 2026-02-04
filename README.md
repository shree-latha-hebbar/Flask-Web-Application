# Flask-Web-Application
A Flask web application with user authentication and personal note management. Users can sign up, log in, and securely store and delete their notes. Built using Flask, SQLAlchemy, and Jinja2.



Technologies used:

• Python  
• Flask  
• Flask-SQLAlchemy  
• Flask-Login  
• Jinja2 Templates  
• HTML/CSS


Installation Steps:


1. Download ZIP from GitHub
2. Extract it
3. Open the folder in terminal
4. Run:
   pip install -r requirements.txt
   python main.py
5. Visit http://127.0.0.1:5000


 Project Structure:

main.py           → Runs the Flask server
website/
│── auth.py       → Login & registration routes
│── views.py      → Main pages/routes
│── models.py     → Database models
│── templates/    → HTML files
│── static/       → CSS/JS files
requirements.txt  → Dependencies
