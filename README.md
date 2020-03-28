# Flask-project1
This project will help in creating a localhost database.
also: 

use the following commands:
1. pip install flask- will install flask at the beginning
2.pip install virtualenv venv -will install virtual environment
3.pip install flask_SQLAlchemy -this will be apart of your imports at the begining of app.py so you have to install it on your terminal
4.run on python ... from app import db
5.db.create_all() -to create your localhost db
6.Adding some users i.e- user1=User-which is classname  then (username="salma",email="salma@gmail.com")
7.updating it to the database---- db.session.add(user1)
8.commiting it to the database---- db.session.commit()
9.To query the database.. db.query.all() //shows all the users you have created.
