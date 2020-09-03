# CI-MS1

Code Institute Milestone 1 Project

This website is a resume giving a brief overview of my skills and experience built up over my working life. The site has been created to highlight my skills and experience without going into too much detail. A link to my CV has been provided for those that are looking for a deeper dive.

Screenshot of final website on different screens: ![Screen Sizes](https://github.com/Chains74/CI-MS1/blob/master/Documentation/MS1%20Screens.png)

## UX
The website is for potential employers to be able to quickly see what my main skills are and they will also be able to see a brief work history with pertinent details from those roles.

Basic Wireframes:

- [Desktop Wireframe](https://github.com/Chains74/CI-MS1/blob/master/Documentation/Wireframes/Desktop%20Wireframe.pdf)
- [Tablet Wireframe](https://github.com/Chains74/CI-MS1/blob/master/Documentation/Wireframes/Tablet%20Wireframe.pdf)
- [Mobile Wireframe](https://github.com/Chains74/CI-MS1/blob/master/Documentation/Wireframes/Mobile%20Wireframe.pdf)

Website MockUps:

- [Desktop Mockup](https://github.com/Chains74/CI-MS1/blob/master/Documentation/Mockups/Desktop%20Mockup.pdf)
- [Tablet Mockup](https://github.com/Chains74/CI-MS1/blob/master/Documentation/Mockups/Tablet%20Mockup.pdf)
- [Mobile Mockup](https://github.com/Chains74/CI-MS1/blob/master/Documentation/Mockups/Mobile%20Mockup.pdf)

## Features

The site consists of 4 pages. The homepage which contains a brief bio and a short list of skills and interests. A Skills page which shows my support and development skills in a little more detaill, a history page which shows a timeline of the last 5 positions I've held and a contact page with location detail and a dummy phone number and contact form.
 
### Existing Features
- Feature 1 - Contact form allows people to send me message directly Does not contain a mailto action, so will refresh when the submit button is pressed..
- Feature 2 - Link to CV to allow potential employers to download a PDF copy of my CV.
- Feature 3 - Link to my LinkedIn and Github pages.


## Technologies

- HTML5:  
HTML was used to define the basic structure of the site. Utilising standard HTML elements such as Divs, Unordered and Ordered lists and Paragraphs.

- CSS3:  
Cascading Style Sheets were used to style the pages of the sites by using user created and exisint Bootstrap classes.

- [Bootstrap 4](https://getbootstrap.com):  
Bootstrap 4 was used to help structure the rown and columns for the Bootstrap grid on the Skills page. It was also utilised for the Contact form on the contacts page, to allow the form fields to stack on top of each other at smaller screen sizes.

- [Google Fonts](https://fonts.google.com/):  
Was used for the 3 fonts used in the website for the body and headings. 

- [Font Awesome](https://fontawesome.com/):  
FA was used to add icons on the Skills page for the Support and Development section headings. It was also utilised for the Github and LinkedIn social links in the footer.

- [Atom](https://atom.io/):  
I used Atom as my editing environment as I like the ability to customise it to aid my worklfow through adding Atom packages to the editor.

- [Adobe CC 2020](https://www.adobe.com/):  
I used Adobe Photoshop and Illustrator to manipulate the icons and images used on the website.

- [Github](https://github.com/):  
I utilised Git and Github to control and commit  changes made to the site using the Github package in Atom and the Github desktop application.

- [Github Desktop](https://github.com/desktop/desktop):  
I used Github Desktop to push and fetch files to and from the Projects Online repository.

- [W3C Markup Validation Service](https://validator.w3.org/):  
I used the W3 online Markup validation tool to check my HTML code and then fixed any issues that arised.

- [W3C CSS Validation Service](http://jigsaw.w3.org/css-validator/#validate_by_uri):  
I used the W3 CSS validator to validate my CSS.


## Testing

Although I have not automated testing on this site, I have tested the site on a multitude of different devices and sizes. This includes a 5K 27" iMac, 13' MacBook Pro, the MBP connected up to a 1080P External Monitor, an 11.9" iPad, an iPad Mini and iPhone 4, 5S, 6 and 7, along with a Samsung Galaxy J3.
The site has also been tested on the folowing browsers: Safari, Firefox, Google Chrome, Vivaldi, Opera and Brave.  The developer tools on all browsers were used to check responsive and test the site on the various device sizes the inspector offers.
I have asked a few friends and family to test the site site and make sure they can navigate it easily and to report back with any issues.
The links have been tested and all open in new tabs within the same browser as the site. On the Contacts page all fields will need to be filled in to submit. The email field will need a valid email address to clear the validation.. 
Had an issue where the timeline elements were stretched to wide on high resolution screens. This was fixed by using a media query to change the width of the timeline content on the higher resolution screens.
The user will find the site to be easy to navigate with simple links in the navigation bar at the top of the screen. This collapses down on smaller screens and is still easy to access when it expands when clicked on. There are no embedded videos or audio as with the website being a resume I wanted it to be clean, sleek and professional looking.


## Deployment

I uploaded the project files to Github and deployed the site usingGithub pages. 

To upload the project to Github I used the process below:

1. Downloaded and installed the Github Desktop application. Logged into my Github account.
2. Installed the Github package into Atom, and connected to my Github account.
3. Staged the changes to the sites pages using the Atom Github pakage and added the Commit message.
4. Pushed the changes to the online repositry using Github Desktop.

To deploy the project using Github Pages  I used the process below:

1. Logged into my GitHub account
2. Clicked on the link to the project repository.
3. Clicked on the Settings link in the project repository.
4. Scrolled down until I found the GithubPages section.
5. Selected Master from the Branch dropdown menu under Source and clicked Save.
6. After a few minutes the link for the published page appeared, which is: 
    
    https://chains74.github.io/CI-MS1/

As I used a local IDE to create the site, all the files already exist locally on my machine. To run the code locally, it is just a case of accessing the  folder containg the files and opening any of the html files from the project in the browser of my choice.


## Credits

### Content
- The application icons for the site where taken from the installed app packages on my machine by showing the package contents and finding the app icon. These were then resized to requirements by using Adobe Photoshop and Illustrator. The Developer icons were found on www.flaticons.com.

### Media
- The profile photo used in this site is one of my own and was converted into a transparent background png using Adobe Photoshop.

### Acknowledgements

- I received inspiration for this project from the CV project in the User Centric Front End Development module.

- I received help from Anthony O'Brien on the CI #user-centric-frontend Slack channel, when I had an issue with my collapsed Navbar not expanding. Anthoony found I had set the position for the navbar where it wasn't needed.

- I used https://onaircode.com/html-css-horizontal-timeline-examples/ to get inspiration and a better understanding of how to code a timeline correctly by looking at the code examples to see how they were put together. 

- I used Stackoverflow to find the answer to how to set the iorder of the links in the footer when stacked on smaller screen sizes.
