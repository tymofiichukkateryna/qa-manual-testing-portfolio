
Test Case ID	Test Case Name	Module/Feature	Description	Pre-condition	Test Steps	Expected Result	Actual Result	Status	Post-conditions	Priority
Log in form										
TC_LOGIN_01	Verify Login Form Loads Correctly After Page Refresh	Login Form	Verify that the login form loads correctly after refreshing the login page	User has access to the login page	"1.Open the login page https://www.saucedemo.com/
2. Refresh the page (press F5 or click browser refresh button)
3. Observe the login form after the page reloads.
4. Verify Username field, Password field, and Login button are displayed and functional."	Login page reloads successfully and the login form (Username field, Password field, Login button) is displayed correctly	Login page reloads successfully and the login form (Username field, Password field, Login button) is displayed correctly	Pass	Login page remains open and ready for login.	Medium
TC_LOGIN_02	Login with valid credentials	Login	Verify that the user can successfully log in with valid credentials and is redirected to the products page.	User has access to the login page. Valid credentials are available.	"1.Open the login page https://www.saucedemo.com/
2. Enter valid username in the Username field and valid password in the Password field
3. Click Login button"	User is successfully logged in and redirected to the Products page. User session becomes active. No error message is displayed.	User is successfully logged in and redirected to the Products page. User session becomes active. No error message is displayed.	Pass	User remains logged in and can interact with the product catalog.	High
TC_LOGIN_03	Login with valid credentials using Enter key	Login	Verify user can log in with valid credentials using Enter key	User has access to the login page	"1. Open login page  https://www.saucedemo.com/
2. Enter valid username and password
3. Press Enter"	User is redirected to Products page, session becomes active, no error message appears.	User is redirected to Products page, session becomes active, no error message appears.	Pass	User remains logged in	High
TC_LOGIN_04	Login with registered email and invalid password	Login	Verify login fails with incorrect password	User is on login page https://www.saucedemo.com/	"1. Enter valid username.
2. Enter invalid password.
3. Click Login."	Error message "Epic sadface: Username and password do not match any user in this service" displayed below password field. User remains on login page.	Error message "Epic sadface: Username and password do not match any user in this service" displayed below password field. User remains on login page.	Pass	User remains logged out	High
TC_LOGIN_05	Login with invalid email and valid password	Login	Verify login fails with invalid username	User is on login page https://www.saucedemo.com/	"1. Enter invalid username.
2. Enter valid password.
3. Click Login."	Error message "Epic sadface: Username and password do not match any user in this service" displayed below password field. User remains on login page.	Error message "Epic sadface: Username and password do not match any user in this service" displayed below password field. User remains on login page.	Pass	User remains logged out	High
TC_LOGIN_06	Login with invalid username and password	Login	Verify login fails with invalid credentials	User is on login page https://www.saucedemo.com/	"1. Enter invalid username.
2. Enter invalid password.
3. Click Login."	Error message "Epic sadface: Username and password do not match any user in this service" displayed below password field. Login does not occur.	Error message "Epic sadface: Username and password do not match any user in this service" displayed below password field. Login does not occur.	Pass	User remains logged out	High
TC_LOGIN_07	Login with empty username and password	Login	Verify validation when fields are empty	User is on login page https://www.saucedemo.com/	"1. Leave username and password fields empty.
2. Click Login."	Error message “Epic sadface: Username is required” displayed. Login does not occur.	Error message “Epic sadface: Username is required” displayed. Login does not occur.	Pass	User remains logged out	High
TC_LOGIN_08	Login with empty username	Login	Verify validation for missing username	User is on login page https://www.saucedemo.com/	"1. Leave username field empty.
2. Enter valid password.
3. Click Login."	Error message “Epic sadface: Username is required” displayed. Login does not occur.	Error message “Epic sadface: Username is required” displayed. Login does not occur.	Pass	User remains logged out	High
TC_LOGIN_09	Login with empty password	Login	Verify validation for missing password	User is on login page https://www.saucedemo.com/	"1. Enter valid username.
2. Leave password field empty.
3. Click Login."	Error message “Epic sadface: Password is required” appears. Login does not occur.	Error message “Epic sadface: Password is required” appears. Login does not occur.	Pass	User remains logged out	High
TC_LOGIN_10	Login with locked user account	Login	Verify locked user cannot log in	User is on login page https://www.saucedemo.com/	"1. Enter locked user username.
2. Enter password.
3. Click Login."	Error message “Epic sadface: Sorry, this user has been locked out.” appears. User remains on login page.	Error message “Epic sadface: Sorry, this user has been locked out.” appears. User remains on login page.	Pass	User remains logged out	High
TC_LOGIN_011	Username field input	Login UI	Verify username field accepts input	User is on login page https://www.saucedemo.com/	"1. Click username field.
2. Enter text."	Cursor appears and user can type.	Cursor appears and user can type.	Pass	Text remains in field	Medium
TC_LOGIN_012	Login page UI layout	Login UI	Verify layout elements load correctly	User is on login page https://www.saucedemo.com/	"1. Open login page.
2. Observe logo, fields and buttons."	Logo loads correctly. UI elements aligned. No overlap and cut off elements.	Logo loads correctly. UI elements aligned. No overlap and cut off elements.	Pass	Page remains open	Medium
TC_LOGIN_013	Error message UI	Login UI	Verify error message visibility	User is on login page https://www.saucedemo.com/	"1. Enter invalid credentials.
2. Click login."	Error message appears in red color below password field.	Error message appears in red color below password field.	Pass	User remains on login page	Medium
TC_LOGIN_014	Username input validation	Login Input	Verify username field accepts characters	User is on login page https://www.saucedemo.com/	1. Enter letters, numbers, special characters in username field.	Field accepts characters and system works normally.	Field accepts characters and system works normally.	Pass	Field contains entered text	Medium
TC_LOGIN_015	Username with trailing spaces	Login Input	Verify system handles spaces	User is on login page https://www.saucedemo.com/	"1. Enter username with trailing spaces.
2. Enter valid password.
3. Click Login."	System trims spaces or handles login correctly. User is successfully logged in and redirected to the Products page. User session becomes active. No error message is displayed.	Error message "Epic sadface: Username and password do not match any user in this service" is shown below the passworf field. User remains on login page	Failed	User logged in	Medium
TC_LOGIN_016	Login in Chrome browser	Compatibility	Verify login page works correctly in Chrome browser	User is on login page https://www.saucedemo.com/ and has valid credentials	"1. Open login page in Chrome browser.
2. Enter valid username and password.
3. Click Login."	User is successfully logged in and redirected to the Products page.	User is successfully logged in and redirected to the Products page.	Pass	User logged in	Medium
TC_LOGIN_017	Password masking	Login Security	Verify password characters are hidden	User is on login page https://www.saucedemo.com/ 	"1. Click password field.
2. Enter password."	Password characters appear as dots (••••).	Password characters appear as dots (••••).	Pass	Password field contains masked input	Medium
<img width="2583" height="1404" alt="image" src="https://github.com/user-attachments/assets/46543ae7-4935-49d6-bf52-0b086a442b43" />
