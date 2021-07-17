# Django REST Framework & Docker

# Docker

- Installation and running means for applications.
- > With Docker it doesn’t matter if you are using a Mac, Windows, or Linux computer anymore. The entire development environment is isolated: programming language, software packages, databases, and more.

- > Docker is really just Linux containers which are a type of virtualization.
- Size and speed, are affected when it comes to virtualization.

## Vitruals machines are homes, Docker containers are apartments

- **Analogy**
  > Virtual Machines are like homes: stand-alone buildings with their own infrastructure including plumbing and heating, as well as a kitchen, bathrooms, bedrooms, and so on. Docker containers are like apartments: they share common infrastructure like plumbing and heating, but come in various sizes that match the exact needs of an owner.

# Containers vs Virtual Environments

- Virtual environments locally isolate Python software packages.
- > rely on a global, system-level installation of Python albeit they can refer to the proper version
- > we can’t run a production database or other services within virtual environments so compared to Docker containers they are far more limited

# Install Docker

- Docker's version should be at least 19
  > $ docker --version
  > Docker version 19.03.5, build 633a0ea

### Installation Check

- $ docker run hello-world
- $ docker info
- $ docker image ls

# Images and Containers

**Definitions**

- > An image is a snapshot in time of what a project contains.
- > A container is a running instance of the image.

- **Analogy**

  > A Dockerfile is the recipe for a cake
  > An image is a snapshot of the recipe at a given time
  > A docker-compose.yml says how to make the cake
  > And the container is the actual, baked cake

## Images

- defining the image with a Dockerfil, is very much like Pipenv or a requirements.txt file.
- >     # Dockerfile
        FROM python:3.7-alpine
- Dockerfiles are read from top-to-bottom.

### Image Builds

- > $ docker image build .

## Image Layers

- Image consist of multuple layers, such that the base layer is often a flavor of Linux, like alpine.
- **Why Image Layering>**
  - > Each image layer is immutable–unchanged–like a git commit. This helps ensure consistency when two developers build the same image.
  - > The second reason is performance. Docker caches the steps in a Dockerfile to speed up subsequent builds.

# Django REST Framework

- Used with Django web framework to create web APIs.
- Must be added to added to the project after Django itself has been installed and configured.

- > (library) $ pipenv install djangorestframework~=3.11.0
- The following apps must be added to the installed apps:

  >     # 3rd party
  >
  > 'rest_framework', # new

        # Local
      'books',

      'api', # new

- > The api app will not have its own database models so there is no need to create a migration file and run migrate to update the database.

- An end point shall be added to the api
  > urlpatterns = [
  > path('admin/', admin.site.urls),
  > path('api/', include('api.urls')), # new
  > path('', include('books.urls')),]

## Views

>      # api/views.py

    from rest_framework import generics

    from books.models import Book
    from .serializers import BookSerializer


    class BookAPIView(generics.ListAPIView):
        queryset = Book.objects.all()
        serializer_class = BookSerializer

## Serializers

- > A serializer translates data into a format that is easy to consume over the internet, typically JSON, and is displayed at an API endpoint.

### Browsable API

- > http://127.0.0.1:8000/api/
