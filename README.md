# E-Commerce-Back-End
E-Commerce-Back-End

For this assignment, We were tasked with adding backend database functionality to an unfinished program using sequelize. Essentially we had to create

### Prerequisites

In order to test out the E-Commerce-Back-End, you'll need to have Node installed, you'll need to run the "npm i" command to install the necessary dependancies, and you'll need to change the information stored in the .env file to reflect your own username.password, and database. You'll also probably need to have a 3rd party program such as Insomnia in order to test out all the different routes.

## Getting Started

Once you've completed all the necessary prerequisites, you can start storing and accessing your own data sets. And in order to show you how to use it, I've included an instructional video that takes you through the steps of generating your own custom employee database. The video will be linked below, along with a step by step explanation. 


Tutorial Video: https://drive.google.com/file/d/1UItqtiTJ9GUr0wsHSCStT2ZQ_nGk_3I6/view?usp=sharing

If you need a little additional instruction, don't worry. Here's how it works:
The first thing you'll wanna do after opening up your terminal is make sure you've sourced the correct database. In order to do this, you'll need to run the command "mysql -u root -p" you will then be prompted to login to your mySQL account.
![Screenshot](https://i.imgur.com/UxRpB3r.png)

Login, and run the "source schema.sql" command. 
![Screenshot](https://i.imgur.com/WXY2qLS.png)

Optionally, you can also run the "npm run seed" command in order to start off with some placeholder data.
![Screenshot](https://i.imgur.com/ruNhjJa.png)

Now you're ready to start manipulating some data. From here, you can run the command "node server.js"
![Screenshot](https://i.imgur.com/1QRHQsS.png)
this will initialize the program, and allow you to start making requests using your 3rd party application.

All that's left to do from here is test out the routes. You can make a get request to recieve all the existing data from the categories/products/tags tables. Or add an additional id parameter to see specific categories/products/tags.  
![Screenshot](https://i.imgur.com/EyHtfSB.png)
![Screenshot](https://i.imgur.com/32dm8hc.png)

You can make a post request to add to one of the tables.
![Screenshot](https://i.imgur.com/7KwIuwa.png)

You can make a put request to modify some of the data in one of the existing tables
![Screenshot](https://i.imgur.com/9OXjru6.png)

Or you can make a delete request to remove the data from one of the existing tables.
![Screenshot](https://i.imgur.com/Q7BMenR.png)

## Built With
* [mySQL](https://www.mysql.com/)
* [Javascript](https://developer.mozilla.org/en-US/docs/Web/JavaScript)


## Authors

**Josh Gumperz** 

- [Link to Github](https://github.com/JoshGumperz)
- [Link to LinkedIn](https://www.linkedin.com/in/josh-gumperz-8706a8185/)

## License

This project is licensed under the MIT License 
