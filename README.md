this is a slack bot i made by following the tutorial on the stardance challenge. it doesn't do anything useful. it can tell you a bad joke and tell you a fact about cats. i'm allergic to cats so it might be lying to me and i would be none the wiser.

if you want to try it go on the hackclub slack https://app.slack.com/client/E09V59WQY1E/C01D7AHKMPF
and do /epic-help on the hackclub slack to see my bot in action (that's what the programmers say right)

Available Commands:

/epic-ping - Check bot latency

/epic-catfact - Get a cat fact

/epic-joke - Get a random joke

/epic-help - Get help


if you want to use it for yourself for some reason...

create a .env file in the project folder and add the following  lines:

SLACK_BOT_TOKEN=xoxb-...   # Bot User OAuth Token (from OAuth & Permissions)

SLACK_APP_TOKEN=xapp-...   # App-Level Token (from Basic Information → App-Level Tokens)

and then run the following commands

npm init -y

npm install @slack/bolt dotenv

npm install axios

node index.js
