# Contact List App

This web-based application helps you remember and saves your contacts list in the database. You can add modify or delete the contact as per your requirement.

---
## Requirements

For development, the tech-stack used are HTML5, CSS, javaScript, MongoDB and Node.js. 

## Screenshots
![Contact List Home](https://i.ibb.co/1X0mXPL/contact-List.jpg)

### Node
- #### Node installation on Windows

  Just go on [official Node.js website](https://nodejs.org/) and download the installer.
Also, be sure to have `git` available in your PATH, `npm` might need it (You can find git [here](https://git-scm.com/)).

- #### Node installation on Ubuntu

  You can install nodejs and npm easily with apt install, just run the following commands.

      $ sudo apt install nodejs
      $ sudo apt install npm

- #### Other Operating Systems
  You can find more information about the installation on the [official Node.js website](https://nodejs.org/) and the [official NPM website](https://npmjs.org/).

If the installation was successful, you should be able to run the following command.

    $ node --version
    v8.11.3

    $ npm --version
    6.1.0

If you need to update `npm`, you can make it using `npm`! Cool right? After running the following command, just open again the command line and be happy.

    $ npm install npm -g

###
---

## Download & Install

    $ git clone https://github.com/bhavyatyagi/contactListApp.git
    $ cd toDoList
    

## Dependencies
  After installing node, this project will need some dependecies too, so just run the following command.

      $ npm install 

## Configure app

- Make sure your MongoDB database server is running

## Running the project

    $ npm start
 
 - This should make your app available on port 8080.

## Simple build for production

    $ npm build 
    
   -  This would require MongoAtlas.
