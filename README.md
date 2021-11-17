# Personal Portfolio
I've created a website to display my portfolio as a front end developer. 

The ultimate objective of this website is to acquire front end development jobs, either from a prospective employer or someone looking to hire a freelancer. This is achieved by giving the user sufficient information to understand my skillset and assess if I'm qualified to carry out the work required.

Users can read about my skillset and experience whilst also browsing previous projects I've worked on. I've made it possible to contact me by adding a contact form and clearly signposting to this form at various points throughout the website.

## UX
There are two main users this website is designed for, employers looking to hire full time or for freelance work. See below for details on each page's purpose and how it assists each user.

### Features

**All pages**
- Navigation: I've created two styles, one for desktop and mobile. 
    - Desktop: The nav bar constantly displays each page with the active page highlighted so that the user can easily see the site structure and where they are on the website.
    - Mobile: The nav bar collapses to a burger nav for smaller devices. This is to maintain a clean and simplified layout on devices with a limited screensize.
- Footer: 
    - Quick links have been added to the footer to allow for easy navigation. 
    - A simplified contact form has been added to the footer. The main purpose of every page won't be to drive a contact form submission, so I added this to the footer across all pages as a subtle call to action without distracting from the main purpose of the page.
    - Social links have been added with the target attribute to ensure the user keeps this website open in their browser.
- Flex design layout:
    - Most pages consist of two main sections at this point in time. Therefore I've gone for a 2 column flex design on desktop to utlise the space on a wider landscape screen. This layout collapses to a single column on smaller devices due to limited screen size.

**Homepage**

It isn't clear what the user is looking to achieve on the homepage so I've aimed to subtly guide the user in the right direction without confusing the design.
- Header section: This is a brief summary about me and the purpose of the site. The main CTA is to contact me so I've added contact button to stand out. A portfolio button will appear on small devices to anchor the user to that section of the page incase it get's lost below the fold.
- Portfolio: To reduce the amount of text on screen I've added an on hover effect to each project to reveal more information. This was a user can reveal more information (e.g. project title) without having a cluttered experience. An mouse over effect has also been added to indicate the image is clickable.

**About**

- Skills: To make the page easier to scan I've added labels to summaries each of my key skills. These labels have been styled differently to clickable buttons to avoid confusion.
- Social section: To make website more perosnable I've added a section for a profile picture and links to my social media accounts.

**Contact**

This page has been reduced to a single column layout with just a contact form as to not distract from the main CTA.

I've made the personal detail fields compulsory as I'll need these to reply to any enquiries. I've left the message field as optional so that the user can chose to submit a quick enquiry or leave more details about their request.


## Features left to add

I have yet to learn javascript so there are a few features I'd like to add at a later point which require javascript:
- Content: As this is the first project I don't have content to populate the descriptions and portfolio yet. This will be populated post completing the course when I finalise my portfolio.
- Carousel: Over time I'll have more projects to include in the portfolio section. To avoid the page becoming too cluttered I'd include a clickable carousel which the user can scroll through.
- Contact form pop up: Rather than taking the user away from other pages to navigate to the form on the contact page, I'd like to serve a pop up form when they click a contact button from another page.
- Post form submission: I'd like to serve the user with a thank you message after form submissions and to signpost to another section of the site.

## Technologies Used
- HTML5
- CSS3
- Google Fonts
- Git
- Github

## Testing

- Browser testing: I opened my website in multiple browsers such as Chrome, Firefox and Microsoft Edge to test all features.
- Responsiveness: In addition to constantly using developer tools to adjust my desktop screen size, I opened my site on mobile and tablet devices to test responsiveness on smaller screen sizes.
- Validators: I ran all documents through W3C's validator to check for errors.

### Validators

- https://validator.w3.org/ to validate html files
- https://jigsaw.w3.org/css-validator/ to validate css files

## Deployment

The version control system I used was git. I regularly commited my repository to Github and deployed my website to Github pages.

1. After setting up my local repository I initialised git using the command `git init`.
2. After making any significant changes to my local repo I added my files to the staging area using `git add .`.
3. Following this I using the command `git commit -m "..."` to commit my work with a message.
4. To keep the remote repo up to date I pushed any updates live using the command `git push origin master`.

## How to clone a local repo

Follow the below steps to get a local copy of this repo:

1. Navigate to my repo https://github.com/LeeCharltonH/personal-portfolio
2. Click on the 'Code' button and select Download ZIP from the drop down options.
3. Go to your downloads and unzip the folder to open my website locally.

## GitHub Pages

https://leecharltonh.github.io/personal-portfolio/

## References

- Google Fonts https://fonts.google.com/ 
- W3C tutorial https://www.w3schools.com/howto/howto_css_image_overlay.asp - Used to create image overlay effect in portfolio section.
- Copepen.io https://codepen.io/erikterwan/pen/EVzeRP - Used to create burger nav for mobile devices.
- CSS Scan https://getcssscan.com/css-box-shadow-examples - Used to create box shadow styling in footer.
- CSS Scan https://getcssscan.com/css-buttons-examples - Design inspiration for buttons.
- Formspree https://formspree.io/ - API used for form submissions.







