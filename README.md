# Welcome to Get Fed. 

## [Live Site](#)

## [GitHub Repo](https://github.com/Craig-Ryan/get-fed-MS3)


![Am I Responsive Image](https://codeinstitute.s3.amazonaws.com/fullstack/ci_logo_small.png)

Get Fed is my 3rd miilestone project from the [Code Institute](https://codeinstitute.net/) Full Stack Web Development Course. 

# Table of Contents

---

# Project Overview
---
Get Fed is an online cookbook where visitors to the site can browse a selection of recipes added by admin and other users. A visitor will have the choice to simply browse or create their own profile in order to add their own recipes to the site and it's database. Each user will also have the choice to delete their profiles and personal recipes. 

!!! Document your decisions - and the reasons for  these decisions - at each stage of the 5 planes,  
and include this information in  the UX section of your README file. !!!

!!! Speaking of user stories, these are a particularly  important part of your project to define in detail  
before you get started with your coding. They  clearly define the needs and wants of your target  
audience, !!!

---

# User stories

## User
- As a new user, I would like to be able to browse through recipes easily.
- As a returning user, I would like to have the option to register to add my own recipes.
- As a registered user, I would like to be able to add, edit and delete my recipes.
- As a casual user, I would like to be able to view the recipes on any device comfortably.
- As a user, I would like to see other content on the site relating to cooking i.e, cookbooks, utensils etc.

## Owner
- As owner of the site I would like to be able to moderate user profiles and add/edit/delete recipes. 

# UX Planes

## Strategy Plane

- <em>Purpose:</em> The purpose of this project is to showcase my understanding of the materials covered so far in the course. It is the first that time I will be using frontend and backend programming together. The building of this project will consist of a combination of HTML, CSS, jQuery, Javascript, Python, MongoDB, Flask & Jinja.

- <em>Business Goals:</em> The overall business goal of this project is to provide users with an online cookbook that is intuitive from the first visit and sparks a positive emotional response resulting in returning visits from users. The website will provide users with the options to view all recipes across all devices, to register their own account and to be able to add/edit/delete their own recipes. 

- <em>Target Audience:</em> This website appeals to a broad target audience as recipes can range from any level of difficulty due to individual entries. Users have the choice to try any recipe stored on the site or to add their own personal recipes to the database. 

## Scope Plane

- This project serves as an online cookbook for any user to access. My top priority is to design a simple yet effective website that allows a visitor to easily navigate through the site, to browse recipes and to register an account in order to add/edit/delete personal recipes. 

- A search option is included to allow users to locate any recipes they may like to try.

- The content represented has been carefully considered in order to illicit positive emotional responses from individual users and to maximise user interactivity to encourage users to return to the site. 

- A register functionality is available for users wishing to add their own recipes to the site. 

## Structural Plane

- The structure of the site is laid out to be consistent for the benefit of the user. Across each page at the top of the page, there is a navbar with the site's logo and name along with links to other parts of the site such as Log In, Register and Resources. On smaller devices a dropdown menu represented by bars houses the links within the site. 

- On the main index page there is a search bar which allows a user to search a recipe or ingredient by name and all recipes housed in cards for tidy, minimialistic presentation. 

- As the site follows consistent design, each page shares common design traits. The Log In/Register Pages are almost exact copies just with different functionality.

- The resources page consists of hand-picked cooking-related resources from the owner.

- A footer at the bottom of each page houses our copyright information and some links to our social media.


## Skeleton Plane

- The mock-up for this site was created using Balsamiq Wireframes. I wanted to get an idea for the best possible design for the end product of this project. A logo was sourced from Google Images. 


## Surface Plane

- In order to keep with consistency the same colors and fonts are used across the entire project.

### Design 

- The design is responsive across mobile, tablet and personal computer screen sizes. 

### Typography 

- The project uses the fonts X and X from [Google Fonts](https://fonts.google.com/)

### Colors 

- The colors used in tis project are XXXX sourced from [Color Hunt](https://colorhunt.co/) and [Adobe Color](https://color.adobe.com/create/color-wheel/)

#### Media 
- [Color Hunt](https://colorhunt.co/)
- [Adobe Color](https://color.adobe.com/create/color-wheel/)
- [Balsamiq](https://balsamiq.com/)

#### Back to [top](#table-of-contents)

---

# Features

## Existing Features 

### Elements across every page

#### Navbar

- The navbar is consitent across each page on the site. It houses links to the home page next to a logo, the user's profile, a resources page, log in and register pages.

- Non-registered users see a list of options within the navbar as follows:
    1. Resources
    2. Log In
    3. Register

- Registered users see a slightly different version of the navbar when logged in:
    1. My Recipes
    2. Resources
    3. Log Out

- On screens below large resolution, the navbar contents are consolidated into a 'hamburger' menu for better UI.

- Python checks a user's session data in order to retrieve the correct navbar content to be passed through to Jinja to be displayed on the site.

#### Footer

- The footer is designed to be simple and to the point, it contains:
    1. The project's name and copyright information.
    2. Social media links for users to follow.


- Hover effects over buttons are constant across all pages.

### Elements on the 'Home' page:

- A search bar allows users to search recipe names and ingredient names. 
- All recipes are housed in cards 

### Elements on the 'My Recipes' page:

- The user's name is housed in a container displaying the user's name followed by profile.
- Each of the user's personal recipes are stored in a card displayed in a grid.
- Buttons with the option to delete or edit a recipe sit below the recipe cards.

### Elements on the 'Resources' page:

- A grid with suggested materials from the owner sit in a grid housed in cards.
- Each card serves as a link to a 3rd party website where users can purchase or learn more about the particular resource.

### Elements on the 'Log In' page:

- A container with the title of 'Log In' prompts a user to enter their details in the form below.
- A form asks a user to input 'Username' and 'Password' details folowed by a 'Submit' button.
- On successful entry, a user is brought to their unique profile or 'My Recipes' page.
- Unsuccessful entries result in a flash message that prompts the user to re-enter their details.

### Elements on the 'Register' page

- A container with the title of 'Register' prompts a user to enter their details in the form below.
- A form asks a user to input 'Username' and 'Password' details folowed by a 'Submit' button.
- On entry, a user is brought to their unique profile or 'My Recipes' page.

## Future Features 

- A favorite button for users to add other recipes to their profiles.
- A review comment functionality under individual recipes.
- A share function for users to share recipes from clicking an icon rather than copy/paste-ing the link address.

# Technologies used

## Languages & Frameworks
- [HTML5](https://developer.mozilla.org/en-US/docs/Web/HTML) - used to build the site structure.
- [CSS3](https://developer.mozilla.org/en-US/docs/Web/CSS) - used to add personal styling to the site.
- [JavaScript](https://developer.mozilla.org/en-US/docs/Web/JavaScript) - used for adding personalised functionality on the site i.e adding/editing/deleting content. 
- [Jinja](https://flask.palletsprojects.com/en/1.1.x/) - used to display data from the backend to the frontend.
- [jQuery](https://jquery.com/) - used in conjunction with Materialize code for functionality of hover states for example. 
- [Python](https://www.python.org/) - used to write logic for running the site. 
- [Flask](https://flask.palletsprojects.com/en/1.1.x/) - used to improve efficient use of HTML templates.
- [MongoDB](https://www.mongodb.com/) - used as the database to house the data of this site.
- [Materialize](https://materializecss.com/) - used to apply clean styling to the site's pages.
- [Heroku](https://www.heroku.com/) - used to host the site. 
- [Font Awesome](https://fontawesome.com/) - used for icons for better UX. 
- [Google Fonts](https://fonts.google.com/) - source of the typography used in this project.
- [dnspython]()
- []()