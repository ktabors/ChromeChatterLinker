Chatter Linker
A Chrome extension for Salesforce.com's Chatter that makes sharing links easy and notifies the user of followers chatter.

Kyle Taborski

This was created for a demo and is therefore not a complete extension. It was developed prior to the release of chatter.

Changes v1.1 - These changes were done during a hackathon for a different extension and were encorperated into this extension with limited testing.
- Added an options page to input username, password, securityToken, and url. URL has a default value. All values are stored in plain text in the browser DB.
- Changed the Chatter count to set the time first used and the count is based off of all posts since that time. That time is updated when the user uses the extension to goto the chatter homepage.

Suggested Improvements
- Adding existing chatter about the page being shared in the popup below the form.
- On the options page allow the user to change the URL the popup form submits to.
- Finishing touches like on the popup page telling the user they need to set their username and password before it will work and warning the user on the options page that the password is stored in plain text in the browser DB.