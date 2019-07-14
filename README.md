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


# How to run the Tests

## Technologies

* Selenium
* Selenide
* Java


## Prerequisites

### Java

Install Java 8.

### Google Chrome

 Make sure that you have the  version 75.x of Chrome before you run the tests later in this guide.


## Run the Tests

To run them test, change the current working directory:

```bash
cd TrelloChallenge
```

And now you can run the demo tests using the command below:

```bash
mvnw clean test
```

The [Maven Wrapper] will take it from here, During the execution of tests, Chrome will automatically open and close several times.
