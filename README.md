# XKCD-email
A script that will email either the newest XKCD comic or a random one

## Usage ##
The script takes the emails of the recipients as arguments ex.
```
sh emailXKCD.sh example@domain.com
```
There can be any number of emails.

### Dependencies ###
```wget```<br>
```shuf``` which is in the default ubuntu installation <br>
```s-nail```<br>
```recode```
## ##
I used Ssmtp on Ubuntu and had it send the message from a gmail account which can be set up like [this][ubuntu-email]




[ubuntu-email]: https://help.ubuntu.com/community/EmailAlerts
