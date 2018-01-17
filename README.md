# Overview
This is an admin portal Node.js app using [Express 4](http://expressjs.com/).

## Getting Started
These instructions will help you to setup your backend server and runnig on your local machine for development and testing purpose.

**Prerequisites**
* [Node.js](https://nodejs.org/en/)
* [MySQL](https://dev.mysql.com/downloads/mysql/)

**Installation**
* Install Node.js

1. To make sure you have Node and [NPM](https://www.npmjs.com/)(Which is installed on your computer when you install Node.js) installed, run two simple commands to see what version of each is installed:
```
node -v

npm -v
```

2. Install from website
   - You can download it directly from [NodeJS.org](https://nodejs.org/en/)

3. Install by Homebrew
[Homebrew](https://brew.sh/) is a package manager for the Mac — it makes installing most open source sofware (like Node) as simple as writing `brew install node`.
```
brew install node
```


* Install MySQL

1. Install from website

   - You can download MySQL Community Server drectly from [MySQL Website](https://dev.mysql.com/downloads/mysql/)

2. Login MySQL database by terminal:

   - You either need to use the full path (/usr/local/mysql/bin/mysql_executable_here)
```
/usr/local/mysql/bin/mysql -u username -p
Enter password:
```

   - Or add it to your $PATH:
```
# Add to $PATH
export PATH="$PATH:/usr/local/mysql/bin"

# Login
mysql -u username -p
Enter password:
```

3. Login MySQL database by IDE:

MySQL [WrokBench](https://dev.mysql.com/downloads/workbench/) is a visual database design tool that integrates SQL development, administration, database design, creation and maintenance into a single integrated development environment for the MySQL database system. 


## Start 

**Install dependencies**

```
# Go to your project folder
cd  ./AdminPortalBackend

npm install 
```
**Starting with node**
```
# Start node server
node server/server.js
```
**Starting with nodemon**

[Nodemon](https://nodemon.io/) is a utility that will monitor for any changes in your source and automatically restart your server.
```
# start node server
nodemon server/server.js
```
