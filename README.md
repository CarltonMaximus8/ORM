# Ex02 Django ORM Web Application
# Date:25/11/2025
# AIM
To develop a Django application to store and retrieve data from a bank loan database using Object Relational Mapping(ORM).

# DESIGN STEPS
## STEP 1:
Clone the problem from GitHub

## STEP 2:
Create a new app in Django project

## STEP 3:
Enter the code for admin.py and models.py

## STEP 4:
Execute Django admin and create details for 10 cars

# PROGRAM
```
admin.py

from django.contrib import admin
from .models import car,carAdmin


admin.site.register(car,carAdmin)

models.py

class car(models.Model):
    Company=models.CharField(max_length=20)
    Model=models.CharField(max_length=20)
    Colour=models.CharField(max_length=20)
    Price=models.IntegerField()
    DOM=models.DateField()

class carAdmin(admin.ModelAdmin):
    list_display=['Company','Model','Colour','Price','DOM']
```
# OUTPUT

<img width="1902" height="1030" alt="Screenshot 2025-11-25 224247" src="https://github.com/user-attachments/assets/2b3e9399-942d-4830-9d46-00c22248ec65" />
<img width="1917" height="1010" alt="Screenshot 2025-11-25 224348" src="https://github.com/user-attachments/assets/6c479e61-afd1-455a-86cc-45a7704ad563" />




# RESULT
Thus the program for creating a database using ORM hass been executed successfully
