NAME: MASINA SREE KARSH

REFERENCE NUMBER: 23005860

DEPARTMENT: CSE(CYBER SECURITY)
# Ex-10-BOOTSTRAP
## Ex-10(a)
## AIM:
To create a Responsive feedback form for a virtual workshop on Constructing Modern Websites built with Bootstrap.

## DESIGN STEPS: 10(a)
### Step 1:
Initialize the HTML document.

### Step 2:
Create the body structure.

### Step 3:
Construct the form.

### Step 4:
Add a submit button and Link Bootstrap JavaScript.

## CODE: 10(a)
```
<!DOCTYPE html>
<html>
  <head>
    <title> Feedback Form | Virtual Workshop on Constructing Modern Websites</title>
    <link rel="stylesheet" href="style.css">
     <meta name="viewport" content="width=device-width, initial-scale=1.0">
   </head>
<body>
  <div class="container">
    <div class="title">Feedback</div>
    <div class="content">
      <form action="#">
        <div class="user-details">
         
 <div class="input-box">
            <span class="details">First Name</span>
            <input type="text" placeholder="Enter your 1st name" required>
            </div>

<div class="input-box">
            <span class="details">Last Name</span>
            <input type="text" placeholder="Enter your last name" required>
            </div>

          <div class="input-box">
            <span class="details">Email</span>
            <input type="text" placeholder="Enter your email" required>
          </div>

          <div class="input-box">
            <span class="details">Phone Number</span>
            <input type="text" placeholder="Enter your number" required>
          </div>
        </div>

        <div class="rating-details">
          <input type="radio" name="rate" id="dot-1">
          <input type="radio" name="rate" id="dot-2">
          <input type="radio" name="rate" id="dot-3">
          <input type="radio" name="rate" id="dot-4">
          <input type="radio" name="rate" id="dot-5">
          <span class="rate-title">Rating</span>

          <div class="category">
            <label for="dot-1">
            <span class="dot one"></span>
            <span class="rate">1</span>
          </label>

          <label for="dot-2">
            <span class="dot two"></span>
            <span class="rate">2</span>
          </label>

          <label for="dot-3">
            <span class="dot three"></span>
            <span class="rate">3</span>
            </label>

          <label for="dot-4">
            <span class="dot four"></span>
            <span class="rate">4</span>
            </label>

          <label for="dot-5">
            <span class="dot five"></span>
            <span class="rate">5</span>
            </label>

          </div>
        </div>
        <div class="button">
          <input type="submit" value="Post">
        </div>
      </form>
    </div>
  </div>
</body>
</html>

```
## OUTPUT:10(a):

![image](https://github.com/sreekarsh/ODD2023-WT-Ex-10-BOOTSTRAP/assets/139841918/5ab3b720-454b-4ddd-bf33-41120f57988e)

## RESULT:
This code creates a responsive feedback form for a virtual workshop on constructing modern websites built with Bootstrap.

# Ex-10(b)
## AIM:
 To create a Responsive student registration form for ABC Engineering College built with Bootstrap.

## DESIGN STEPS: 10(b)
### Step 1:
Initialize the HTML document with the necessary Bootstrap links.

### Step 2:
Create a container for the form and add a heading.

### Step 3:
Inside the form, create form groups for the student’s name, email, and gender.

### Step 4:
Add a submit button for the form.

### Step 5:
Link the Bootstrap JavaScript file at the end of the body.

## CODE: 10(b)

```
<!DOCTYPE html>
<html>
  <head>
    <title> Student Registration Form | ABC Engineering College </title>
    <link rel="stylesheet" href="style.css">
     <meta name="viewport" content="width=device-width, initial-scale=1.0">
   </head>
<body>
  <div class="container">
    <div class="title">Registration</div>
    <div class="content">
      <form action="#">
        <div class="user-details">
         
 <div class="input-box">
            <span class="details">First Name</span>
            <input type="text" placeholder="Enter your 1st name" required>
            </div>

<div class="input-box">
            <span class="details">Last Name</span>
            <input type="text" placeholder="Enter your last name" required>
            </div>

          <div class="input-box">
            <span class="details">Username</span>
            <input type="text" placeholder="Enter your username" required>
          </div>

          <div class="input-box">
            <span class="details">Email</span>
            <input type="text" placeholder="Enter your email" required>
          </div>

          <div class="input-box">
            <span class="details">Phone Number</span>
            <input type="text" placeholder="Enter your number" required>
          </div>

          <div class="input-box">
            <span class="details">Password</span>
            <input type="text" placeholder="Enter your password" required>
          </div>
          <div class="input-box">
            <span class="details">Confirm Password</span>
            <input type="text" placeholder="Confirm your password" required>
          </div>
        </div>
        <div class="gender-details">
          <input type="radio" name="gender" id="dot-1">
          <input type="radio" name="gender" id="dot-2">
          <input type="radio" name="gender" id="dot-3">
          <span class="gender-title">Gender</span>

          <div class="category">
            <label for="dot-1">
            <span class="dot one"></span>
            <span class="gender">Male</span>
          </label>

          <label for="dot-2">
            <span class="dot two"></span>
            <span class="gender">Female</span>
          </label>

          <label for="dot-3">
            <span class="dot three"></span>
            <span class="gender">Prefer not to say</span>
            </label>

          </div>
        </div>
        <div class="button">
          <input type="submit" value="Register">
        </div>
      </form>
    </div>
  </div>
</body>
</html>
```
## OUTPUT:10(b):

![image](https://github.com/sreekarsh/ODD2023-WT-Ex-10-BOOTSTRAP/assets/139841918/52892e69-a0b5-4285-9edd-27d637982f9c)


## RESULT:
This code creates a Responsive student registration form for ABC Engineering College built with Bootstrap.
# Ex-10(c)
## AIM:
To develope a program to structure vertical form layouts which handle form validation in bootstrap.

## DESIGN STEPS: 10(c)
### Step 1:
Initialize the HTML document with the necessary Bootstrap links.

### Step 2:
Create a container for the form and add a heading.

### Step 3:
Inside the form, create a form group for the name input field. Add the required attribute to the input field for validation.

### Step 4:
Add a submit button for the form.

### Step 5:
Add a script to handle the form validation on submit.

## CODE: 10(c)
``` 
<!DOCTYPE html>
<form>
<div class="form-group">
<div class="col-md-6">
<label for="valid01" class="form-label">Username</label>
<input type="text" class="form-control" id="valid01" required>
<div class="invalid-feedback">
Please provide a valid Username.
</div>
</div>
<div class="col-md-3">
<label for="valid02" class="form-label">Password</label>
<input type="text" class="form-control" id="valid02" required>
<div class="invalid-feedback">
Please provide a valid Password.
</div>
</div>
<div class="col-md-3">
<label for="valid03" class="form-label">Department</label>
<select class="form-select" id="valid04" required>
<option>Choose anyone Department</option>
<option>AIML</option>
<option>AIDS</option>
<option>IOT</option>
<option>CYBER SECURITY</option>
</select>
<div class="invalid-feedback">
Please select a valid Department.
</div>
</div>
<div class="col-md-9">
<label for="valid04" class="form-label">Mobile Number</label>
<input type="text" class="form-control" id="valid04" required>
<div class="valid-feedback">
December 2023 Unit - 5 Prepared by Dr.R.Selvakumar 27
19AI414 – Fundamentals of Web Application Development
Entered Details are correct.
</div>
</div>
<div class="col-md-9">
<label for="valid05" class="form-label">Designation</label>
<input type="text" class="form-control" id="valid05" required>
<div class="valid-feedback">
Entered Details are correct.
</div>
</div>
<div class="col-md-9">
<label for="valid06" class="form-label">E-Mail ID</label>
<input type="text" class="form-control" id="valid06" required>
<div class="valid-feedback"> Entered Details are correct.
</div>
</div>
<div class="col-md-3">
<label for="valid07" class="form-label">Term & Conditions </label>
<input type="checkbox" class="form-control" id="valid07" required>
<div class="invalid-feedback">
You must agree to terms and conditions before submitting...
</div>
</div>
<button type="button" class="btn btn-success"> Submit </button>

```
## OUTPUT:10(c):

![image](https://github.com/sreekarsh/ODD2023-WT-Ex-10-BOOTSTRAP/assets/139841918/076bd423-87c2-48e0-80dc-90670eacf348)


## RESULT:

This code develops a program to structure vertical form layouts which handle form validation in bootstrap.

# Ex-10(d)
## AIM:
 To create a basic email login form in Bootstrap with validation function.

## DESIGN STEPS: 10(d)
### Step 1:
Initialize the HTML document with the necessary Bootstrap links.

### Step 2:
Create a container for the form and add a heading.

### Step 3:
Inside the form, create a form group for the email input field. Add the required attribute to the input field for validation.

### Step 4:
Add a submit button for the form.

### Step 5:
Add a script to handle the form validation on submit.

## CODE: 10(d)
```
<!DOCTYPE html>
<html>
<head>
    <title>Login Form</title>
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.3.1/css/bootstrap.min.css">
</head>
<body>
    <div class="container">
        <h2 class="mt-5">Login Form</h2>
        <form class="needs-validation" novalidate>
            <div class="form-group">
                <label for="email">Email:</label>
                <input type="email" class="form-control" id="email" placeholder="Enter your email" name="email" required>
                <div class="invalid-feedback">Please enter a valid email.</div>
            </div>
            <button type="submit" class="btn btn-primary">Login</button>
        </form>
    </div>
    <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.3.1/js/bootstrap.min.js"></script>
    <script>
    (function() {
        'use strict';
        window.addEventListener('load', function() {
            var forms = document.getElementsByClassName('needs-validation');
            var validation = Array.prototype.filter.call(forms, function(form) {
                form.addEventListener('submit', function(event) {
                    if (form.checkValidity() === false) {
                        event.preventDefault();
                        event.stopPropagation();
                    }
                    form.classList.add('was-validated');
                }, false);
            });
        }, false);
    })();
    </script>
</body>
</html>

```
## OUTPUT: 10(d):

![image](https://github.com/sreekarsh/ODD2023-WT-Ex-10-BOOTSTRAP/assets/139841918/6f87cbdc-0c1e-4e2a-b3e8-dbd996ddd89a)

## RESULT:
This code creates a basic email login form in Bootstrap with validation function.
