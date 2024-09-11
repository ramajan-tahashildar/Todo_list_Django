# django-todo
 The Django-based Todo List project allows users to manage tasks through a web interface. This project demonstrates key Django features such as models, views, templates, and forms to implement CRUD (Create, Read, Update, Delete) operations on tasks. It also integrates user authentication, ensuring tasks are personal to each logged-in user.
## Demo
![image](https://github.com/ramajan-tahashildar/Todo_list_Django/blob/b1d40edcea8c091b9b3663ee81d6fed1aed7a8f9/Assets/TODO.png)
Once you have downloaded django, go to the cloned repo directory and run the following command

create virtual environment
```bash
$ python -m venv todo_venv
```
activate script
```bash
todo_venv/scripts/activate
```
 make migration 
```bash
$ python manage.py makemigrations
```

This will create all the migrations file (database migrations) required to run this App.

Now, to apply this migrations run the following command
```bash
$ python manage.py migrate
```

One last step and then our todo App will be live. We need to create an admin user to run this App. On the terminal, type the following command and provide username, password and email for the admin user
```bash
$ python manage.py createsuperuser
```

That was pretty simple, right? Now let's make the App live. We just need to start the server now and then we can start using our simple todo App. Start the server by following command

```bash
$ python manage.py runserver
```


Once the server is hosted, head over to http://127.0.0.1:8000/todos for the App.

Cheers and Happy Coding :)
