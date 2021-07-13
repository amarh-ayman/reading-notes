# Django Best Practices: Custom User Model

- According to Django's official documentation, it is preferred to use a custom user model, for more flexibility.
- > a general rule, always use a custom user model for all new Django projects.

## Setup

### creating a new Django project

> create and navigate into a dedicated directory called accounts for our code

    install Django
    make a new Django project called config
    make a new app accounts
    start the local web serve

## AbstractUser vs AbstractBaseUser

> In both cases we can subclass them to extend existing functionality however AbstractBaseUser requires much, much more work.

## Custom User Model

> update config/settings.py

    create a new CustomUser model
    create new UserCreation and UserChangeForm
    update the admin

## Superuser

> $ python manage.py createsuperuser

## Templates/Views/URLs

> Our goal is a homepage with links to log in, log out, and sign up. Start by updating settings.py to use a project-level templates directory.
> Then set the redirect links for log in and log out, which will both go to our home template. Add these two lines at the bottom of the file.
> Create a new project-level templates folder and within it a registration folder as that's where Django will look for the log in template. We will also put our signup.html template in there.
> Then create four templates:
> urls
> views
