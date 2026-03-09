# Checklist for login form
## Functional testing(positive)
* Refresh login page. Verify that Login form loads correctly. Should not happen: Form fields broken, page error.
## Functional testing(positive)
* Log in with valid credentials and verify that the user is redirected to the dashboard page, the session is active. Error message doesn't appear.
## Functional testing(positive)
* Enter valid email and password. Press enter. Verify that login request is executed and user is redirected to the dashboard page, the session is active.
## Functional testing(negative)
* Enter a registered email and an invalid password, click ‘Login’. Verify that an error message is displayed belove the password field, the user is not logged in, and the login page remains open.
## Functional testing(negative)
* Enter an invalid email and a valid password, click ‘Login’.
Verify that an error message is displayed belove the password field,
the user is not logged in, and the login page remains open.
## Functional testing(negative)
* Enter invalid email and password, click ‘Login’.
Verify that an error message is displayed belove the password field,
the user is not logged in, and the login page remains open.
## Functional testing(negative)
* Leave username and password fields empty - click ‘Login’. Verify that error message appears below the password field "Epic sadface: Username is required". User shouldn't login.
## Functional testing(negative)
* Leave username field empty, enter valid password, click ‘Login’. Verify that error message appears below the password field "Epic sadface: Username is required". User shouldn't login.
## Functional testing(negative)
* Leave password field empty, enter valid username, click ‘Login’. Verify that error message appears below the password field "Epic sadface: Password is required". User shouldn't login.
## Functional testing(negative)
* Enter locked user username and password credentials, click Login. Verify that error message appears below the password field "Epic sadface: Sorry, this user has been locked out." User should not login.
## UI/UX testing(positive)
* Click inside Username field. Verify that cursor appears and user can type. Username field should be clickable, input isn't blocked.
## UI/UX testing(positive)
* Open login page. Verify that logo image loads correctly (no broken image icon), 
logo is aligned according to design. Input fields and buttons are properly spaced. 
There are no overlapping or cut off elements.
## UI/UX testing(negative)
* Enter invalid login credentials, click 'Login', verify that an error message 
is shown belove the password field in red color and easy to notise. User is not logged in 
and the login page remains open.
## Input validation(positive)
* Enter letters, numbers, and special characters in Username field. Verify that field accepts valid characters. Application shouldn't crash and page shouldn't brake.
## Input validation(negative)
* Enter username with spaces after text and a valid password. Verify that system handles or trims spaces correctly. Login bahavior shouldn't be incorrect.
## Compatibility(positive)
* Open login page in Chrome browser. Enter valid credentials, click 'Login". Verify 
that user is successfully logged in, user is redirected to the dashboard page.
## Security(positive)
* Click on password field, enter any characters. Verify that entered 
characters are masked by dots, actual characters are not visible.
