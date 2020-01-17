# Pre-requisites
Install Mongo DB from shared resource in Reference
# Components
* It has 2 applications.
* `schoolapp`: which is basically the front end of the application using Angular. You can find more detail about the project in its Readme.md file in its folder
* `schoolappbackend`: as it is clear from its name it is backend which is basically serve couple of api endpoints written in NodeJs (with express) using MongoDb as Database
# How to run mongodb server
Basically you just need to run following command
```
mongod
```
If it throws error like `command not found` then you just need to make sure Mongo Db is installed and its executable is on PATH variable
Alternatively you can just run it from its installation folder by running following command in terminal (for windows)
```
"C:\Program Files\MongoDB\Server\4.2\bin\mongod.exe"
```
# How to run schoolbackendapp
```
cd schoolappbackend && node app.js
```
# How to run angular front end app
```
cd schoolapp && ng serve
```
# Reference
Full credit to this tutorial : https://www.positronx.io/angular-8-mean-stack-tutorial-build-crud-angular-material/