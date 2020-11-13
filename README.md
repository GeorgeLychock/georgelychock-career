## georgelychock-career.com
### My User Centric Frontend Development Milestone Project

<h1 align="center">George Lychock Career Website</h1>

[View the live project here.](http://www.georgelychock-career.com/pages/test/glcareerupdate/index.html)

This is the main career website for George Lychock. It contains all the job, education, and professional development information for George Lychock. This site will replace my Bootstrap3 site that currently exists at www.georgelychock-career.com. I plan to use a hybrid of the existing content, learned modules from the CI lesson plan, and other resources I have found along the way, but all the code will be completely new and any 'borrowed' code will be documented below.

##### Possible landing page image, carried over from BS3 site:
<h1  align="center"><img src="http://www.georgelychock-career.com/images/glcareer-opener-03-750w.png"></h1>

-   ## User Experience (UX)
    Since this site will almost always be accessed by first-time users, the focus will be on a more simple, less-busy design and navigation. Very few images. Precise and succinct content, fewer words, more content flow. My old career site, based on Bootstrap3 was too word heavy. The mobile experience needs to be completely flawless and error free as I suspect that up to 25% of the traffic will be via mobile device.

-   ### User stories
    -   #### General User Experience
        1.  As a Site Visitor, I want to have a persistent navigation element/method allowing me to jump to any site content quickly.
            -  ##### Acceptance Criteria -- Duplicated in Testing below
                1.  Main Content should never be more than **two clicks** away from home.
                2.  Home should never be more than **one click** away from anywhere on the site.
                3.  Nav dropdown is required, giving access to any main content page (career objectives, education, skills, work history, pd etc.) from anywhere in the site.

        2.  As a Site Visitor, I want to be able to see a similar experience whether desktop, tablet, or mobile, so that I can later access information in a similar manner if I change devices.
            -  ##### Acceptance Criteria Duplicated in Testing below
                1.  All content, with exception of imagery, has to be accessible from desktop, tablet, or mobile device.


    -   #### Recruiter and HR Contact Experience
        1.  As a Recruiter, I want to easily understand what types of information about George Lychock will be available so I can determine if George has minimum requirements to be considered further. 
            -  ##### Acceptance Criteria -- Duplicated in Testing below
                1.  Upon landing at the site an immediate indication needs to be present that communicates to the user what main categories of information are available to view.
                2.  Access to the most recently published resume.
                3.  Access to any other relevant online resources showing George's career history and path

    -   #### Hiring Manager Experience
        1.  As a Hiring Manager, I want to access quickly the information that shows me George is a good candidate for the position.
            -  ##### Acceptance Criteria -- Duplicated in Testing below
                1.  A link to George's most relavent published resume (one that aligns with LinkedIn, Indeed, etc.) needs to be accessible and immediately present upon entering the site.
                2.  A graphic, or other method, that indicates what skills and respective level of proficiency George has; preferrably something that can be understood within 15-20 sec.

    -   #### Casual Visitor Experience
        1.  As a Casual/AdHoc Visitor, I want to see some cutting edge layout and responsiveness so I can learn how to enhance my future sites.
            -  ##### Acceptance Criteria -- Duplicated in Testing below
                1.  TK
                2.  TK

-   ### Design
    -   #### Colour Scheme
        -   Most likely using a white main background to give a more professional look as opposed to black or dark colors.
    -   #### Typography
        -   Two Google fonts, to be determined at design phase.
    -   #### Imagery
        -   Images will be kept to a minimum, most likely just a hero image of something that corresponds to George's PD or Education. There will be an image of George on a profile page.
    -   #### Iconography
        -   Use icons in nav elements, social media elements

-   ### Wireframes

    -   Desktop Wireframe - [View](https://github.com/GeorgeLychock/georgelychock-career/blob/main/_documentation/_wireframes/georgelychock-career-desk-01.pdf)

    -   Mobile Wireframe (Scrolling Home Version) - [View](https://github.com/GeorgeLychock/georgelychock-career/blob/main/_documentation/_wireframes/georgelychock-career-smart-01-scrolling-home.pdf)

    -   Mobile Wireframe (No Scrolling Home Version) - [View](https://github.com/GeorgeLychock/georgelychock-career/blob/main/_documentation/_wireframes/georgelychock-career-smart-01-no-scrolling-home.pdf)

## Requirements
-   ### Business Reqs
        -   Smartphone first design; to replicate a native app as closely as possible
        -   Re-work Smartphone UX into a desktop experience
        -   Smartphone experience should be substantially different than desktop, yet retain many of the elements and content reuse.
        -   wireframes for both scenarios need to be approved prior to prod dev (dev can spend up to 5% of BP budget prior to approval)
        -   Site navigation needs to be simple, no dropdowns, no nav button on smartphone view
-   ### Structure Reqs
    -   Desire to have Home landing page non-scrolling on all viewports, this might not be attainable, and it may be more desirable to have scrolling on desktop but non-scrolling on smartphone, team will iterate to finalize this requirement
    -   Three (3) screen max click path to any content on the site
    -   Resume download to be present at top on all screens, all viewports, fixed to top
    -   Persistent social media icons in footer for all screens, all viewports
    -   High Level Sitemap:
        -   Home   
            -   Work History
                -   Work History Item
            -   Skills Summary and Career Focuses
                -   Currently Working On Item
                -   Recent Certifications Item
                -   Skills Progress Bar Item
            -   Portfolio and Projects
                -   Project Item
                -   Portfolio Item
            -   Education, Credentials, and Professional Development
                -   Edu Item
                -   Cred Item
                -   PD Item
            -   Profile Page
    -   Main Page Sections:
        -   Home
            -   Download Resume Feature
            -   Jumbotron
            -   Nav (to Content Area Landing Pages eg Work History)
            -   Social Media Links
        -   Secondary Pages (Content Area Landing Page)
            -   Download Resume Feature
            -   Nav (to Content Area Landing Pages eg Work History)
            -   Content TOC, Short Descriptions
            -   Social Media Links
        -   Third Pages (Content Item Page)
            -   Download Resume Feature
            -   Nav (to Content Area Landing Pages eg Work History)
            -   Content Item, Long Description
            -   Social Media Links
-   ### General Requirements
        -   Alt text all links and images
-   ### Navigation Reqs
    -   Persistent Back button
    -   Persistent nav header on Smartphone viewports
    -   Menu items should have respective icons
    -   No collaspable nav button on any viewports
-   ### Social Media Section
    -   Social media links will have circular backgrounds, with two sizes and colors, distinquishing more important links for the less important links
-   ### Home
    -   Use a hero image that is personally connected to George
    -   Mobile experience will be a single screen with nav icons and no scrolling to add'l content
    -   Desktop and tablet expiences will have a scrolling Home page with a hero image, nav icon section, social media links section, and a cerifications section
    -   Download button and connected text should float right, md and higher viewports
    -   A My Profile link should float right with the Resume link on the smartphone top banner area


*   ### Future Reqs
    *   *Capture furture release reqs here*
    *   Address responsibility issues with tablet viewports
    *   Add a "About Hero Image" modal or link to page ref




## Approved Features and Initial Release Strategy

Release 1
-   Responsive on all device sizes
-   Reveal a pitch, a hero image, contact information
-   Method to show skill set
-   Method to download resume
-   Design and Apply structure
-   Define Look and Feel
-   Apply Look and Feel
-   Method to view my work history
-   Method to see what I have been working on in Professional Development
-   Method to show education history
-   Method to show what I work on outside of my main career
-   Method to connect to my github repo
-   Method to quickly get to my social media sites

Release 2
-   Add Profile Page to site
-   Create an About Hero Image modal



## Technologies Used

### Languages Used

-   [HTML5](https://en.wikipedia.org/wiki/HTML5)
-   [CSS3](https://en.wikipedia.org/wiki/Cascading_Style_Sheets)

### Frameworks, Libraries & Programs Used

1. [Bootstrap 4.4.1:](https://getbootstrap.com/docs/4.4/getting-started/introduction/)
    - Bootstrap was used to assist with the responsiveness and styling of the website.
2. [Hover.css:](https://ianlunn.github.io/Hover/)
    - Hover.css was used on the Social Media icons in the footer to add the float transition while being hovered over.
2. [Google Fonts:](https://fonts.google.com/)
    - Google fonts were used to import the 'Titillium Web' font into the style.css file which is used on all pages throughout the project.
2. [Font Awesome:](https://fontawesome.com/)
    - Font Awesome was used on all pages throughout the website to add icons for aesthetic and UX purposes.
1. [jQuery:](https://jquery.com/)
    - jQuery came with Bootstrap to make the navbar responsive but was also used for the smooth scroll function in JavaScript.
3. [Git](https://git-scm.com/)
    - Git was used for version control by utilizing the Gitpod terminal to commit to Git and Push to GitHub.
3. [GitHub:](https://github.com/)
    - GitHub is used to store the projects code after being pushed from Git.
3. [Photoshop:](https://www.adobe.com/ie/products/photoshop.html)
    - Photoshop was used to create the logo, resizing images and editing photos for the website.
3. [Balsamiq:](https://balsamiq.com/)
    - Balsamiq was used to create the [wireframes](https://github.com/GeorgeLychock/georgelychock-career/blob/main/_documentation/_wireframes/) during the design process.
3. [Jira:](https://www.atlassian.com/software/jira)
    - Jira was used to track spints and work logs for all work done on the site.
3. [Confluence:](https://www.atlassian.com/software/confluence)
    - Confluence was used to document all information around scoping, structure, technologies, and releases for this project.


## Testing

The W3C Markup Validator and W3C CSS Validator Services were used to validate every page of the project to ensure there were no syntax errors in the project.

-   [W3C Markup Validator](https://jigsaw.w3.org/css-validator/#validate_by_input) - [Results](https://github.com/)
-   [W3C CSS Validator](https://jigsaw.w3.org/css-validator/#validate_by_input) - [Results](https://github.com/)

### Testing User Stories from User Experience (UX) Section

-   #### First Time Visitor Goals

    1. As a First Time Visitor, I want to easily understand the main purpose of the site and learn more about the organisation.

        1. Upon entering the site, users are automatically greeted with a clean and easily readable navigation bar to go to the page of their choice. Underneath there is a Hero Image with Text and a "Learn More" Call to action button.
        2. The main points are made immediately with the hero image
        3. The user has two options, click the call to action buttons or scroll down, both of which will lead to the same place, to learn more about the organisation.

    2. As a First Time Visitor, I want to be able to easily be able to navigate throughout the site to find content.

        1. The site has been designed to be fluid and never to entrap the user. At the top of each page there is a clean navigation bar, each link describes what the page they will end up at clearly.
        2. At the bottom of the first 3 pages there is a redirection call to action to ensure the user always has somewhere to go and doesn't feel trapped as they get to the bottom of the page.
        3. On the Contact Us Page, after a form response is submitted, the page refreshes and the user is brought to the top of the page where the navigation bar is.

    3. As a First Time Visitor, I want to look for testimonials to understand what their users think of them and see if they are trusted. I also want to locate their social media links to see their following on social media to determine how trusted and known they are.
        1. Once the new visitor has read the About Us and What We Do text, they will notice the Why We are Loved So Much section.
        2. The user can also scroll to the bottom of any page on the site to locate social media links in the footer.
        3. At the bottom of the Contact Us page, the user is told underneath the form, that alternatively they can contact the organisation on social media which highlights the links to them.

-   #### Returning Visitor Goals

    1. As a Returning Visitor, I want to find the new programming challenges or hackathons.

        1. These are clearly shown in the banner message.
        2. They will be directed to a page with another hero image and call to action.

    2. As a Returning Visitor, I want to find the best way to get in contact with the organisation with any questions I may have.

        1. The navigation bar clearly highlights the "Contact Us" Page.
        2. Here they can fill out the form on the page or are told that alternatively they can message the organisation on social media.
        3. The footer contains links to the organisations Facebook, Twitter and Instagram page as well as the organization's email.
        4. Whichever link they click, it will be open up in a new tab to ensure the user can easily get back to the website.
        5. The email button is set up to automatically open up your email app and autofill there email address in the "To" section.

    3. As a Returning Visitor, I want to find the Facebook Group link so that I can join and interact with others in the community.
        1. The Facebook Page can be found at the footer of every page and will open a new tab for the user and more information can be found on the Facebook page.
        2. Alternatively, the user can scroll to the bottom of the Home page to find the Facebook Group redirect card and can easily join by clicking the "Join Now!" button which like any external link, will open in a new tab to ensure they can get back to the website easily.
        3. If the user is on the "Our Favourites" page they will also be greeted with a call to action button to invite the user to the Facebook group. The user is incentivized as they are told there is a weekly favourite product posted in the group.

-   #### Frequent User Goals

    1. As a Frequent User, I want to check to see if there are any newly added challenges or hackathons.

        1. The user would already be comfortable with the website layout and can easily click the banner message.

    2. As a Frequent User, I want to check to see if there are any new blog posts.

        1. The user would already be comfortable with the website layout and can easily click the blog link

    3. As a Frequent User, I want to sign up to the Newsletter so that I am emailed any major updates and/or changes to the website or organisation.
        1. At the bottom of every page their is a footer which content is consistent throughout all pages.
        2. To the right hand side of the footer the user can see "Subscribe to our Newsletter" and are prompted to Enter their email address.
        3. There is a "Submit" button to the right hand side of the input field which is located close to the field and can easily be distinguished.

### Further Testing

-   The Website was tested on Google Chrome, Internet Explorer, Microsoft Edge and Safari browsers.
-   The website was viewed on a variety of devices such as Desktop, Laptop, iPhone7, iPhone 8 & iPhoneX.
-   A large amount of testing was done to ensure that all pages were linking correctly.
-   Friends and family members were asked to review the site and documentation to point out any bugs and/or user experience issues.

### Known Bugs

-   On some mobile devices the Hero Image pushes the size of screen out more than any of the other content on the page.
    -   A white gap can be seen to the right of the footer and navigation bar as a result.
-   On Microsoft Edge and Internet Explorer Browsers, all links in Navbar are pushed upwards when hovering over them.

## Deployment

### GitHub Pages

The project was deployed to GitHub Pages using the following steps...

1. Log in to GitHub and locate the [GitHub Repository](https://github.com/)
2. At the top of the Repository (not top of page), locate the "Settings" Button on the menu.
    - Alternatively Click [Here](https://raw.githubusercontent.com/) for a GIF demonstrating the process starting from Step 2.
3. Scroll down the Settings page until you locate the "GitHub Pages" Section.
4. Under "Source", click the dropdown called "None" and select "Master Branch".
5. The page will automatically refresh.
6. Scroll back down through the page to locate the now published site [link](https://github.com) in the "GitHub Pages" section.

### Forking the GitHub Repository

By forking the GitHub Repository we make a copy of the original repository on our GitHub account to view and/or make changes without affecting the original repository by using the following steps...

1. Log in to GitHub and locate the [GitHub Repository](https://github.com/)
2. At the top of the Repository (not top of page) just above the "Settings" Button on the menu, locate the "Fork" Button.
3. You should now have a copy of the original repository in your GitHub account.

### Making a Local Clone

1. Log in to GitHub and locate the [GitHub Repository](https://github.com/)
2. Under the repository name, click "Clone or download".
3. To clone the repository using HTTPS, under "Clone with HTTPS", copy the link.
4. Open Git Bash
5. Change the current working directory to the location where you want the cloned directory to be made.
6. Type `git clone`, and then paste the URL you copied in Step 3.

```
$ git clone https://github.com/YOUR-USERNAME/YOUR-REPOSITORY
```

7. Press Enter. Your local clone will be created.

```
$ git clone https://github.com/YOUR-USERNAME/YOUR-REPOSITORY
> Cloning into `CI-Clone`...
> remote: Counting objects: 10, done.
> remote: Compressing objects: 100% (8/8), done.
> remove: Total 10 (delta 1), reused 10 (delta 1)
> Unpacking objects: 100% (10/10), done.
```

Click [Here](https://help.github.com/en/github/creating-cloning-and-archiving-repositories/cloning-a-repository#cloning-a-repository-to-github-desktop) to retrieve pictures for some of the buttons and more detailed explanations of the above process.

## Credits

### Code

-   The download button code came from Code Institute, User Centric Module, Full Stack Software Deveveloper Program:
    Find code use indicated by "CODE REUSE - Download Button User Centric Module, Code Institute"
        `<div class="d-none d-md-block">`
            `<p class="navbar-text my-auto mr-2"><i>Download Most Recent Published Resume</i></p>`
            `<a href="/login" class="btn btn--cta-nav btn--red">Download Resume</a>`
        `</div>`

-   The skills progress bar code on the Skill Page came from Code Institute, User Centric Module, Full Stack Software Deveveloper Program:
    Find code use indicated by "CODE REUSE - Skills Progress Bar User Centric Module, Code Institute"
        `<div class="row progress-section">`
           `<div class="col">`
                `<div class="progress">`
                   ` <div class="progress-bar" role="progressbar" aria-valuenow="60" aria-valuemin="0" aria-valuemax="100" style="width: 90%;">`
                       ` <span class="sr-only">90% complete</span>.......`
                   
-   [Bootstrap4](https://getbootstrap.com/docs/4.4/getting-started/introduction/): Bootstrap Library used throughout the project mainly to make site responsive using the Bootstrap Grid System.

-   [MDN Web Docs](https://developer.mozilla.org/) : For Pattern Validation code. Code was modified to better fit my needs and to match an Irish phone number layout to ensure correct validation. Tutorial Found [Here](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/input/tel#Pattern_validation)

### Content

-   All content was written by the developer.

-   Psychological properties of colours text in the README.md was found [here](http://www.colour-affects.co.uk/psychological-properties-of-colours)

### Media

-   All Images were created by the developer.

### Acknowledgements