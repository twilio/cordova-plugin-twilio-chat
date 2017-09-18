cordova-plugin-twilio-chat 
================
[![NPM](https://img.shields.io/npm/v/cordova-plugin-twilio-chat.svg)](https://www.npmjs.com/package/cordova-plugin-twilio-chat) [![Build Status](https://travis-ci.org/twilio/cordova-plugin-twilio-chat.svg?branch=master)](https://travis-ci.org/twilio/cordova-plugin-twilio-chat)

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
