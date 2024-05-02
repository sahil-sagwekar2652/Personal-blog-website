# Personal blog website 👨‍💻

- A blog website made using Flask, HTML, CSS and Bootstrap
with PostgreSQL database and NGINX web-server and deployed using Docker on AWS EC2.
- Designed using micro-services pattern, implemented CICD for seamless updates.

![flask_blog_cicd](https://github.com/sahil-sagwekar2652/Personal-blog-website/assets/89456541/c6ff4a20-839c-4255-bcf3-dc6846572f9e)

## Badges 🏷
[![My Skills](https://skillicons.dev/icons?i=py,flask,postgres,nginx,docker,aws,githubactions)](https://skillicons.dev)


## Features
1. **Self-hosted on AWS EC2.**
2. **Micro-Services architecture using Docker containers.**
3. **Setup HTTPS using Let's Encrypt.**
4. **Implemented CICD using GitHub Actions.**



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
