#### Tech Blog App

#### Descritiption
A CMS-style blog site for developers to publish articles, blog posts, thoughts, and opinions for others to read and comment on. 

#### Built With 🧰
- [x] Express.js
- [x] MySQL
- [x] Sequelize
- [x] Handlebarjs

#### Project Visuals :sunglasses:
<img width="1156" alt="Screenshot" src="images/Screen Shot 2021-11-13 at 3.09.42 PM.png">

## Link
[Click here](https://tech-blog-full-stack.herokuapp.com/) to go to the deployed application.

### How to use
To get started:

` Download the code or clone the repo`                    
` npm i to install necessary packages `       
` npm run seed to populate database `       
` npm start` 

#### User Story 📖
> AS A developer who writes about tech      
> I WANT a CMS-style blog site      
> SO THAT I can publish articles, blog posts, and my thoughts and opinions        

#### Acceptance Criteria ✅
> GIVEN a CMS-style blog site
? WHEN I visit the site for the first time
> THEN I am presented with the homepage, which includes existing blog posts if any have been posted; navigation links for the homepage and the dashboard; and the option to log in
> WHEN I click on the homepage option
THEN I am taken to the homepage
> WHEN I click on any other links in the navigation
> THEN I am prompted to either sign up or sign in
> WHEN I choose to sign up
> THEN I am prompted to create a username and password
> WHEN I click on the sign-up button
> THEN my user credentials are saved and I am logged into the site
> WHEN I revisit the site at a later time and choose to sign in
> THEN I am prompted to enter my username and password
> WHEN I am signed in to the site
> THEN I see navigation links for the homepage, the dashboard, and the option to log out
> WHEN I click on the homepage option in the navigation
> THEN I am taken to the homepage and presented with existing blog posts that include the post title and the date created
> WHEN I click on an existing blog post
> THEN I am presented with the post title, contents, post creator’s username, and date created for that post and have the option to leave a comment
> WHEN I enter a comment and click on the submit button while signed in
> THEN the comment is saved and the post is updated to display the comment, the comment creator’s username, and the date created
> WHEN I click on the dashboard option in the navigation
> THEN I am taken to the dashboard and presented with any blog posts I have already created and the option to add a new blog post
> WHEN I click on the button to add a new blog post
> THEN I am prompted to enter both a title and contents for my blog post
> WHEN I click on the button to create a new blog post
> THEN the title and contents of my post are saved and I am taken back to an updated dashboard with my new blog post
> WHEN I click on one of my existing posts in the dashboard
> THEN I am able to delete or update my post and taken back to an updated dashboard
> WHEN I click on the logout option in the navigation
> THEN I am signed out of the site
> WHEN I am idle on the site for more than a set time
> THEN I am able to view comments but I am prompted to log in again before I can add, update, or delete comments    

## Usage
1. Go to the deployed app at [https://the-tech-blog-24601.herokuapp.com/](https://the-tech-blog-24601.herokuapp.com/).
2. Click on posts to view comments.
3. Click on "Login" to login or signup.
4. Click on "Dashboard" to view your post dashboard.
5. From your dashboard, click on a post to update it or delete it.
6. From the homepage while logged in, click on a post to view and add comments.
7. Click on "Logout" to logout.

## Passwords
This application hashes passwords to maintain security through bcrypt.

## Templating
This application uses [express-handlebars](https://www.npmjs.com/package/express-handlebars) for templating.

## License
Licensed under the [MIT](https://choosealicense.com/licenses/mit/) license.

#### Acknowledgement, Documentation & Resources 🤝
- [Sequelize Documentation](https://sequelize.org/v5/)
- [Workbench documentation](https://dev.mysql.com/doc/workbench/en/)
- [MySQL2 Documentation](https://www.npmjs.com/package/mysql2)
- [SQL Troubleshooting Resources on Stack Overflow](https://stackoverflow.com/questions/26554818/using-mysql-in-the-command-line-in-osx-command-not-found)
- [SQL Deferrable Constraints Resoruces](https://begriffs.com/posts/2017-08-27-deferrable-sql-constraints.html)
- [All you need to know about Async Await In JavaScript](https://medium.com/technofunnel/javascript-async-await-c83b15950a71)
- [JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E)
- [NodeJS](https://img.shields.io/badge/node.js-6DA55F?style=for-the-badge&logo=node.js&logoColor=white)
- [ExpressJS](https://img.shields.io/badge/Express.js-404D59?style=for-the-badge)
- [MySQL](https://img.shields.io/badge/mysql-%2300f.svg?style=for-the-badge&logo=mysql&logoColor=white)
- [Sequelize](https://img.shields.io/badge/Sequelize-52B0E7?style=for-the-badge&logo=Sequelize&logoColor=white)