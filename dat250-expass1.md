#Expass 1

###The installation 
Even tho I didn't have any of the required software installed, except Git, I did not encounter any major problems. The only problem I had was the installation of Maven, because I was a bit unsure about which version to get. I solved this by googling, where I found a tutorial to follow.

###Validating the software
After the installations I checked that the software was working by running the different versions commands. Like mvn -v for maven, heroku login for heroku and java -version for the jdk.

###Technical problems encountered with the Heroku platform
The issues I encountered with Heroku was that not every command worked in Git Bash, for instance with the login command. I get sent to the webpage to login, and it says in the terminal that I am logged in, but I have to use Ctrl C to end the command. Another command that I found out didn't work in Git was the heroku pg:psql, but this, as well as the heroku login command works in Windows command prompt, "Ledetekst".  
Another issue I had was that I could not do the "Provision add-ons" step. To provision the Papertrail add-on I had to verify my account by adding a credit card.
My final issue is that I can't start a one-off dyno at hvl, there is some problem there, but I can do this at UiB.

###Pending issues
I still have the same issues, with not all the commands working in Git, but I can execute this commands in Windows command prompt. And that I have not verified my account by adding a credit card, so I can't use the Papertrail add-on. 

###My Heroku link
https://damp-wildwood-66123.herokuapp.com/