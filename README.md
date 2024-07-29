# swe-550-threat-model
Basic repo for threat model assessment

This represents a basic web application with the following features:
- Presents the user with a login page upon arrival to the web page.
- Uses an open-source component to authenticate user credentials against those stored on the database.
- If the username/password combo exists in the database, the user will be presented with a message of the day also stored on the database, otherwise they will be notified that their login was unsuccessful
- Once logged in, the user will be able to comment on the message of the day and those comments will get stored in the database.

DATABASE STRUCTURE:
The database will consist of three tables:
- users
- message_of_the_day
- mod_comments
