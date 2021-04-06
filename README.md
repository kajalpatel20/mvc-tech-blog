# Model-View-Controller (MVC): Tech Blog

## User Story

AS A developer who writes about tech
I WANT a CMS-style blog site
SO THAT I can publish articles, blog posts, and my thoughts and opinions


 ## Description: 

Writing about tech can be just as important as making it. Developers spend plenty of time creating new applications and debugging existing codebases, but most developers also spend at least some of their time reading and writing about technical concepts, recent advancements, and new technologies. A simple Google search for any concept covered in this course returns thousands of think pieces and tutorials from developers of all skill levels!

So, I have created this application which builds a CMS-style blog site similar to a Wordpress site, where developers can publish their blog posts and comment on other developers’ posts as well. I build this site completely from scratch and deploy it to Heroku. My app will follow the MVC paradigm in its architectural structure, using Handlebars.js as the templating language, Sequelize as the ORM, and the express-session npm package for authentication.

## Table of Contents:

* [Mock-Up](Mock-Up)
* [Usage](#usage)
* [Installation](#installation)
* [Deployment](deployment)
* [License](#license)
* [Questions](questions)

## Mock-Up

The following animation demonstrates the application functionality:

![Animation cycles through signing into the app, clicking on buttons, and updating blog posts.](./Assets/14-mvc-homework-demo-01.gif) 


## Usage:

GIVEN a CMS-style blog site

WHEN I visit the site for the first time

THEN I am presented with the homepage, which includes existing blog posts if any have been posted; navigation links for the homepage and the dashboard; and the option to log in

WHEN I click on the homepage option

THEN I am taken to the homepage

WHEN I click on any other links in the navigation

THEN I am prompted to either sign up or sign in

WHEN I choose to sign up

THEN I am prompted to create a username and password

WHEN I click on the sign-up button

THEN my user credentials are saved and I am logged into the site

WHEN I revisit the site at a later time and choose to sign in

THEN I am prompted to enter my username and password

WHEN I am signed in to the site

THEN I see navigation links for the homepage, the dashboard, and the option to log out

WHEN I click on the homepage option in the navigation

THEN I am taken to the homepage and presented with existing blog posts that include the post title and the date created

WHEN I click on an existing blog post

THEN I am presented with the post title, contents, post creator’s username, and date created for that post and have the option to leave a comment


## Installation:

My application’s folder structure must follow the Model-View-Controller paradigm. I need to use the [express-handlebars](https://www.npmjs.com/package/express-handlebars) package to implement Handlebars.js ,[MySQL2](https://www.npmjs.com/package/mysql2) and [Sequelize](https://www.npmjs.com/package/sequelize) packages to connect to a MySQL database for my Models, and create an Express.js API for Controllers.

I also need the [dotenv package](https://www.npmjs.com/package/dotenv) to use environment variables, the [bcrypt package](https://www.npmjs.com/package/bcrypt) to hash passwords, and the [express-session](https://www.npmjs.com/package/express-session) and [connect-session-sequelize](https://www.npmjs.com/package/connect-session-sequelize) packages to add authentication.

 ### Deployment: 


* The URL of the functional, deployed application.

https://kaj-mvc-tech-blog.herokuapp.com/

* The URL of the GitHub repository, with a unique name and a readme describing the project: 

https://github.com/kajalpatel20/mvc-tech-blog


## License:
 APACHE 2.0

  [![Github License](https://img.shields.io/badge/license-APACHE 2.0-blue.svg)]
## Questions:

The repo for this project can be found here

https://github.com/kajalpatel20/mvc-tech-blog

For any questions or to report issues, email me at: kajalpatel20@gmail.com
