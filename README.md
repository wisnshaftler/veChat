# veChat
This is simple nodejs socketIO and apache cordova chat app run on windows, android, and ios. To create this app i use nodeJS, Apache cordova, Socket,IO and JQMobile. Get this join to improve this app. Thank you.

----------------------------------------------------------------------------------------------------------
                                         Installing and create android app.
-----------------------------------------------------------------------------------------------------------

1- First you need download Android SDK and jdk1.8 Apache cordova and nodeJS with nodemon and socketIO.(If you have Android Studio and it      works correct you dont need Android SDK and jdk)
    (download Android SDK and jdk1.8 https://drive.google.com/drive/folders/1jAqr5yN0dtwItNjSSsCR4Xt4GyVcikJ-?usp=sharing and install)
    [set jdk and android SDK path in your computer]

2- Extract and navigate to node_server folder.

3- Edit what you like or edit veChat\www\js file 4th line localhost to your pc ip address

3- open cmd and locate to node_server folder and enter this command:- nodemon app.js

4- open vChat\www folder and press shift+mouse right click then choose Open command window here.

5- enter this commands :-
   cordova platform add browser    //for browser application
   cordova platform add android    //for android application
   cordova build android
   cordova emulate android         //emulate android app
   
   [You must have installed android SDK API 27 or higher for this]
 
6- Done! You can find android apk file in veChat\platforms\android\app\build\outputs\apk\debug or if you build for browser you can see        webbrowser mode in your default browser.
