# Oswald
A slack bot for Stevens Ultimate

## Installation
1. `$ npm install`
2. Get Slack API token and add it to the credentials folder in a file called
slackToken.json formatted as {"token":"[token]"}
3. Get Google calendar client secret and add it to the credentials folder as a
file called client_secret.json
4. `$ npm start`

##Notes
For google calendar client secret, follow these steps: https://developers.google.com/calendar/quickstart/nodejs
For slack api, create the app and then navigate to OAuth and permissions. Then use Bot User OAuth access token
Then it should work.
For AWS setup with nodejs, follow this: https://docs.aws.amazon.com/sdk-for-javascript/v2/developer-guide/setting-up-node-on-ec2-instance.html

