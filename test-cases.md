# Test cases – AutomationExercise app

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

Expected Result:
User is logged in successfully and redirected to the home page


