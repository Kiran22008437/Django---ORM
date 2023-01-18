# Django ORM Web Application

## AIM
To develop a Django application to store and retrieve data from a database using Object Relational Mapping(ORM).

## Entity Relationship Diagram

Include your ER diagram here

## DESIGN STEPS

### STEP 1:To creat admin account enter the following command to creat a superuser:

### STEP 2:Add the username and email for the superuser

### STEP 3:The next prompt in the shell is for your password.add a strong passsword.add strong password and press the enter key to cnfirm it once again:

Write your own steps

## PROGRAM
```	Model.py

from django.db import models
form django.contrib import admin
class Employee (model.Model):
	eid=models.charFiel(max_lengeth=20,help_text="Employee ID")
	name=models.charfield(max_lengeth+=100)
	salary=models.integerfield()
	age=models.integerfield()
	email=model.s Emailfield()
	
class employeeAdmin(admin.modelAdmin):
	list_display=('eid','name','salary','age','email')

admin.py

from django.contrib import admin
form.models import employee,employeeadmin
admin.site.register(Employee,EmployeeAdmin) ```



## OUTPUT
![kiran 22008437 ](https://user-images.githubusercontent.com/118668751/213098097-3a65007f-f467-4a82-99a5-0a460b1c1438.png)

Include the screenshot of your admin page.


## RESULT
