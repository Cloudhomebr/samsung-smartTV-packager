<h1>samsung smart tv packager (2013)</h1>
by james b. pollack<br>
www.adifferentengine.com<br>

this script will let you package a folder containing a html5 app without touching the samsung SDK.  

TO USE -- 

first:  

<code>npm install </code>

then:

<code>node samsungpackager.js folderToArchive APPID APPTITLE SERVERIP logFolderToDelete<code>

*the logFolderToDelete parameter is optional

---> i.e: <code>node samsungpackager.js ../src GTV GTV 192.168.0.25 ../src/logs</code>

*all paths relative to samsungpackager.js

the app will be served at localhost:80, just boot up your TV, point it at the correct IP address and sync your app.
