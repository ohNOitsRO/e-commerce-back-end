# E-commerce Back End (Module 13 Challenge)

## Description

A mock E-commerce website with a preset database to connect the front and back end using mySQL and Sequelize to mimic a live envinronment.  Using Insomnia to test API endpoint routes.

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Credits](#credits)
- [License](#license)

## Installation

Install the node packages with "npm i" within the application directory.  
Install the mySQL package in order to connect to the database with "npm i mysql2".  
Install the sequelize package to connect express to the mySQL database with "npm i sequelize".  
Install the dot.env package in order to hide important credentials needed to login to the mySQL database with "npm i dotenv".  
Install the Insomnia API platform to check your API route requests from: https://insomnia.rest/

Open up your mySQL Terminal and run "mysql -u root -p" to have the database start listening.  
Then run "source db/schema.sql" to create the database, followed by "use ecommerce_db" to set the database.  

After in your Gitbash Terminal then run "npm run seed" to seed data into the newly created database tables.
Finally run "node server.js" to launch the sequelize connection and be able check your API routes in Insomnia.


Run the application with "node server.js" in the terminal command line and follow the prompts!  

## Usage

### Link to multiple video demos of application.

HOW TO START:  
https://www.youtube.com/watch?v=DqUBsx_3YWA

GET (Single) Routes:  
https://www.youtube.com/watch?v=uomKJkvLjU0

GET (All) Routes:  
https://www.youtube.com/watch?v=RQl5nfRnA38

Categories (POST/PUT/DELETE) Routes:  
https://www.youtube.com/watch?v=mvSOatv05Vw

Tags (POST/PUT/DELETE) Routes:  
https://www.youtube.com/watch?v=aYbXnoXng9A

Products (POST/PUT/DELETE) Routes:  
https://www.youtube.com/watch?v=XDPz1zc55gI


## Credits

MySQL for its Database management  
https://www.mysql.com/

Node.js for its CLI capabilities  
https://nodejs.org/en/

Sequelize for its ORM capablities to connect the front and back end.  
https://sequelize.org/

## License

Please refer to the LICENSE in the repo.

---