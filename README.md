Echo Messenger Bot
====================
This project is merely an echo bot to serve as base code to be built upon. Based on node.js, the project uses the messenger-bot node client to send and receive messages. Handy for getting something set up quickly for hackathons.

### Prerequisites
Set up Facebook page account

### To run locally:
1. Fill ./config/default.json contents with information from your Facebook page account
2. Launch node server: node app.js
3. Launch ngrok with port 5000: ./ngrok http 5000
4. Update Facebook with ngrok's https url
5. Talk to bot

### Pushing to production:
Works with Heroku