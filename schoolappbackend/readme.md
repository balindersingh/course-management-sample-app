# Pre-requisites
Install Mongo DB from shared resource in Reference
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
# How to run schoolbackendapp - i.e. hosting API endpoints using NodeJS
```
cd schoolappbackend && node app.js
```

# Reference
https://docs.mongodb.com/manual/tutorial/install-mongodb-on-windows/#run-mongodb-from-cmd