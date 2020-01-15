# ![GA Logo](https://ga-dash.s3.amazonaws.com/production/assets/logo-9f88ae6c9c3871690e33280fcf557f33.png) 

### GA's SEI Course Project #3: React Application

# Jeddah Guide 
<img align="center" src="Jeddah_Guide_Logo.PNG"></img>

## Description


## Installation
<a href="google.com"> Click here </a> to access the deployed version of the application. <br>
To install the react project, fork and clone this repository then use git bash terminal to run the command
``` npm install ``` followed by ``` npm start ``` to start the server after the installation process is finished.

## Technologies Used
* HTML -DOM
* CSS
* JSX
* JavaScript
* React
* React Strap
* React Bootstrap
* React Router Dom
* GitHub
* Open Weather API


## How the code works
### App.js
The main rendered component by ``` index.js```. It handles the display of the main navigation bar that allows the user to choose the type of place they wish to see a list of, whether it's a restaurant, cafe, hotel, a place or an activity. As well as taking care of the defining the routes to each one of the components responsible for displaying the corresponding list of places, which will be achieved when the user clicks on the link associated with that place.

### Components
The application has 7 components:
  * ``` Restaurant ```
  * ``` Cafes ```
  * ``` Hotels ```
  * ``` Places ```
  * ``` Activities ```
<br>Each one of the previous 5 components recieves a list that corresponds to the component name (sent by ``` App.js``` when routing to that component), for example: the ``` Restaurant ``` component will recieve a list of resturants, the ``` Cafes ``` component will recieve a list of cafes, and so on.
<br>The main purpose of each one of the components is to display the list it recieves and enable the user to click on a specific item to display more information about it.
* ``` Display ```
<br> Displays information of the place/item chosen by the user from any of the previous components where it'll be rendered.
* ``` Show Carousel ```
<br> Rendered by the ``` Display ``` component to show multiple images of the currently displayed place using ``` Bootstrap Carousel ``` as part of the inormation related to that place.


## Resources
<a href="https://github.com/sei-jed-10/W08D04-React-Router"> React-Router</a> <br>
<a href="https://reactstrap.github.io"> React Strap </a> <br>
<a href="https://reactstrap.github.io/components/navbar/"> React Strap - Navbar </a> <br>
<a href="https://react-bootstrap.github.io/getting-started/introduction"> React Bootstrap - Getting Started </a> <br>
<a href="https://react-bootstrap.netlify.com/components/cards/#cards"> React Bootstrap - Cards </a><br>
<a href="https://react-bootstrap.github.io/components/carousel/"> React Bootstrap- Carousels </a> <br>
<a href="https://openweathermap.org/api"> Weather API </a><br>
<a href="https://help.github.com/en/github/writing-on-github/working-with-advanced-formatting"> GitHub- Advanced Formatting</a><br> 
<a href="https://github.com/sei-jed-10/React-App-Deployment-Steps"> React-App-Deployment-Steps </a>
