# Django
Django Basics

## Django
- Django?
  - ***Django : The Web Framework for perfectionist with deadlines!***
  - Use Python in backend
  - Django has capability to render Json response.
  - Separate Functionlity to web Applications
  - Helps in Separe websites to different different apps
  - Database pull information like performing CRUD Operations the we need a connecter to database
  - Django make wasy to create website, with this framework
  - Django Based on Python, means Machine Learning, Artificial Intelligence, Data Science, Tensorflow is in python.
- Why we use Django? already HTML, CSS and JavaScript


## Installation
***
  1. Python on your device
  2. Django
  3. Open Powershell in your Folder [rightClick]+shift for windows
  4. ``` pip install django```
  5. ``` pip install django --version ```
  6. Folder open with VSCode
  7. Go To Extension and Search **django** [Baptiste Darthenay] first one
  8. Also Install **python** [microsoft]
  9. Django Documentation
  10. [Django](https://www.djangoproject.com/start/) 
 
## Get Started With Django
***
   - Create a Project
   - ``` django-admin startproject project_name```
   - Your project will added with multiple files by django-admin
     - Project_Name Folder
       - init.py
       - setting.py
       - urls.py
     - manage.py
   - Terminal
   - ``` python manage.py runserver```
   - Now your server start & you have a port
   - [http://127.0.0.1:8000](http://127.0.0.1:8000) open it It say Django Worked Successfully!

## HTML & Django, How websites works?
***
   - Basic Requirements to build a website
     - HTML
     - CSS
     - JavaScript
   - Django is not a basic requirement to build a website. It's a platform which help us to make websites in easier way.
   - Django provides facilities like Rendering Website, Interact with Database etc
   
   * HTML - Basic Structure Skeleton
   * CSS - Design, Color, look & fell etc
   * JavaScript - Making it Funtional, like Engine etc
 
## How Website Work?
***
   - ![Websitework](websiteWorking.jfif)
   - **Client Request** for a website through a link [Youtube](https://www.youtube.com/) to **WebServer** , Webserver process the request and If website found it webserver return HTML+CSS+JS as a **Response** to client on the browser Now It's Browser responsibility to render all the stuff if not found gives 404 Not Found Error.
   - Browers convert the source code which is not understable by normal human being who is not a developer and render too fast even user not experience it.
  
## HTML
***
   - HTML stands for Hyper Text Markup Language
   - It's a standard markup language for giving a static skeleton to Web applications or Websites
 
## CSS
***
   - CSS stands for cascading Style Sheets
   - It's a style sheet language that is used to handle the presentation of a webpage containing HTML
   - Makes Look & Feel of website beautiful
   - CSS3 also provides features like Animation etc
 
## JavaScript
***
   - JavaScript is a high-level dynamic interpreted programming language
   - It allows clients-side scripting to create completely dynamic web applications or websites
   - Button Click, Add Item in cart, Amount Change - Within Clients means within Browers
  
## Django
***
   - ***Django is a free and opensource web application framework written in Python***
   - Django offers a big **collection of modules** which you can use in your own projects
   - Django is also a framework. Primarily, frameworks exist to save developer community a lot of waste time and Headache.
   - Suppose you have a blog website and you have a 1000 of blogs Now you create 1000 html, CSS and JS pages for each it's too lengthy not feasible. We want to save the template of blog and render text from database.
   - Django have their own **Database Connecter**
   - Serve Json Response, Static file,media-file and changes in database using Django.
   - URL Dispatcher

## MVT architecture of Django
***

   - MVT stands for Model View Template is a software design pattern.
   - This View is used to execute the **Business Logic** and Interact with a Model to carry Data & render a template.
   - There is no separate **Controller** Here Complete Application is based on ModelView Template
   - ![MVT](mvt.jfif)
   - A project has a single website and a website has a multiple apps like Home, Contact, Blog, shop etc because we want our concern should be separate.
   - Model
      - If you want to create Database contains Emp_Id, Emp_Name, Address, Contact etc save them 
      - Write a Python class for like field Character, Integer, primary key etc 
   - View
      - View is the look
      - View is associated with a template
      - Basically it pull data from Model at runtime and process it and send Data to Template and template render Data
      - View is only one eiher we have 1 page or 1000 pages
   - Template
      - Template get data from view and render the data accordingly
      - Template has basically a template which has placehoder for title, contents etc.
      - Like HTML,CSS and Javascript but use **Django Templating Engine**
      - Templating Engines process the placeholders of Template which comes at runtime.
    - URL
      - Django Dispatcher decides whether to send urls
    
    
 ## Understand Django
   - Project_Name Folder
      - To add urls you have to edit **urls.py**
      - Request first come in Project's **urls.py** and from here send to any others app **urls.py** 
      - ```python
           urlpatterns = [
            path('admin/', admin.site.urls),
          ]```
      - Project vs App
     

    
