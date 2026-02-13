Colors Lab
# Summary
This COLORS application will start at a login screen, where the SQL will determine who can access past the login screen via username & password pairs. 

# Technologies
Digital Ocean, GoDaddy, whatsmydns.net, Command Prompt, ARC, Developer tools.

# High-Level Setup Instructions
To run make the information accessible in an easy way, you can follow the steps I took: (1) Get a Droplet from DigitalOcean, (2) get a Domain from GoDaddy and change the NS's & A type record from the default ones to DigitalOcean's (NS listed in Networking -> Domains and A type to IP address), (3) make sure to change the domain name cop4331-5.com listed in code.js to your http://YOURDOMAINNAME/LAMPAPI (or if that doesn't work use IP address instead of Domain Name), (4) use Incognito mode or something of the sort to view http://YOURDOMAINNAME in HTTP (NOT HTTPS).  If you are having problems to have the website show, check whatsmydns.net to see if the domain name is connected to your IP address.  After the steps above, you should be able to see the Login page, which has a grey background.  To view the rest of the page, log in as a user based on your mySQL input; for example, if you add a username as SamH and have a password of Test, you should be able to view past the Login page after entering those credentials.  If your password still does not work, where you can not get past the Login AND no error shows, check Developer tools.

# How to Run and Access the Application
Type in the Domain name or IP address from your Droplet or Domain in an Incognito browser, make sure it is HTTP.  You should be able to see the Login page, which has a grey background.  To view the rest of the page, log in as a user based on your mySQL input of valid users; for example, if you add a username as SamH and have a password of Test, you should be able to view past the Login page after entering those credentials.  If your password works, you should be moved over to the colors page, where you can either add or search a color that that logged-in user has set up.  The information should save even if you log out of the session.

# Assumptions, Limitations, AI Usage (Class Policy)
You can look up how to create a table in the mySQL tied to your Droplet; you will likely have a different domain name, IP, and password to access the droplet - REMEMBER YOUR INFORMATION.  You cannot view the website in HTTPS unless you get additional features to allow for that.  The information has only been slightly modified to fit my IP, DNS, and password for "TheBeast", though those changes should not be present in this GitHub presentable.  If you were to modify using AI, as per class policy, make sure to claim how AI was used as it is not your own work and should give due credit.
