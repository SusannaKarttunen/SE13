A.Use cases scenario and flow chart

1. Use cases

User:
  -Login
  -Log out
  -Edit account
  -Delete account
  -Add friends
  -Add foes
  -Search for people
  -Show people in list
  -Show people in map
  -Delete friends
  -Delete foes
  -Plan route
  -Edit options

First timer:
  -Sign up

2. Use case scenario

"User wants to login"

Initial state: 
  User is not logged in and is a registered user

Normal flow:
  User opens the application.
  User sees the page with the username and password form and the "Login" button.
  Then he/she enters the username and password and clicks "Login".
  The user is redirected to the start screen of the application and is now logged in.

What can go wrong: 
  The user mistypes the username or password.

Other activities going on at the same time: 
  Database checks the match with the username and password.

End state:
  The user is logged in.

3. https://github.com/rosasuominen/SE13/blob/master/UseCase_SE13.png

B. User interface

1. Main views of the system

  -Login page
  -Sign up page
  -Main page
  -Map screen
  -People list page
  -Search page
  -Settings page
  -Edit account page
  -Plan route page
  
2. Description of the views.

Login page:
  Only contains the Login form and the link/button for the Sign up page
  
Sign up page:
  Contains a form with the following fields: username, password, email, first name, last name, 
  birth date (optional), study group (optional), teacher or student (optional). Also contains the sign 
  up button and a button for going back to the previous screen.
  
Main page:
  Has links for map, people list, search, settings, plan route and log out.
  
Map screen:
  Has a map view of the campus, buttons to move the view to a different floor, 
  the map can be zoomed, people can be clicked, a button to return to the main page, 
  a button to go to the people list and a button to go to the plan route page. 
  Also shows a route if planned with the plan route page.

People list:
  Has filter buttons for showing friends, foes and all people currently logged in, 
  people can be marked either friend, foe or neutral. Has a button to return to the main page and a
  button to go to the search page.
  
Search page:
  Has a search bar, shows a list of people found. searched people can be marked either friend, foe or neutral.
  Has a button to go to the people list  and a button to return to the main page.
  
Settings page:
  Has buttons for edit account and delete account. User can delete the account by pressing the button. 
  Has a button to return to the main page.
  
Edit account page:
  User can edit password, email, study group and teacher/student status. Has a button to save changes, 
  to go to settings page and to return to the main page.

Plan route page:
  Has a form with "Starting point", "End destination", a button for marking current location as the starting point, 
  a button for choosing the start or end point from the map screen, a "Plan route" button, 
  a button to return to the main page.
  
3. https://github.com/rosasuominen/SE13/blob/master/interface_SE13.png

4. State transitions between the views.

Login page:
  Leads to the main page and Sign up page.
  
Sign up page:
  Leads to the main page and the login page.
  
Main page:
  Has links for map, people list, search, settings, plan route and log out. Log out leads to the login page.
  
Map screen:
  Leads to the people list, plan route page and main page.

People list:
  Leads to the search page and the main page.

Search page:
  Leads to the people list and the main page.

Settings page:
  Leads to the edit account page, main page or the login page.

Edit account page:
  Leads to the main page and the settings page.
  
Plan route page:
  Leads to the map page and the main page.
  
  https://github.com/rosasuominen/SE13/blob/master/sorsatransitions.png
