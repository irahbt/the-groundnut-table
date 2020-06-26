# The Groundnut Table 
## Milestone project 1: User-Centric Frontend Development - Code Institute

This is a website for “The Groundnut Table” supper-club. It is designed to be easily recognisable as such and responsive on a range of devices to increase accessibility. The layout of the site is clean and has conveniently placed navigation throughout. This ensures that any prospective guests are able to easily gather the information necessary to make a decision. The website will be used for marketing purposes to extend the reach of the supper-club beyond it’s current client base. 

![Responsive design image](https://github.com/irahbt/the-groundnut-table/blob/6641b44222eb30b1d7357ad8141f929e82614825/assets/images/readme-images/responsive-design.png)



[View the live demo version here](https://irahbt.github.io/the-groundnut-table/ "Live demo version")

 
## User Experience (UX)

### User stories

- #### First Time User Goals

   1. As a First Time User, I want to understand the main purpose of the enterprise 
   
   2. As a First Time User, I want to be able to navigate intuitively through the site 
   
   3. As a First Time User, I want to easily find any social media links to learn more about the company and establish trustworthiness 

- #### Returning User Goals

   1. As a Returning User, I want to find when and where the next supper club will take place and how much it will cost 
   2. As a Returning User, I want to find how to register my interest in attending a supper club. 

 - #### Frequent User Goals

   1. As a Frequent User, I want to check to see if there are any newly added supper club dates. 


### Design 

#### In order to maintain brand identity, the design was inspired by [The Groundnut Cookbook](https://www.amazon.co.uk/dp/0718179412/ref=cm_sw_em_r_mt_dp_U_PiB9Eb2421508 "Cookbook") which was published following the success of the The Groundnut Table supperclub. 

- #### Colour Scheme
    -  The three main colours used are orange, white and grey in accordance with the branding.

-   #### Typography
    -  The Spartan font is used throughout the website with Sans Serif as the back-up font. Spartan closely resembles the typography used for the Groundnut Cookbook, creating brand consistency and recognisability. Varying font weights and letter-spacing where used for aesthetic and distinguishing purposes. 

-   #### Imagery
     -   Each background image shows a part of the table used during the supper club to reinforce the nature of the business. The images correlate with each other to create a story-board effect that is intriguing to the user.  

-   #### Layout 
     -   The layout of the site was designed to be as intuitive as possible for the user, with information being presented in a logical manner Home, introduces the company. About, provides information as to what the company does. Details, provides details of the events and Seats, allows users to sign up having been given all the necessary information. 

### Wireframes



## Features

### Existing Features

-	The site uses bootstrap grid and media queries in order to be responsive at a variety of sized 
-	Hover-overs are used to indicate that an element is interactive  
-	Animation is used on the homepage to provide a slow-reveal effect
-	The navbar collapses on smaller screen sizes to conserve screen real estate 
-	Parallax scrolling effect is used on background images to deliver a unified experience to users
-	Parallex is only supported on desktop devices, to compensate for this, media queries were used to position the background image on smaller devices such as tablets and mobile phones. 
-	The addition of Smooth Scrolling gives the impression of seamlessness

### Features Left to Implement
- Currently, the collapsed navbar on smaller screens remains on the screen after a link has taken the user to their selected destination, this mean the user has to press the burger icon twice which is bad UX. We would like to implement a feature that collapses the navbar list automatically once the user has reached the targeted href
- We would like to provide feedback once the submit button has been activated on the form for seats, to re-assure users that their request has been acknowledged 
- In the future, we would like to include a “Sign-up for the Newsletter” check-box on the Seats form that would provide customers with information regarding events

## Technologies Used

### Languages Used

- [HTML5](https://en.wikipedia.org/wiki/HTML5)
- [CSS3](https://en.wikipedia.org/wiki/Cascading_Style_Sheets)


### Frameworks, Libraries & Programs Used

1. [Bootstrap 4.5:](https://getbootstrap.com/docs/4.5/getting-started/download/)
    - Bootstrap was used to help make the website responsive on a range of devices

2. [Hover.css:](https://ianlunn.github.io/Hover/)
    - Hover.css was used on the Social Media icons in the footer of the page to implement the grow transition when the icons are hovered over 

3. [Google Fonts:](https://fonts.google.com/)
    - Google fonts was used to import the ‘Spartan’ font into the style.css

4. [Font Awesome:](https://fontawesome.com/)
    -  Font Awesome icons were used for the details section and the social media links in the footer

6. [Git](https://git-scm.com/)
    - The Gitpod terminal from Git was used to commit to Git and Push to GitHub
.
7. [GitHub:](https://github.com/)
    - GitHub was used to store the code after being pushed from Git

8. [Figma:](https://www.figma.com/)
    - Figma was used to create the [wireframes](figma link) during the design process.



## Testing

The W3C Markup Validator and W3C CSS Validator Services were used to validate the project:

-   [W3C Markup Validator](https://validator.w3.org/#validate_by_input) - [Results - find better link!](https://validator.w3.org/nu/#textarea)
-   [W3C CSS Validator](https://jigsaw.w3.org/css-validator/#validate_by_input) - [Results - find better link!](http://jigsaw.w3.org/css-validator/validator$link)

### Testing User stories

- #### First Time User Goals

   1. As a First Time User, I want to understand the main purpose of the enterprise 

        * The hero image provides visual cues as to the nature of the company (a table)
        * The heading is positioned in the centre of the page to ensure focus. The heading states the company name, which also contains the company logo
        * The navigation bar provides users with four clear options home (refreshes the page), about, details and seats

   
   2. As a First Time User, I want to be able to navigate intuitively through the site 

        * Upon entering the site, the navigation bar is positioned at the top of the page and unobstructed by any images.  This makes it easy for users to locate and read 
        * The navigation bar is stuck to the top of the screen so the user is always able to navigate wherever they are in the site
        * In accordance with UX expectancies the logo, in the right-hand corner, navigates users back to the homepage
        * All navigation links provide feedback to the user with hover overs, this makes them easily identifiable as links

   
   3. As a First Time User, I want to easily find any social media links to learn more about the company and establish trustworthiness 

        * Social media links can easily be found at the footer of the page. Icons are used for UX purposes 


- #### Returning User Goals

   1. As a Returning User, I want to find when and where the next supper club will take place and how much it will cost 

         * All of this information is clearly laid out in the details section. Icons are used to signpost specific information e.g. a calendar for dates

   2. As a Returning User, I want to find how to register my interest in attending a supper club. 
         * The title of “seats” is used for the register page as a continuation of the table theme 
         * The seats page includes a form that clearly shows the information required to book, error messages will appear if this information is not entered correctly
 
 - #### Frequent User Goals

   1. As a Frequent User, I want to check to see if there are any newly added supper club dates. 
         * The dates sections is clearly signposted with a calender icon in the details section. A "new" badge has been added to the latest date to indicate that new dates are added regularly. This is reinforced in the seats form which states that new dates are added on the first of every month


### Testing Interactive Elements 

- #### All navigation links send users to the expected destination


 - #### Youtube Video:
    - the video does not autoplay on opening the page 
    - the video responds to all buttons (play, fullscreen etc.)
    - the video automatically enters full screen when on smaller devices to allow for optimum viewing  

 - #### Seats Form:
    - An error message appears when required fields are empty 
    - An error message appears an invalid email address 
    - when all inputs are valid the submit button refreshes the page and returns the user to the seats page. The page must be refreshed before filling out the form again   

### Further Testing

- The Website was tested on Google Chrome, Firefox, Microsoft Edge and Safari browsers.
- The website was tested on a variety of devices such as Desktop, Laptop, iPad mini,  iPhone 7, iPhone 8, iPhoneX and Nokia E30
- Friends and family members viewed the site and provided feedback on bugs and UX issues

### Known Bugs 

- On Internet Explorer, only certain css is applied 
- On Internet Explorer, all text is push to the right hand side of the screen. Due to these issues we would suggest that the website is not accesable on Interenet explorer at this time
- On small devices the footer re-aranges  

## Deployment

### GitHub Pages

The project was deployed to GitHub Pages using the following method:
    
1. On GitHub, navigate to the site's repository, "irahbt
/the-groundnut-table" LINK 
2. Under the repository name, there is a menu, locate the "Settings" button and click on it 
3. Scroll down the Settings page until you reach the "GitHub Pages" section
4. Under "GitHub Pages", use the Source drop-down menu and select a publishing source, select "Master Branch"
5. The page should automatically refresh at this point 
6. Scroll back down to the "Github Pages" section to find the now published site to locate the now published site https://irahbt.github.io/the-groundnut-table/

### Making a Local Clone
1. On GitHub, navigate to the site's repository, "irahbt
/the-groundnut-table" LINK 
2. Above the list of files, click  Code.
3. To clone the repository using HTTPS, under "Clone with HTTPS", click ..

## Credits

### Code

-   The parallex scrolling effect came from LINK

-   [Bootstrap 4.5](https://getbootstrap.com/docs/4.5/getting-started/introduction/): Bootstrap Library used throughout the project for styling and layout purposes, it was also used to make the site responsive where appropriate 

### Content

-   The About content was taken from the "The Groundnut cookbook" with permission from the authorse.



### Media

-   

### Acknowledgements

