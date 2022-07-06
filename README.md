# coding-events-demo

Purpose of app: 

To create unique user accounts that the user can utilize to create and follow coding events around the area. 

Current state of app:

New coding events can be created and stored in a database, but it lacks functionality to create user accounts. 

Future improvements:

Add logic to create user accounts. 
Person class should include:
- ID
- First & Last name
- Email or username
- Password
(Getters and setters for each except ID)
- Profile info 
- List of events created and/or followed 

Person --> many-to-many relationship with events follwed
Person --> one-to-many relationship with events created 
