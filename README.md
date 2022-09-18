# Express Node JS Api Sample Using Mysql

### Install
$ git clone https://github.com/idmaintzain/nodejs-express-mysql.git
$ cd into project_folder ie cd nodejs-express-mysql
$ npm install


### Configure app

#### Step 1 working with localhost

        1. install mysql You can use workbench or any phpmyadmin from XAMPP or WAMP Server
        4. CREATE DATABASE crud;
        5. CREATE TABLE users(
                _id INT NOT NULL AUTO_INCREMENT,
                firstName VARCHAR(45) NOT NULL,
                lastName VARCHAR(45) NOT NULL,
                email VARCHAR(45) NOT NULL,
                createdAt DATETIME NULL,
                updatedAt DATETIME NULL,
                PRIMARY KEY (_id),
                UNIQUE INDEX _id_UNIQUE (_id ASC),
                UNIQUE INDEX email_UNIQUE (email ASC)
        );


### Start app using Nodemon

    $ npm run dev

### Running APP
After starting your app, run with this http://127.0.0.1:3000/api/user/ and check router page for other access page
