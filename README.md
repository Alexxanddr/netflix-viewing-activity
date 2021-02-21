# netflix-viewing-activity

**Scrape viewing activity from Netflix**

For retrieve the json of the history viewing activity:

- install the dependecy with: `pip3 install -r requirements.txt`

- Retrieve netflix user id (necessary in multiaccount), this field is located in the html page with **data-profile-guid** property

- Add in the environment variable: **NETFLIX-EMAIL**, **NETFLIX-PASSWORD** and **NETFLIX-USER_ID**

- execute python3 netflix.py
