# PIWorksQ5Answer

User Management Screen Specification Document

This screen allows us to list, filter and sort the existing users and add new users to our system.

Requirements:
1) List all users.
2) List all active users by hiding disabled users with a checkbox.
3) Filter the users and show the new list.
4) Sort the users and show the new list.
5) Add new users to the system by getting their credentials in the user registiration screen.

Components and Their Behaviour
1) Top Bar
    1) New User Button: Prompts or shows the user registiration menu.
    2) Hide Disabled Users Checkbox: A checkbox to hide disabled users from the "User List" component when its checked
2) User List:
   1) Row of Column Names: A horizontal list that displays the name of the rows. Example names: User ID, Name, Surname etc. Every box in this row also has 2 buttons: Filter button and Sort Button.
   2) Filter Button: Filter buttons shows a prompt according to the cell that they are on. So; if it's on a numerical value for example, it will let the user to provide a range of numbers.
   3) Sort Button: Same as filter button each cell will have its own sort button. At the initial state, this button will be an up-down button and will not list the users with no order.
     By clicking it one time, it will become an up button and the list will sort in ascending order.
     Then clicking again will make it down button and the users will be sorted in descending order. Clicking for the third time resets the button.
   4) List: Based on the "Hide Disabled Users Chackbox", "Filter" and "Sort"; lists all the users. If there are no users in the system or there are no eligible users with given filters displays: "There are no users to show."
3) Register User Subscreen
   1) Save Button: This button saves the user to the system. It is inactive until all the information about the user is given.
   2) Username Textbox: It lets us to enter the username.
   3) Display Name Textbox: It lets us to enter the user's display name.
   4) Phone Textbox: A textbox to enter users phone number.
   5) Email Textbox: Checks if the email format is correct.
   6) User Roles Dropbox: A dropbox to give user role to the new user. The options are "Guest", "Admin" and "SuperAdmin".
   7) Enabled Checkbox: A checkbox to indicate if the user is active. Check if he/she is active, uncheck if not
