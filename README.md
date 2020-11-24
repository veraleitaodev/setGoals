<h1 align="center">SetGoals</h1>

[View the live project here.](http://set-goals-vl.herokuapp.com)

This is the website built to meet the requirements for milestone 3 of fullstack developer diploma at Code Institute. It is designed to be responsibe and accessible on a range of devices, making it easy to navigate for users and visiting users.

I aim to develop and test a platform to enable individuals life by setting and planning their goals. “Failing to plan is planning to fail”; “You become what you think about most of the time”.  
This platform will enable people to edit their goals, store them according to priority. The Individual is encouraged to use a forum to publish accomplishments.

![responsive app](static/images/multiple-devices.jpeg)

## User Experience (UX)

- ### User stories

  - #### First Time Visitor Goals

    1. As a First Time Visitor, I want to easily understand the main purpose of the site and learn more about setting goals.
    2. As a First Time Visitor, I want to be able to easily navigate throughout the site to find content.
    3. As a First Time Visitor, I want to be able to easily register on website as user and set first goals.

  - #### Returning Visitor Goals

    1. As a Returning Visitor, I want to easily refer back to the main steps of setting smart goals.
    2. As a Returning Visitor, I want to easily log in to my goals page.
    3. As a Returning Visitor, I want to be able to create, update and delete my goals.

  - #### Frequent User Goals
    1. As a Frequent User, I want to explore content in image boards online related to my goals. As images are a powerful tool to help focus in goals.
    2. As a Frequent User, I want to easily access my current goals and costumize them.

- ### Design
  - #### Colour Scheme
    - The two main colours used on the website are inspired by this [photo](https://www.behance.net/gallery/45528461/Selectologie) using [ adobe color ](color.adobe.com) software.  
      ![alt text](static/images/colours.jpeg "generated colour scheme")
  - #### Typograpy
    - The Gruppo font is the font used for the Logo with Sans Serif as the fallback font in case for any reason the font isn't being imported into the site correctly. Gruppo Font is a display typeface that comes with clean and clear texture.
    - The Noto Sans font in the main font used throughou this project, with Sans Serif as the fallback font.
  - #### Imagery
    - The background hero image is chosen as a path and is divided in two. It is designed to be striking and give the user the ilusion of discovering a path.  
      The svg image used in the middle div in home pageuses the same colour as navbar and footer and is supposed to suggest planning ideas. The same svg is used in my goals card while upload image is not available.

* ### Wireframes

  - [Register page in desktop and tablet view](static/images/wireframes/register_dt.png "wireframe for register page in desktop and tablet view");

  - [Register page in mobile view](static/images/wireframes/register_mobile.png "wireframe for register page in mobile view");

  - [Login page in desktop and tablet view](static/images/wireframes/login_dt.png "wireframe for login page in desktop and tablet view");

  - [Login page in mobile view](static/images/wireframes/login_mobile.png "wireframe for login page in mobile view");

  - [Home page in desktop and tablet view](static/images/wireframes/home_dt.png "wireframe for Home page in desktop and tablet view");

  - [Home page in mobile view](static/images/wireframes/home_mobile.png "wireframe for Home page in mobile view");

  - [New Goal page in desktop and tablet view](static/images/wireframes/newGoal_dt.png "wireframe for My progress page in desktop and tablet view");

  - [New Goal page in mobile view](static/images/wireframes/newGoal_mobile.png "wireframe for New Goal page in mobile view");

  - [Goal page in desktop and tablet view](static/images/wireframes/goalPage_dt.png "wireframe for Goal page in desktop and tablet view")

  - [Goal page in mobile view](static/images/wireframes/goalPage_mobile.png "wireframe for New Goal page in mobile view");

## Features

- Responsive on all device sizes

- Interactive elements

- Register and Login

- Create, update and delete data

## Technologies Used

### Languages Used

- [HTML5](https://en.wikipedia.org/wiki/HTML5)
- [CSS3](https://en.wikipedia.org/wiki/Cascading_Style_Sheets)
- [Javascript](https://en.wikipedia.org/wiki/JavaScript)
- [Python3](<https://en.wikipedia.org/wiki/Python_(programming_language)>)

### Frameworks, Libraries & Programs Used

1. [Materialize 1.0.0:](https://materializecss.com)
   - Materialize was used to assist with the responsiveness and styling of the website.
2. [Google Fonts:](https://fonts.google.com/)
   - Google fonts were used to import Gruppo and Noto Sans fonts into the style.css file which is used on all pages throughout the project.
3. [Font Awesome:](https://fontawesome.com/)
   - Font Awesome was used throughout the website to add icons for UX purposes.
4. [jQuery:](https://jquery.com/)
   - jQuery came with Materialize to make the navbar toggle, the collapsible bars, dropdown menu, the parallax effect in home page, the tooltip effect in edit and delete Icons, the card hide/show content, but it was also used for the alert box with function in JavaScript.
5. [Git](https://git-scm.com/)
   - Git was used for version control by utilizing the Gitpod terminal to commit to Git and Push to GitHub.
6. [GitHub:](https://github.com/)
   - GitHub is used to store the projects code after being pushed from Git.
7. [Photoshop:](https://www.adobe.com/ie/products/photoshop.html)
   - Photoshop was used to resize images for the website.
8. [Balsamiq:](https://balsamiq.com/)
   - Balsamiq was used to create the [wireframes](https://github.com/) during the design process.
9. [Adobe Color:](https://color.adobe.com/create/color-wheel)
   - Adobe Color was used to generate the color scheme.
10. [Flask:](https://pypi.org/project/Flask/)
    - Flask was used in the html templates including a base template.
11. [Jinja2:](<https://en.wikipedia.org/wiki/Jinja_(template_engine)>)
    - Jinja is part of the Flask library and was used throughout this project.
12. [Werkzeug:](https://pypi.org/project/Werkzeug/)
    - Werkzeug is part of the Flask library and was used throughout this project to encrypt data.
13. [PyMongo:](https://pypi.org/project/pymongo/)
    - The pymongo package is a native Python driver for MongoDB. crucial in the communication of python with MongoDB, both used in this project.
14. [MongoDb:](https://www.mongodb.com/)
    - MongoDB is a document database and is used to store the data input from the forms in new goals page. The data stored is created, updated and deleted in mongoDb through the app.

## Testing

Please refer to [testing.md](testing.md) file to find the report on the testing carried out in this project.

## 6. Deployment

## 7. Credits

- RegEx code to validate email address obtained from https://stackoverflow.com/questions/17464404/html5-pattern-attribute-not-matching-for-emailusergmail-com
- upload image file section in new-goal.html - code obtained from https://codepen.io/opznhaarlems/pen/mKymJy and adapted to this Project
- information in how-to.html obtained from https://www.ucop.edu/local-human-resources/_files/performance-appraisal/How%20to%20write%20SMART%20Goals%20v2.pdf
- code obtained from https://stackoverflow.com/questions/26393539/css-solution-to-hide-div-after-x-amount-of-seconds to hide div after 4 seconds\*/
