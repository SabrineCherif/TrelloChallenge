# TrelloChallenge

# Test Case 1
Summary: Check Login functionality

Steps:
 1- Go to Trello home page 
 2- Click on Login 
 3- Fill the username and the password 
 4- Click on "Log In" 

Expected Results:
- User is redirected to boards page

# Test Case 2
Summary: Check team creation functionality

Steps:
 1- Go to Trello home page 
 2- Click on Login 
 3- Fill the username and the password 
 4- Click on Log In 
 5- Click on "Create a team" button 
 6- Fill the name and description
 7- Click on "Create" 

Expected Results:
- User is redirected to created team page 
- Team name and description are correctly displayed


PS:
- I would like to improve the check of the team creation: the displayed team name and description.
- Change the wait from Thread.sleep to explicit wait (implicit wait didn't work).
