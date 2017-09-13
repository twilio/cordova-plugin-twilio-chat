# cordova-plugin-twilio-chat 

> This plugin offers support of [Twilio Programmable Chat](https://www.twilio.com/chat) for [Apache Cordova](https://cordova.apache.org/)

# Usage
After this plugin installation [Twilio Programmable Chat](https://www.twilio.com/chat) is available in your Cordova project using `TwilioChat` accessor.
API and interfaces are identical to [Twilio Chat JavaScript library](https://www.twilio.com/docs/api/chat/changelogs/javascript).  

Example of usage:
```
    TwilioChat.Client.create(token).then(client => {
        // Use client
    });
```
