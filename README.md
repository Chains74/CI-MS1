# CI-MS1

Code Institute Milestone 1 Project

This website is a resume giving a brief overview of my skills and experience built up over my working life. The site has been created to highlight my skills and experience without going into too much detail. A link to my CV has been provided for those that are looking for a deeper dive.

Screenshot of final website on different screens: ![Screen Sizes](https://github.com/Chains74/CI-MS1/blob/master/Documentation/MS1%20Screens.png)

---

## User Experience (UX)

The website is for potential employers to be able to quickly see what my main skills are. They will also be able to see a brief work history with pertinent details from those roles. I wanted to keep the site sleek and easy to navigate using the navigation bar at the top of each page. I have made sure that the header and footer are the same, along with the minimal colour palette and splitting of sections between the off-white and gradient colours. This is repeated across the site so the user experience doesn't change between pages.

## Features

The site consists of 4 pages. The homepage which contains a brief bio and a short list of skills and interests. A Skills page which shows my support and development skills in a little more detail, a history page which shows a timeline of the last 5 positions I've held and a contact page with location details and a dummy phone number and contact form.

### Existing Features
- Feature 1 - The nav-bar was fixed to the top of the screen to allow users to easily navigate through the site. The links to
- Feature 2 - Contact form allows people to send me message directly Does not contain a mailto action, so will refresh when the submit button is pressed..
- Feature 3 - Link to CV to allow potential employers to download a PDF copy of my CV.
- Feature 4 - Link to my LinkedIn and Github pages.

## Future Features
- Keep site updated with future work experience.
- Put site up on a custom domain.
- Add mailto action to contact form, so potential employers can contact me directly.

---

## Wireframes & Mockups

- The wireframes and mockups were created using Adobe XD. The layout of the site didn't change too much from the original design. The main design difference between the mockups and the finished site was to the history page. I did not feel it was a good idea to include more details of my job roles, as I had a link to download my CV, so having the extra details was unwarranted and would have distracted from the sleek clean design layout I was aiming for.

Basic Wireframes:

- [Desktop Wireframe](https://github.com/Chains74/CI-MS1/blob/master/Documentation/Wireframes/Desktop%20Wireframe.pdf)
- [Tablet Wireframe](https://github.com/Chains74/CI-MS1/blob/master/Documentation/Wireframes/Tablet%20Wireframe.pdf)
- [Mobile Wireframe](https://github.com/Chains74/CI-MS1/blob/master/Documentation/Wireframes/Mobile%20Wireframe.pdf)

Website Mockups:

- [Desktop Mockup](https://github.com/Chains74/CI-MS1/blob/master/Documentation/Mockups/Desktop%20Mockup.pdf)
- [Tablet Mockup](https://github.com/Chains74/CI-MS1/blob/master/Documentation/Mockups/Tablet%20Mockup.pdf)
- [Mobile Mockup](https://github.com/Chains74/CI-MS1/blob/master/Documentation/Mockups/Mobile%20Mockup.pdf)

## Fonts
- The Montez font was used for the main h1 headings on each page and the logo/brand in the left-hand side of the navigation bar.

- The Montserrat font was used for the h2 section headings.

- The Merriweather font was utilised for all the remainder of the text used on the site.

## Colour Palette

- The site was designed with a simple colour palette to keep the site sleek and avoid any clashes with the skills and software imagery.

The main body uses the following HEX code colour:

 - #F2F2F2

The gradient is made up of the following HEX code colours:

- #9A9A9A
- #DBDBDB
- #E4E4E4
- #F2F2F2

---

## Technologies

- [HTML5](https://github.com/liigalized/MS1_boredom_guide):  
HTML was used to define the basic structure of the site. Utilising standard HTML elements such as Divs, Unordered and Ordered lists and Paragraphs.

- [CSS3](https://en.wikipedia.org/wiki/CSS):  
Cascading Style Sheets were used to style the pages of the sites by using user created and existing HTML and Bootstrap classes.

- [Bootstrap 4](https://getbootstrap.com):  
Bootstrap v4.5.0 was used to help structure the rows and columns for the Bootstrap grid on the Skills page. It was also utilised for the Contact form on the contacts page, to allow the form fields to stack on top of each other at smaller screen sizes.

- [Google Fonts](https://fonts.google.com/):  
Was used for the 3 fonts used in the website for the body and headings.

- [Font Awesome](https://fontawesome.com/):  
FA was used to add icons on the Skills page for the Support and Development section headings. It was also utilised for the Github and LinkedIn social links in the footer.

- [Atom](https://atom.io/):  
I used Atom as my editing environment as I like the ability to customise it to aid my workflow through installing packages in the editor.

- [Adobe CC 2020](https://www.adobe.com/):  
I used Adobe Photoshop and Illustrator to manipulate the icons and images used on the website, and XD to create the wireframes and mockups.

- [Git](https://git-scm.com/):  
Git was used for version control and tracking of changes made to the code.

- [Github](https://github.com/):  
Github was used to host the project repository, while Github pages was utilised to publish the site.

- [Github Desktop](https://github.com/desktop/desktop):  
I used Github Desktop to push and fetch files to and from the Projects online repository.

- [W3C Markup Validation Service](https://validator.w3.org/):  
Used to validate my HTML code and alert me to any errors.

- [W3C CSS Validation Service](http://jigsaw.w3.org/css-validator/#validate_by_uri):  
Used to validate my CSS code and alert me to any errors.

---

## Testing

### Navigation Bar / Footer:

- Navigation bar is fixed to the top of the screen on all screen sizes, and all links to other pages on the site. This has been tested on desktop, laptop, tablet and mobile devices.
- The footer is located at the bottom of the screen but is not fixed, so will only show once the user has scrolled to the bottom of the page. This was done to make sure that the user could maximise the available screen estate when reading through the page.
- The social links open on new tabs with the currently used browser. Again this was tested across all devices.
- With the CV download link, this will open the PDF in a new tab on anything less than laptop screen, and on laptops and above it will give you the option to open or save the PDF locally.

### Homepage:
* On the homepage the skills are set to float either to the left or right of the skill image. I have also set a style that changes the font-size and colour of the skill on smaller screens to make it stand out a little.

### History Page:
* The goal of the testing on the history page was to make sure that the brief details of each job would not display on smaller sizes, so they just show the job title and company. On tablets in landscape the job details will reappear.

### Contact:
* On the contacts page I have tested to make sure that all fields need to be filled in before you can submit the form. This was done by adding the required option on the input elements in the code.

## Code Validation

### CSS Validation:
<p>
    <a href="http://jigsaw.w3.org/css-validator/check/referer">
        <img style="border:0;width:88px;height:31px"
            src="http://jigsaw.w3.org/css-validator/images/vcss"
            alt="Valid CSS!" />
    </a>
</p> - PASSED

### HTML validation:

- Homepage: PASSED
- Skills: PASSED
- History: PASSED
- Contact: PASSED

### Browsers tested

The site was tested on the below browsers, using the dev tools of each browser to check the responsiveness. This was achieved using the various device sizes available within each browsers tools.

- Firefox - Passed
- Chrome - Passed
- Brave - Passed
- Vivaldi - Passed
- Opera - Passed
- Safari - Passed
- Microsoft Edge - Passed

- Responsiveness was tested on an iMac, MacBook Pro, Dell laptop, iPhone, iPad and Samsung J3. Desktop/Mobile OS compatibility was tested on macOS 10.14/15, iOS 13, Android, and Windows 7.

The site URL was shared with friends and family and they were asked to test usability and to report back with any issues they may have experienced. No problems were reported back.

## Issues fixed

Issue:- Collapsed Nav-bar would not expand.  
Fix:- Problem caused by setting position property on the nav-bar class. Solution provided by Anthony O'Brien on Slack.

Issue:- Timeline content divs stretched wider than the content on desktop screen sizes.  
Fix:- used media query to set the content div's width on larger screens.

Issue:- Development skills list off centre when displayed on mobile screens.  
Fix:- Used CSS and media queries to position items centrally on smaller screens.

---

## Deployment

I uploaded the project files to Github and deployed the site using Github pages.

To upload the project to Github I used the process below:

1. Downloaded and installed the Github Desktop application. Logged into my Github account.
2. Installed the Github package into Atom, and connected to my Github account.
3. Staged the changes to the sites pages using the Atom Github package and added the Commit message.
4. Pushed the changes to the online repository using Github Desktop.

To deploy the project using Github Pages  I used the process below:

1. Logged into my GitHub account
2. Clicked on the link to the project repository.
3. Clicked on the Settings link in the project repository.
4. Scrolled down until I found the Github Pages section.
5. Selected Master from the Branch dropdown menu under Source and clicked Save.
6. After a few minutes the link for the published page appeared, which is:

    https://chains74.github.io/CI-MS1/

As I used a local IDE to create the site, all the files already exist locally on my machine. To run the code locally, it is just a case of accessing the folder containing the files and opening any of the html files from the project in the browser of my choice.

---

## Credits

### Content
- The application icons for the site where taken from the installed app packages on my machine by showing the package contents and finding the app icon. These were then resized to requirements by using Adobe Photoshop and Illustrator. The Developer icons were found on www.flaticons.com.

### Media
- The profile photo used in this site is one of my own and was converted into a transparent background png using Adobe Photoshop.

### Acknowledgements

- I received inspiration for this project from the CV project in the User Centric Front End Development module.

- I received help from Anthony O'Brien on the CI #user-centric-frontend Slack channel, when I had an issue with my collapsed Navbar not expanding. Big thanks for the help in fixing that.

- I used https://onaircode.com/html-css-horizontal-timeline-examples/ to get inspiration and a better understanding of how to code a timeline correctly by looking at the code examples to see how they were put together.

- I used Stackoverflow to find the answer to how to set the order of the links in the footer when stacked on smaller screen sizes.
