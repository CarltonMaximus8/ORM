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

# OUTPUT

<img width="1919" height="1079" alt=<img width="1917" height="1010" alt="image" src="https://github.com/user-attachments/assets/1715a124-5a99-4946-8dd8-9241788ff380" />
 />

<img width="1920" height="1080" alt=<img width="1902" height="1030" alt="Screenshot 2025-11-25 224247" src="https://github.com/user-attachments/assets/ebb27e9e-8df7-48c1-8823-576173222f46" />
" />

# RESULT
Thus the program for creating a database using ORM hass been executed successfully
