# NGO-Project
## introduction
This functional requirement is part of a global web portal for a customer. Customer is a non-profit organization and branches all over the world. For fund raising, they organize various activities and events on multiple cities and sell the tickets and other artifacts like t-shirts, cap, etc. 

### functional specification

Application will have two user roles:
1. Admin users, who are responsible for user creation, event management such as event creation, event editing and make an event inactive.
2. Regular users, who can view the events and register for those events. They do not have any capabilities of admin functionalities.

### Admin Module:
Admin user(s) are responsible for:
- Creation of n-numbers of regular users. There will be a default Admin user who will be added directly in the database.
- Manage events.

Upon login, if the user is an admin user, he/she will see a screen like this:

From above screen, Admin user can manage existing users or create n-number of users. When “Add User” or “Edit” link is clicked, a popup screen will appear with these entry fields:
o First Name
o Last Name
o Email
o Password
o Role(Dropdown with two values : Admin & User)
o Save Button
o Cancel Button
Once the Save button is clicked, popup window will close and changes will be reflected on the grid (table).
