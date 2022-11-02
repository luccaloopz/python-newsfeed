# Python Newsfeed

[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](https://opensource.org/licenses/MIT)

## **Description**
The purpose of this project was to refactor the back-end of a full stack application originally built in Node.js to use Python instead. Users are able to create their own account, submit links to tech-related articles, comment on other user's articles, and upvote articles.  

## **Deployed Application Link**

Click on the following link to be redirected to the deployed application:
https://my-tech-news.herokuapp.com/ 

## **Technologies**

* ![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white)
* ![CSS3](https://img.shields.io/badge/css3-%231572B6.svg?style=for-the-badge&logo=css3&logoColor=white)
* ![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E)
* ![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
* ![MySQL](https://img.shields.io/badge/mysql-%2300f.svg?style=for-the-badge&logo=mysql&logoColor=white)
* ![Flask](https://img.shields.io/badge/flask-%23000.svg?style=for-the-badge&logo=flask&logoColor=white)
* ![Jinja](https://img.shields.io/badge/jinja-white.svg?style=for-the-badge&logo=jinja&logoColor=black)



## **Installation**
First, you'll want to clone down this repository onto your local machine. You can do this by copying the code within the green code button towards the upper-righthand side of the screen and typing out `git clone *insert your copied code here*` within Windows PowerShell.

Next, you'll want to type the following in the command line. This creates the vitual environment. 
```
python -m venv venv
```

Next, type the following into the command line to lauch the virtual environment:
```
./venv/Scripts/activate
```

Next, type the following into the command line to install dependencies:
```
pip install -r requirements.txt
```

Next, create a .env file in the root of your project and add the following. Replace PASSWORD with your password to your root MySQL user:
```
DB_URL=mysql+pymysql://root:PASSWORDd@localhost/python_news_db

```

Seed the database:
```
python seeds.py
```

Lastly, you'll want to start the server locally. You can do this by typing the following within the command line at the root of this project directory.
```
python -m flask run
```

## **Application**
Here's what the home page of the application looks like:

![screenshot](./assets/homepage.PNG)

Here's what the dashboard looks like:

![screenshot](./assets/dashbaord.PNG)

Here's what the edit page looks like:

![screenshot](./assets/edit-post.PNG)

## **License**
The following application is covered under the MIT License.