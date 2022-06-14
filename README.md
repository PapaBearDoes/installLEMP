# PapaBearsLEMP
Install an SSL LEMP stack on Debian/APT based systems.

This requires you to already have a domain that is resolving to your intended webserver correctly (ie, the ports 80 and 443 are open already, the domain name resolves to your external IP, and your router sends that traffic to your intended server correctly).

Once that's setup, all you have to do is `sudo nano ./installLEMP` and then change the email and domain to your information, then run the installer:

`./installLEMP`