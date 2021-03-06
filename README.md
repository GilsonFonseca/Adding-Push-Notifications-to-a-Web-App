# Push Notifications codelab


  In this codelab, is taught how to add Push Notifications to web applications, [here](https://codelabs.developers.google.com/codelabs/push-notifications/index.html?index=..%2F..%2Findex#0). you can see how to do it.

  You'll also learn the basics of Service Workers.

## What this codelab teach us

* Service Worker basics: installation and event handling
* How to set up a Google Cloud Messaging (GCM) account
* How to add a web manifest
* Techniques for requesting GCM to send a notification to a web client
* Notification display
* Notification click handling

## What you'll need in order to make it work
  In order to run it properly you'll need to download the [Web Server for Chrome app](https://chrome.google.com/webstore/detail/web-server-for-chrome/ofhbbkphhbklhfoeikjpcbhemlocgigb), because this codelab was designed to work well with it, but you're free to use your own web server.</br>
  After that you need to configurate it by selecting the app folder of the project in the  "choose folder" button, you'll need to check the box next to "Automatically show index.html" too, and lastly stop and restart the server by sliding the toggle labeled "Web Server: STARTED", now the web server is setted for you to work on the codelab.</br>
  In order to you test this code after setting up the server, you'll need to go to [Push Companion](https://web-push-codelab.appspot.com/) copy the public key and change it in app/scripts/main.js now you have to allow notifications on your browser, then copy the Subscription, go to [Push Companion](https://web-push-codelab.appspot.com/) one more time and paste it under "Subscription to Send To". Then in "Text to Send" you text a message and click in "Send Push Message" button, you'll should see a notification appearing in the bottom right.
