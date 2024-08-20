Test Case 1: Valid Login Title: Successful login with valid credentials

Description: Verify that users can log in with correct username and password.

Preconditions:

User has a valid account with the system. Steps:

Navigate to the login page. Enter a valid username in the "Username" field. Enter the corresponding password in the "Password" field. Click the "Login" button. Expected Result:

User is redirected to the dashboard or home page. A success message or user’s name is displayed. Test Case 2: Invalid Username Title: Login attempt with an invalid username

Description: Verify that the system does not allow login with an incorrect username.

Preconditions:

User has a valid password but an invalid username. Steps:

Navigate to the login page. Enter an invalid username in the "Username" field. Enter a valid password in the "Password" field. Click the "Login" button. Expected Result:

An error message indicating "Invalid username or password" is displayed. User remains on the login page. Test Case 3: Invalid Password Title: Login attempt with an incorrect password

Description: Verify that the system does not allow login with an incorrect password.

Preconditions:

User has a valid username but an incorrect password. Steps:

Navigate to the login page. Enter a valid username in the "Username" field. Enter an incorrect password in the "Password" field. Click the "Login" button. Expected Result:

An error message indicating "Invalid username or password" is displayed. User remains on the login page. Test Case 4: Empty Fields Title: Login attempt with empty username or password fields

Description: Verify that the system prompts for both username and password if any field is left empty.

Preconditions:

User is on the login page. Steps:

Navigate to the login page. Leave the "Username" field empty and enter a valid password. Click the "Login" button. Repeat the steps leaving the "Password" field empty. Expected Result:

An error message indicating that both fields are required is displayed. User remains on the login page.
