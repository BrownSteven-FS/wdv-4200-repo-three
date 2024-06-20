# WDV-4200 Node Secret Assignment
## Repo 3

### Purpose
The purpose of this repo is to demonstrate properly controlling secret environment variables. 

### Getting started
This repo prevents the uploading of the environment variables by adding the ```.env``` file to the .gitignore file. 

To run the application, please update the ```.env.example``` file with the correct values and remove the ```.example``` from the file name.

From there, run
```shell
npm i
node app.js
```

### Secret Environment Variables
The ```.env.example``` looks like this by default:
```shell
SECRET_QUESTION=
SECRET_ANSWER=
```

You will need a value for both ```SECRET_QUESTION``` and ```SECRET_ANSWER``` for this application to run properly.

### Contact
Steven Brown
smbrown1@student.fullsail.edu