# ElephantLabs uptime check

Every 10 minutes GitHub checks the addresses in `sites.txt`.
If one is down (after 3 tries), an issue titled **DOWN: …** opens and GitHub
emails everyone watching this repo. It closes itself when the site is back.

Add a site: one line in `sites.txt` — `Name|https://address/|text the page must contain`.
Test the alert: Actions → Uptime check → Run workflow → tick "Send a test alert".
