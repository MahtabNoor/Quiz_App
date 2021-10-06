# Developing Django on Repl.it

- Fork this template to get started
- Simply hit run to start the server
- The server will autoreload as needed. You don't need to restart the server manually.

## Add your first view

1. Create a file under `mysite` named `views.py` with the following contents:

```
from django.http import HttpResponse


def index(request):
    return HttpResponse("Hello, world.")
```

2. Add a url pattern under `mysite/urls.py`. It should look like this:

```
from django.contrib import admin
from django.urls import path
from . import views

urlpatterns = [
    path('admin/', admin.site.urls),
    path('', views.index, name='index'),
]
```

## Shell

Django utilizes the shell for managing your site. For this click on the `?` in the lower-right corner and click "Workspace shortcuts" from there you can open a new shell pane. 

## Database

By default this template utilizes the sqlite database engine. While this is fine for development it won't work with external users of your app as we don't persist changes to files when they happen outside the development environment. 

We suggest bringing a database using an outside service. 


# FINALASSESMENT
1. Project Prerequisites :
This Django Quiz App requires a good knowledge of html, css, javascript, 
bootstrap, and  Python Django Framework. 
2.Tech Stack: 
FRONTEND- 
HTML
CSS
BOOTSTRAP
BACKEND-
PYTHON DJANGO
SQLITE (DATABASE)
3.Project description :
So here we have created 4 models or databases named Quiz, Question, Answer, 
and marks_of_user. In the Quiz model, the details related to the quiz is added 
like the name of the quiz etc. In the Question model as the quiz is the foreign 
key, it is possible to add a question with respect to the quiz we want.
It is possible to add the options and tick the correct option. Similarly in the 
Answer model question is a foreign key all the options are saved with their 
Boolean values and with respect to the particular question. Finally, in the marks 
of the user model the name of the user, the user’s marks, and the name of the 
quiz given by user is saved.
When a super user is created using create superuser command in the prompt an 
Admin is made.
Admin can add a new quiz.
Add new Question and delete question.
4. Project Set up details:
Insatllation of Python , Anaconda prompt,  Django framework, chrome or any 
other browser, Text editor like atom or notepad

