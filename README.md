# Employee-Review-System
A full stack, app used for reviewing employee.



### Description

A full stack app, in which the admin, can assign the employees, to review each other on the basic of there work. The admin has special power, to make any other employee





After reaching the project directory you have to run the following the command.
   ```` 
        npm install 
        npm start || nodemon index.js
   ````

#### If you want to make an employee as admin then use the secret key : happy.

### Features

  You can review the employees. The admin has the special power to assing, the task to employee, remove the employee, add new admin, and also employee;
  
  
  # HomePage / Admin View

  # Home page / Employee view

  
  # Sign-Up


  # Sign-In

  # Forget Password
  
  # Assign Task

  # Employee List
  

  

### Folder Structure

```
Employee Review System
    |
    |               |--->css
    |--->assets---->|--->images
    |             
    |
    |               |--->flashMiddleware.js
    |--->config---->|--->mongoose.js
    |               |--->passport-local-Stradegy.js
    |
    |                  |-->admin_controller.js
    |--->controllers-->|-->home_controller.js
    |                  |-->review_controller.js
    |                  |-->user_controller.js
    |
    |               |-->review.js
    |--->models---->|
    |               |-->user.js
    |
    |              
    |               |-->admin.js
    |--->routes---->|-->index.js
    |               |-->review.js
    |               |-->user.js
    |
    |              |--->_header.ejs
    |              |---> addEmployee.ejs
    |              |---> admin.ejs
    |              |---> employe.ejs
    |--->views---->|--->forget_password.ejs
    |              |--->home.ejs
    |              |--->layout.ejs
    |              |--->sign_in.ejs
    |              |--->sign_up.ejs
    |
    |-->node_modules
    |-->.gitignore
    |--> index.js
    |--> package-lock.json
    |-->package.json
    
    ````
EXTRA
