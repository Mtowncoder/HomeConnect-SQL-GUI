# HomeConnect-SQL-GUI
Integrated SQL and a GUI into home connect API code

In order to run this code you must make a home connect developer account

This code is for Fridge-Freezers

If you want to use for outside of Fridge-Freezers, the only thing you should have to change should be the URL's in the code and maybe the headers for the GET and PUT requests

When authorizing for Simulator select IdentifyAppliance, Fridge-Freezer settings, Fridge-Freezer control

Click first command, Look in the Curl -Get Headers for the auth_key(should start with Bearer). Also look for HAID

Insert auth_key into code and keep HAID for when program asks for it's input

I am currently trying to find a way to automatically refresh the auth_key, I am still writing code for the EXIT and GET settings button on the GUI

I am also trying to think of another command for the "This is a button Widget" placeholder
