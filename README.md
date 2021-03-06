# Library-Management-System
An online library management system built in mongodb, nodejs, express
## Techonologies used in this application

### Front-end

1. HTML5
2. CSS3
3. BOOTSTRAP 4
4. jQuery

### Back-end

1. MongoDB
2. Express.js
3. Node.js
4. Passport.js

## Install dependencies
Open git bash or command line tools at application file and run following npm command or if you know what to do, just look at `package.json` file :)

`npm install passport passport-local passport-local-mongoose body-parser connect-flash ejs express express-santizer express-session method-override mongoose multer sharp uuid --save`

#### Install dev dependencies if needed
`npm install nodemon faker --save-dev`

## Run the application
All data in this application stored in MongoDB. Make sure MongoDB installed in your machine or environment. Keep `mongod` running on background and run `node app.js` on app folder. That's it! 

## Functionalities

Whole app is divided into three modules.

* Admin
* User
* Browse books
* ``For Borrowed books the default return date is 7 days after borrowing``
### Admin module functionalities
* Sign up (This route is hidden. only accessible by typing the route manually and when admin log in)
* Login
* Logout
* Track all users activities
* Add books
* Update books
* Delete books
* Search books by category, title, author, ISBN
* Find users by firstname, lastname, email and username
* Delete user account
* Restrict individual user if violate any terms and conditions
* Browse books showcase
* Update admin profile and password
* Add new admin
* Delete currently logged in admin profile

### User module functionalities
* Sign up
* Login
* Logout
* Track own activities
* Borrow books
* Renew books
* Return borrowed books
* Browse books showcase 
* Add, edit and delete comment on any books comment section
* Update profile and password
* Delete account 

### Browse books module functionalities
This module can be accessed by anyone
* Show all books
* Find books on filtered search








