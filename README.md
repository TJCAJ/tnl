# The Nut Low

The Nut Low is a website customised for a small and very specific target group. This is for members in a local poker club in Stockholm, Sweden. Created to make it easier for members to meet, socialise and playing poker together. It will be a handy tool for members and useful to schedule tournaments more frequently. The website also aims to explain the basics of some of the most common poker games. [View the live site here](https://tjcaj.github.io/nutslow/index.html)

![Responsice Mockup]

This my first Milestone project for Code Institute's Full Stack Software Development Diploma. It was built using HTML and CSS. GitPod was used for writing the code for this website, as well as committing and pushing to GitHub. GitHub was then used to store the project after it had been pushed from GitPod. I choosed to deploy the website via GitHub quite early in the development process, as I figured it made sense to test my modest coding skills and try to minimalize errors before submission.

## Design

The looks and the feel of the website is created with red, white green and black colours. Inspired from the most common colours related to playing poker and other card games. This also helps to user visual with strong contrasts and is easy to navigate through.


## Features

- __Navigation Bar__

  - Visible on all the website pages. Consists of links to Home, Gallery and a Log in/Sign up page that will be responsive on all devices. This will allow users navigate the website's pages on any device in a seamless flow without having to revert back to the previous page via the ‘back’ button.

  - This was also the thing I spent way to much time trying to figure out why the code didn’t respond as I intended with a similar solution to the Love Running project. Having the menu items visible on larger screens and just a menu bar on phones and similar devices with smaller screens.
 

![Nav Bar Mockup]

- __The landing page image__

  - The landing page image is an ai generated picture that I’ve generated through [fotor.com](fotor.com) It consists of a classic poker table with a player visible in a dark and smoky room. This introduces the user to the website with a strong visual animation in order to to grab their attention. In a simple way it also reveals the main topic for the website.


![Landing Page](https://github.com/)

## Website information

The main body of the homepage welcomes the user and intend to describe what and who it is created for via clear and consist information about KPC United’s poker club in Stockholm, Sweden. 

#### KPC United
Here I also added a separate description about the club, its members and a brief historic background as an introduction and helpful guide to new users and whoever is interested in joining the club.


- __The Nut Club Section__

 Is a vital part of the website that depict an overview of recent winners and tournaments. This should encourage the user to use its member service and for others to join the club and share their passion for poker.

This is also where we have a short description of some of the most common poker games with information that I’ve translated from the Swedish online version of the poker website [888poker](https://www.888poker.se/magazine/strategy/poker-variations)

- __Meetup Times section__

  - This section will allow the user to see dates for upcoming poker tournaments and who hosts the event.
  - My intention is that this section will be updated with status of seats taken and when it's fully booked, as the members sign up for each event via the Log in/Sign up form.
  - In this way this section helps to keep the user up to date.

![Meetup Times](https://github.com/)

- __The Footer__ 

  - The footer is visible on all pages. This section contain icons as links to social media sites for members to share their love for poker. The links opens to a new tab to allow easy navigation and accessible to the visually impaired who may be using a screen reader, by the use of aria labels.

  - The footer is valuable to the user as it encourages them to stay connected and up to date via social media.


![Footer](https://github.com/)

- __Gallery__

  - The Gallery consist of pictures from pexels.com for now. It is added to the website in order to inspire how fun and exciting it is to play poker with KPC United.
  -  I’ve made sure that all the images was processed and compressed in file size via Adobe Photoshop to compressed .webp-files in order to enhance the user experience.
  - In order to make the Gallery responisve I was adviced by my mentor to look at a [Youtube video](https://youtu.be/2uvyx4YK_rQ?feature=shared) about Flexbox. This helped me in my efforts to create a responsive gallery.

![Gallery](https://github.com)

- __The Log in/Sign up Page__

  - This page will help the user to log in on their account and submit to upcoming poker tournaments under the auspices of KPC. The user will be able specify the date they would like take a seat with a maximum of 16 players at every event. The user will be notified of their status via email from the KPC administrator.

![Sign Up](https://github.com/)

### Features Left to Implement

- As future enhancements, the Log in/Sign Up form can generate an an immediate and automatic response to the user with a clear message of their status - a.k.a. if the user gets a seat at the upcoming event or not. In this way the user can always log in to check their status.
- The Gallery can certainly be improved with a rolling gallery where images shift frequently and also allow for users to upload their own pictures related to KPC United poker games.
- The website can be structured in a more informative and user friendly way with more content/pages that describes the most popular poker games in more details, with tips and tricks to improve your game as a poker player.
- More links can also be added to various online poker card rooms with descriptions of what services the provide

## Design

![Home](http:..png)

## Testing 

Information about the tests ca be viewed [here](Test.md)

### Validator Testing 

- HTML
  - No errors were returned when passing through the official [W3C validator](https://validator.w3.org/nu/?doc=https%3A%2F%2Fcode-institute-org.github.io%2Flove-running-2.0%2Findex.html)
- CSS
  - No errors were found when passing through the official [(Jigsaw) validator](https://jigsaw.w3.org/css-validator/validator?uri=https%3A%2F%2Fvalidator.w3.org%2Fnu%2F%3Fdoc%3Dhttps%253A%252F%252Fcode-institute-org.github.io%252Flove-running-2.0%252Findex.html&profile=css3svg&usermedium=all&warning=1&vextwarning=&lang=en#css)

### Unfixed Bugs

Favicon are customised  with favicon.io and copied into the code according to their info but when the website is loaded it’s not showing.

The landing page mimage not responsive. As I talked with my mentor he helped me figure out that it was easier to add the hero image as a < img > tag in the HTML rather than as a url and styling in the CSS. This solved my issue.

The menu bar was a hard and lasting problem for me. I couldn’t understand why it didn’t work despite that the code looked good to me, accordingly to the method I’ve learned in the Love Running Project. The real breakthrough was unexpected. I simply made an error in the CSS styling as I started to add headings and paragraphs to the main section. I typed { ( which resulted in breaking up my code and (!) Showing the menu bar as intended on smaller devices with the correct function in place… However after several attempts to understand why this happened I had my second mentor call that pointed me in the right direction. I thought I knew it had something to do with the flex box properties…

GitPod in Visual studios on my MacBook Pro didn’t work as easy as working directly in the browser for me. As a beginner with all these new platforms and development tools it is a constant battle trying to understand why and how all functions works in each dev tool. A simple thing here was that I couldn’t change the text in Visual studios. Nothing happened and it was hard to google any answers. For me it was easier to stick to the browser that worked as submission day closed in.

Git commit… I am a beginner and this was a real struggle for me in the beginning as I tested out code and functionality on various elements  in a rapid haste. Made several errors with this, but as it goes one can only get better with experience. Googled a lot and studied the Love Running project several times to improve on this.

## Deployment

The site was deployed to GitHub pages. But it was not without a minor issue. As I deployed my website it didn’t go through Github for a long time. Then I realised that it was due to the fact that I hadn’t pushed my last commits. This made the deployment to fail. The solution again was to google and find the answer. 


- The site was deployed to GitHub pages. The steps to deploy are as follows: 
  - In the GitHub repository, navigate to the Settings tab 
  - From the source section drop-down menu, select the Master Branch
  - Once the master branch has been selected, the page will be automatically refreshed with a detailed ribbon display to indicate the successful deployment. 

The live link can be found [here](https://tjcaj.github.io/nutslow/)


## Credits 

Inspiration for the readme file was taken from The Love Running Project as well as my mentor Gareth McGirr and my fellow students Martiless (flawlesscooking), Airdrie86 (life-hack) and Kera Cudmore.

## Acknowledgements
Thanks to my mentor for helpful feedback and creative input as well as mental support and encouragement by my student Cohort facilitator on Slack, Kristyna Ci.

## Technologies used

For the purpose of this project, the following technologies were used.
### Languages:
HTML
CSS

### Frameworks, Libraries, Programs & Applications Used:
### Google Font
Google fonts were used to import the following fonts Big Shoulders Display and  Paytone One. These were imported to style.css and were used throughout the project.

### Font Awesome
Font Awesome was used on each page of the website to provide icons for UX purposes.

### GitPod
GitPod was used for writing all the code for this project. It was also used to commit and push to GitHub.

### GitHub
GitHub was used to store this project.

### GitPages
GitPages was used to deploy the project.

### ### Balsamiq
Balsamiq was used to draw initial Wireframes for this project.

### Am I Responsive
Am I Responsive was used to check that each page of the site was responsive. It was also used to create the mock-up image seen at the beginning of this document.

### Google Development Tools
Google Dev Tools was used to edit code and check responsiveness before making the changes permanent.


## Content 

- The text about poker games for the The Nut Club section was copied and translated from [888poker](https://www.888poker.se/magazine/strategy/poker-variations)
- Code snippet for the the Log in/Sign Up page was taken [from](https://codepen.io/ig_design/pen/KKVQpVP)
- The icons in the footer and the menu bar were taken from [Font Awesome](https://fontawesome.com/)


## Media

Favicon was created via favicon.io

Images - Pexels and private pictures.

Fonts - Google fonts.

Icons - Font Awesome.