# Humanly Random
### An SMS-powered random number generator


This is my submission to the Trinity Junior Fresher Computer Science Competition.
My submission is an android app, so you will need to install it on an android phone to test it.

### How to Install Humanly Random:
- Enable developer mode on your android phone
  If you're not sure how to do this, see: https://developer.android.com/studio/debug/dev-options
- navigate to https://bit.ly/HumanlyRandom and download the .apk file
- Open the downloaded package file with Android's Package Installer
- You should get a screen asking if you'd like to install the app, press install
- You might get asked if you would like to scan the app with google play
  press accept if you'd like (I have nothing to hide)
- The app should now be installed

### Using Humanly Random:
- When you open the app for the first time you will get a pop-up asking for the permission
  to send and receive SMS messages, press allow (the app cannot read your messages, it simply
  requires the permission to send messages. The app will not work this permission isn't granted)
- Click the big white button to generate a random number
- To stop you from spamming my inbox, you cannot generate more than one random number per minute.

### How Humanly Random Works:
Humanly random uses Android's telephony library to send an SMS to the developer (i.e. me),
asking for a random number. You should then, after some time, receive a text message containing
your random number. The time taken to generate a random number will vary wildly due to a huge 
variety of factors. It can take anywhere between a few seconds up to, in the worst cases, a few days.


The app was developed using Processing, a Java-based IDE, along with the android telephony library for Java
If you have Processing installed on a computer, you can take a look at the source code by opening HumanlyRandom.pde
(You may need to install Android Mode if you want to play with the code)
Otherwise, you can check out the soruce code on my github page: 
https://github.com/Fechulo/HumanlyRandom/blob/master/HumanlyRandom/HumanlyRandom.pde
