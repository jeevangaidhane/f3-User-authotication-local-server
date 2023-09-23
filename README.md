# User-Authentication-using-Local-Storage
creating a user authentication page with form validation
Project Overview: User Authentication using Local Storage
UI Reference
Figma Link- https://www.figma.com/file/b6eP7qojPEj7sKVVpBtiI7/F3---Auth-Contest?type=design&node-id=0%3A1&mode=design&t=nj3dPCKRUSAfpHAi-1

Task Description
You are tasked with creating a User Authentication system using local storage. You will create a user interface as depicted in Figma, with two pages: "Signup" and "Profile."

On the "Signup" page, collect user details and store them in local storage. The state of the user stored in local storage should include an access token, which should be a random 16-byte string that you generate.

After a successful signup, redirect the user to the "Profile" page and display their details there.

On the "Profile" page, include a "Logout" button. Clicking this button should clear the local storage (including the access token) and redirect the user to the "Signup" page.

Use JavaScript to ensure that users cannot manually navigate to the "Profile" page unless they are logged in (i.e., an access token is present in local storage). Similarly, prevent logged in users from manually navigating to the "Signup" page.

In both success and failure scenarios, display appropriate messages as shown in the UI design. All fields should be mandatory during signup. After a successful signup, display a success message and then redirect the user to the "Profile" page.

Features
Signup Page: Create a signup page as shown in the Figma design. All fields should be mandatory.
User State: On signup, store the user's details in local storage. This should include an access token (a randomly generated 16-byte string).
Profile Page: Create a profile page as shown in the Figma design. On this page, display the details of the user stored in local storage.
Logout: Implement a "Logout" button on the profile page. When clicked, clear the local storage and redirect the user to the signup page.
Access Control: Implement access control using JavaScript. If a user tries to manually navigate to the "Profile" page without an access token in local storage, redirect them to the signup page. Similarly, if a user with a valid access token tries to manually navigate to the "Signup" page, redirect them to the profile page.
Success and Error Messages: Display appropriate success and error messages as shown in the UI design.
Marking Scheme (100 Marks)
Signup Page - 15 Points
Proper creation of the signup page as per the Figma design
All fields on the signup page should be mandatory

User State - 20 Points
Successful storage of user details in local storage upon signup
Generation and storage of a random 16-byte access token

Profile Page - 20 Points
Proper creation of the profile page as per the Figma design
Successful display of user details from local storage on the profile page

Logout - 10 Points
Correct implementation of the "Logout" button, which should clear the local storage and redirect the user to the signup page

Access Control - 25 Points
If a user tries to navigate to the "Profile" page without an access token, they should be redirected to the signup page
If a logged-in user tries to navigate to the "Signup" page, they should be redirected to the profile page

Success and Error Messages - 10 Points
Proper display of success and error messages as per the UI design
After a successful signup, a success message should be displayed and the user should be redirected to the "Profile" page
