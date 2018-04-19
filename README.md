# Fitness Website

## This project is a Fitness Website having some great features to keep a tab on your fitness.

## Deploy to heroku
 
  <a href="https://heroku.com/deploy?template=https://github.com/Suesanz/Fitness-Website">
  <img src="https://www.herokucdn.com/deploy/button.svg" alt="Deploy">
</a>

## For development purpose

### Prerequisites:

1.Any javascript IDE supporting node js(recommended: Webstorm by Jetbrains).

2.The database created is by using Sequilizer in nodejs. Here mysql is used as dialect. If someone works on other database
 platform they can change dialect in model.js file.
 
 3.The datbase created  must have same name,username as written in model.js file. If someone intended to change it please do change the configuration from sequilizer command also.
 
 ### HOW TO SET UP?

**Step 1:** Run command 
      * npm install *
      
**Step 2:** To make sign in working register your app from facebook and twitter from their developer page.The client id and client secret used here in strategies are just some random number(obviously).

**Step 3:** Run command
      * node server.js *
       and open the respective port mentioned in your browser.
      
 