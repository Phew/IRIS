
# IRIS-OSINT - EZ OSINT
  An Email/User OSINT &amp; Password breach hunting tool, locally or using premium services, with support for many APIS.

## Infomation on project
  A simple way to do OSINT on a username, email, or domain.
  Get results on databreaches, sites the target has used, google dorks that can lead to more infomation and much more.

# How To Use
```bash
python3 -m pip install -r requirements.txt
python3 -m pip install holehe
python3 main.py
```

# Basic Search
```bash
< Start the program >
python3 main.py

< Run a WeLeakInfo search on test@gmail.com >
set target test@gmail.com
start 2
```

# RETARDS READ HERE
```bash
INSTALL FUCKING PYTHON
RUN THE INSTALLER
ADD TO PATH
RUN "python -m pip install -r requirements.txt"
NOW RUN IT HOLY FUCK
```


# Errors
| Error  | Fix |
| ------------- | ------------- |
| Cannot use sitescan module  | Install holehe module, the command is `pip3 install holehe`  |
| Weleakinfo module not working | Put an API key into the config.json file. |
| Breachdirectory is broken | Get a new API key from [here](https://rapidapi.com/rohan-patra/api/breachdirectory)


## Modules
| Module Name  | API Docs/Link | Infomation |
| ------------- | ------------- | ------------- |
| WeLeakInfo  | https://weleakinfo.to  | Used for databreach and leak analysis  |
| Twitter Data  | Self Made  | Used for grabbing phone numbers and emails off of a Twitter account |
| Site Scan  | Self Made  | Find sites a user is signed up for using reset password & signup endpoints  |
| Thatsthem | https://thatsthem.com/ | Get the name, address and phone number associated with an email address | 
| Keybase | Self Made | Grab an email linked to a keybase account just from a username |
| Breach Directory | https://breachdirectory.tk/ | Allows you to search through all public data breaches to make sure your emails, usernames, passwords, and domains haven't been compromised. |
| IP Leak | https://breachdirectory.com | Search where user ips have been used and get emails, usernames, and other infomation!
| Username To Email | https://breachdirectory.com | Enter a username and get a email, ip, and where that email has been leaked.


## Credits
  - HellSec, Checksum, Robert, Void, Tsuki, and Zalgo
