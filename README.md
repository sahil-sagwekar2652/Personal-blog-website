# Personal blog website 👨‍💻

A simple blog website made using Flask, HTML, CSS and Bootstrap
with PostgreSQL database and deployed on Heroku.


## Badges 🏷


![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![Flask](https://img.shields.io/badge/flask-%23000.svg?style=for-the-badge&logo=flask&logoColor=white)
![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white)
![Bootstrap](https://img.shields.io/badge/bootstrap-%23563D7C.svg?style=for-the-badge&logo=bootstrap&logoColor=white)
![Heroku](https://img.shields.io/badge/heroku-%23430098.svg?style=for-the-badge&logo=heroku&logoColor=white)
![Postgres](https://img.shields.io/badge/postgres-%23316192.svg?style=for-the-badge&logo=postgresql&logoColor=white)
## Lessons Learned 📚

This is my first fully functional web project. I learned to use the Flask web framework through the process of creating a quick and simple backend.

Implementing **user authentication** with flask and password hashing.

Experimented with relational databases and learned to perform 
CRUD operations through an Object-relational mapper (SQL-Alchemy) in Python.


## Environment Variables 🔐

To run this project, you will need to add the following environment 
variables to your virtual environment

`SECRET_KEY` - Flask app secret key



## Deployment 🌏

Clone the repository on your terminal and run the following commands.  
**Requirements:** You must have **Python** 🐍 installed.


![Windows Terminal](https://img.shields.io/badge/Windows%20Terminal-%234D4D4D.svg?style=for-the-badge&logo=windows-terminal&logoColor=white)

### Creating a virtual environment
* _if virtualenv is not already installed, run the following command or else skip to the next one_

```cmd
    > pip install virtualenv 
```
* _create and activate a new venv inside the project directory_
```cmd
    > virtualenv myenv
    > myenv\Scipts\activate
```
### Deploying on LocalHost
```cmd
    > python main.py
```
* _Copy and paste the localhost link in your browser to view the project._
