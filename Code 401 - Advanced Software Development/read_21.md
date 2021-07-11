# Django - Models

> Models define the structure of stored data, including the field types and possibly also their maximum size, default values, selection list options, help text for documentation, label text for forms, etc

- Django apps uses models to access and manage data
- Models basically refers to the database, the tables of data/information about objects.

## Model Relationships:

- one to one (OneToOneField)
- one to many (ForeignKey)
- many to many (ManyToManyField)

# Model primer

- model is Djngo are defined in models.py file, in created app.
- > from django.db import models

## Feature Inside Models

- **Fields**: Data attribute - column
  - > my_field_name = models.CharField(max_length=20, help_text='Enter field documentation')
  - Common field arguments:
    - primary_key
    - help_text
    - default
    - choices
- **Metadata**
  - Data about models
  - Meta data are defined throug :
    > class Meta:
        ordering = ['-my_field_name']
- **Methods**

  - minimally you should include str method in model, makes data readable for humans.

    - > def **str**(self):
      > return self.field_name

  - get_absolute_url(), is another common method

    - > which returns a URL for displaying individual model records on the website (if you define this method then Django will automatically add a "View on Site" button to the model's record editing screens in the Admin site).

    - def get_absolute_url(self):
      """Returns the url to access a particular instance of the model."""
      return reverse('model-detail-view', args=[str(self.id)])

## Model management

- Managing model basically includes, updating, or deleting records, and running select queries.

### Creating and modifying records

> - Create a new record using the model's constructor.

    record = MyModelName(my_field_name="Instance #1")

    - Save the object into the database.
    record.save()

### Searching for records

- search is done using attributes of the object
- _Getting All Records_
  - QuerySet --> objects.all()
- _Getting Specific Records Based on a Criteria_
  - QuerySet --> filter()

# Defining the LocalLibrary Models

> from django.db import models
> from django.urls import reverse
> import uuid
