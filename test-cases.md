# Test cases – automationexercise app

## TC-01 Register user with valid data

Preconditions:
User is on the home page

Steps:
1. Click on 'Signup/Login'
2. Enter valid name and email address
3. Click 'Signup'
4. Fill required account information with valid data
5. Click 'Create Account'

Expected result:
Account is created successfully and confirmation message is displayed

## TC-02 Register user with missing required fields

Preconditions:
User is on the registration form

Steps:
1. Click on 'Signup/Login'
2. Enter name and email
3. Click 'Signup'
4. Leave one or more required fields empty
5. Click 'Create Account'

Expected result:
Error message is displayed and account is not created

## TC-03 Login with valid credentials

Preconditions:
User has a registered account

Steps:
1. Click on 'Signup/Login'
2. Enter valid email and password
3. Click 'Login'

Expected result:
User is logged in successfully and redirected to the home page

## TC-04 Login with invalid credentials

Preconditions:
User is on login page

Steps:
1. Click on 'Signup/Login'
2. Enter invalid email and/or password
3. Click 'Login'

Expected result:
Error message is displayed and user is not logged in

## TC-05 Login with empty fields

Preconditions:
User is on login page

Steps:
1. Click on 'Signup/Login'
2. Leave email and password fields empty
3. Click 'Login'

Expected result:
Error message is displayed indicating required fields and user is not logged in

## TC-06 View product listing

Preconditions:
User is on the home page

Steps:
1. Navigate to 'Products' section
2. Observe the list of available products

Expected result:
Product list is displayed with relevant information such as name, price, and image

## TC-07 View product details

Preconditions:
User is on the product listing page

Steps:
1. Click on a product
2. Observe product detail page

Expected result:
Product detail page is displayed with correct information (name, price, description, image)

## TC-08 Navigate between sections

Preconditions:
User is on the home page

Steps:
1. Click on 'Products'
2. Click on 'Home'
3. Click on 'Signup/Login'

Expected result:
User can navigate between sections and each page loads correctly

## TC-09 Submit registration with invalid email

Preconditions:
User is on the registration form

Steps:
1. Click on 'Signup/Login'
2. Enter name and invalid email format
3. Click 'Signup'

Expected result:
Error message is displayed and registration is not allowed

## TC-10 Partial form submission

Preconditions:
User is on the registration form

Steps:
1. Click on 'Signup/Login'
2. Enter only name or only email
3. Click 'Signup'

Expected result:
System prevents submission and displays validation message
