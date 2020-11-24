## georgelychock-career.com
### My User Centric Frontend Development Milestone Project

<h1 align="center">George Lychock Career Website</h1>

[View the live project here.](http://www.georgelychock-career.com/pages/test/glcareerupdate/index.html)

This is the main career website for George Lychock. It contains all the job, education, and professional development information for George Lychock. This site will replace my Bootstrap3 site that currently exists at www.georgelychock-career.com. I plan to use a hybrid of the existing content, learned modules from the CI lesson plan, and other resources I have found along the way, but all the code will be completely new and any 'borrowed or sampled' code will be documented below.

##### Possible landing page image, carried over from BS3 site:
<h1  align="center"><img src="http://www.georgelychock-career.com/images/glcareer-opener-03-750w.png"></h1>

-   ## User Experience (UX)
    Since this site will almost always be accessed by first-time users, the focus will be on a more simple, less-busy design and navigation. Very few images. Precise and succinct content, fewer words, more content flow. My old career site, based on Bootstrap3 was too word heavy. The mobile experience needs to be completely flawless and error free as I suspect that up to 50% of the traffic will be via mobile device.

-   ### User stories
    -   #### General User Experience
        1.  As a Site Visitor, I want to have a persistent navigation element/method allowing me to jump to any site content quickly.
            -  ##### Acceptance Criteria -- Duplicated in Testing below
                1.  Most detailed Content is never more than **two clicks** away from home.
                2.  Home is always **one click** away from anywhere on the site.
                3.  Nav dropdown (collapse) is *prohibited*
                4.  Either links to sub pages and/or Home should be visible on any page at any scroll point on any viewport.

        2.  As a Site Visitor, I want to have a similar experience whether desktop, tablet, or mobile, so that I can later access information in a similar manner if I change devices.
            -  ##### Acceptance Criteria -- Duplicated in Testing below
                1.  All content has to be accessible from desktop, tablet, or mobile device.
                2.  All images should have alt text
                3.  Icons should be consistent across viewports
                4.  Indentation (margins and padding) should be structurally similar across viewports
                5.  Pages and sections use the same names throughout the site ei when refering to Work History, it's not later referred to Work Experience or Job Summary etc somewhere else in the site or on site nav
                6.  All fonts are consistent for each section and element across all viewports
                7.  All documents and links to external sites should open a new tab in the browser
                8.  Any page or internal site links should never open a new browser tab

    -   #### Recruiter and HR Contact Experience
        1.  As a Recruiter, I want to easily understand what types of information about George Lychock will be available so I can determine if George has minimum requirements to be considered further. 
            -  ##### Acceptance Criteria -- Duplicated in Testing below
                1.  Upon landing at the site an immediate indication needs to be present that communicates to the user what main categories of information are available to view.
                2.  Access to the most recently published resume must be present on all pages, all viewports.
                3.  Access to George's Profile page must be present on all pages, all viewports.

    -   #### Hiring Manager Experience
        1.  As a Hiring Manager, I want to access quickly the information that shows me George is a good candidate for the position.
            -  ##### Acceptance Criteria -- Duplicated in Testing below
                1.  A link to George's most relavent published resume (one that aligns with LinkedIn, Indeed, etc.) needs to be accessible and immediately present upon entering the site.
                2.  A graphic, or other method, that indicates what skills and respective level of proficiency George has; preferrably something that can be understood within 15-20 sec.
                3.  One Click access to George's Work History
                4.  A skills summary page needs to be present
                5.  An Education and/or Professional Development page needs to be present

    -   #### Casual Visitor Experience
        1.  As a Casual/AdHoc Visitor, I want to see some cutting edge layout and responsiveness so I can learn how to enhance my future sites.
            -  ##### Acceptance Criteria -- Duplicated in Testing below
                1.  Mobile experience on Home page should not require a scroll to view entire Home page content
                2.  The Desktop Home page should offer more initial information on site content and offer a more robust nav that will not be displayed on the mobile view Home
                3.  Use at least one advanced Bootstrap component on the site.

-   ### Design
    -   #### Colour Scheme
        -   Most likely using a white main background to give a more professional look as opposed to black or dark colors. The final color scheme will have to be iterated over to the R2 release given time contraints.
    -   #### Typography
        -   Two Google fonts, Montserrat will be used for headings and titles, Raleway will be used for all running text and nav items.
    -   #### Imagery
        -   Images will be kept to a minimum, most likely just a hero image of something that corresponds to George's PD or Education. There will be an image of George on a profile page.
    -   #### Iconography
        -   Use icons in nav elements, social media elements, using Font Awesome icons.
    -   #### Profile Page
        -   The Profile page should have a different look and feel and Content Area struture than the other pages of the website; this will probably be finished in a R2 of the site.

-   ### Wireframes

    -   Desktop Wireframe - [View](https://github.com/GeorgeLychock/georgelychock-career/blob/main/_documentation/_wireframes/georgelychock-career-desk-01.pdf)

    -   Mobile Wireframe (Scrolling Home Version) - [View](https://github.com/GeorgeLychock/georgelychock-career/blob/main/_documentation/_wireframes/georgelychock-career-smart-01-scrolling-home.pdf)

    -   Mobile Wireframe (No Scrolling Home Version) - [View](https://github.com/GeorgeLychock/georgelychock-career/blob/main/_documentation/_wireframes/georgelychock-career-smart-01-no-scrolling-home.pdf)

## Requirements
-   ### Business Reqs
    -   Smartphone first design; to replicate a native app as closely as possible
    -   Re-work Smartphone UX into a desktop experience
    -   Smartphone experience should be substantially different than desktop, yet retain many of the elements and content reuse.
    -   Wireframes for both scenarios need to be created prior to dev work.
    -   Site navigation needs to be simple, no dropdowns, no nav button on smartphone view

-   ### Structure Reqs
    -   Desire to have Home landing page non-scrolling on all viewports, this might not be attainable, and it may be more desirable to have scrolling on desktop but non-scrolling on smartphone, team will iterate to finalize this requirement
    -   Three (3) screen max click path to any content on the site
    -   Resume download to be present at top on all screens, all viewports, fixed to top
    -   Persistent social media icons in footer for all screens, all viewports
    -   Projected High Level Sitemap:
        -   Home   
            -   Work History
                -   Work History Item*
            -   Skills Summary and Career Focuses
                -   Currently Working On Item*
                -   Recent Certifications Item*
                -   Skills Progress Bar Item*
            -   Portfolio and Projects
                -   Project Item*
                -   Portfolio Item*
            -   Education, Credentials, and Professional Development
                -   Edu Item*
                -   Cred Item*
                -   PD Item*
            -   Profile Page
    -   Main Page Sections:
        -   Home
            -   Download Resume Feature
            -   Hero Image
            -   Nav (to Content Area Landing Pages eg Work History)
            -   Social Media Links
        -   Secondary Pages (Content Area Landing Page)
            -   Download Resume Feature
            -   Nav (to Content Area Landing Pages eg Work History)
            -   Content TOC, Short Descriptions
            -   Social Media Links
        -   Third Pages (Content Item Page)*
            -   Download Resume Feature
            -   Nav (to Content Area Landing Pages eg Work History)
            -   Content Item, Long Description
            -   Social Media Links
        *Third Level pages may be ommited if # of content items doesn't require the extra level of structure/display

-   ### General Requirements
    -   Alt text all images
    -   Use Semantic HTML whenever possible following the MDN guide found [here.](https://developer.mozilla.org/en-US/docs/Web/HTML/Element)
    -   Limit Semantic Elements implemented to the following list:
        -   main
        -   section
        -   nav
        -   article
        -   aside
        -   header
        -   footer
        -   button
        -   address

-   ### Navigation Reqs
    -   Persistent Home or Back button
    -   Persistent banner on Smartphone viewports containing Home, resume download, and Profile buttons
    -   Menu items should have respective icons, determined by developer
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
    *   Address responsive issues with tablet viewports
    *   Add a "About Hero Image" modal or link to page ref
    *   Add a timeline graphic to the Work History page
    *   Review adding Profile and Creds section on L1 pages
    *   Apply minor column structure to desktop view for Skills and Work History pages
    *   Update profile picture

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
-   Method to connect to my github repo
-   Method to quickly get to my social media sites

Release 2
-   Updated Profile Page to site
-   Updated profile picture of George
-   Method to show what I work on outside of my main career
-   Create an About Hero Image modal



## Technologies Used

### Languages Used

-   [HTML5](https://en.wikipedia.org/wiki/HTML5)
-   [CSS3](https://en.wikipedia.org/wiki/Cascading_Style_Sheets)

### Frameworks, Libraries & Programs Used

1. [Bootstrap 4.4.1:](https://getbootstrap.com/docs/4.4/getting-started/introduction/)
    - Bootstrap was used to assist with the responsiveness and styling of the website.
2. [Google Fonts:](https://fonts.google.com/)
    - Google fonts were used to import the 'Titillium Web' font into the style.css file which is used on all pages throughout the project.
3. [Font Awesome:](https://fontawesome.com/)
    - Font Awesome was used on all pages throughout the website to add icons for aesthetic and UX purposes.
4. [jQuery:](https://jquery.com/)
    - jQuery came with Bootstrap to make the navbar responsive but was also used for the smooth scroll function in JavaScript.
5. [Git](https://git-scm.com/)
    - Git was used for version control by utilizing the Gitpod terminal to commit to Git and Push to GitHub.
6. [GitHub:](https://github.com/)
    - GitHub is used to store the projects code after being pushed from Git.
7. [Fireworks:](https://www.adobe.com/ca/products/fireworks.html)
    - Photoshop was used to create the logo, resizing images and editing photos for the website.
8. [Balsamiq:](https://balsamiq.com/)
    - Balsamiq was used to create the [wireframes](https://github.com/GeorgeLychock/georgelychock-career/blob/main/_documentation/_wireframes/) during the design process.
9. [Jira:](https://www.atlassian.com/software/jira)
    - Jira was used to track spints and work logs for all work done on the site.
10. [Confluence:](https://www.atlassian.com/software/confluence)
    - Confluence was used to document all information around scoping, structure, technologies, and releases for this project.


## Testing

The W3C Markup Validator and W3C CSS Validator Services were used to validate every page of the project to ensure there were no syntax errors in the project.

-   [W3C Markup Validator](https://validator.w3.org/nu/)
    - [Results-index](https://github.com/GeorgeLychock/georgelychock-career/blob/main/_documentation/validation/w3c-nu-html-index-screenshotfrom2020-11-18.png)
    - [Results-workhistory](https://github.com/GeorgeLychock/georgelychock-career/blob/main/_documentation/validation/w3c-nu-html-workhistory-screenshotfrom2020-11-22.png)
    - [Results-skills.html](https://github.com/GeorgeLychock/georgelychock-career/blob/main/_documentation/validation/w3c-nu-html-skills-screenshotfrom2020-11-22.png)
    - [Results-portfolio.html](https://github.com/GeorgeLychock/georgelychock-career/blob/main/_documentation/validation/w3c-nu-html-portfolio-screenshotfrom2020-11-22.png)
    - [Results-education.html](https://github.com/GeorgeLychock/georgelychock-career/blob/main/_documentation/validation/w3c-nu-html-education-screenshotfrom2020-11-23.png)
-   [W3C CSS Validator](https://jigsaw.w3.org/css-validator/#validate_by_uri+with_options) - [Results](https://github.com/GeorgeLychock/georgelychock-career/blob/main/_documentation/validation/jigsaw-css-screenshotfrom2020-11-18.png)

-   ### Testing User Stories from User Experience (UX) Section
    -   #### General User Experience
        1.  As a Site Visitor, I want to have a persistent navigation element/method allowing me to jump to any site content quickly.
            -  ##### Acceptance Criteria -- Duplicated in Testing below
                1.  Most detailed Content is never more than **two clicks** away from home.
                2.  Home is always **one click** away from anywhere on the site.
                3.  Nav dropdown (collapse) is *prohibited*
                4.  Either links to sub pages and/or Home should be visible on any page at any scroll point on any viewport.

        2.  As a Site Visitor, I want to have a similar experience whether desktop, tablet, or mobile, so that I can later access information in a similar manner if I change devices.
            -  ##### Acceptance Criteria Duplicated in Testing below
                1.  All content has to be accessible from desktop, tablet, or mobile device.
                2.  All images should have alt text
                3.  Icons should be consistent across viewports
                4.  Indentation (margins and padding) should be structurally similar across viewports
                5.  Pages and sections use the same names throughout the site ei when refering to Work History, it's not later referred to Work Experience or Job Summary etc somewhere else in the site or on site nav
                6.  All fonts are consistent for each section and element across all viewports
                7.  All documents and links to external sites should open a new tab in the browser
                8.  Any page or internal site links should never open a new browser tab

    -   #### Recruiter and HR Contact Experience
        1.  As a Recruiter, I want to easily understand what types of information about George Lychock will be available so I can determine if George has minimum requirements to be considered further. 
            -  ##### Acceptance Criteria -- Duplicated in Testing below
                1.  Upon landing at the site an immediate indication needs to be present that communicates to the user what main categories of information are available to view.
                2.  Access to the most recently published resume must be present on all pages, all viewports.
                3.  Access to George's Profile page must be present on all pages, all viewports.

    -   #### Hiring Manager Experience
        1.  As a Hiring Manager, I want to access quickly the information that shows me George is a good candidate for the position.
            -  ##### Acceptance Criteria -- Duplicated in Testing below
                1.  A link to George's most relavent published resume (one that aligns with LinkedIn, Indeed, etc.) needs to be accessible and immediately present upon entering the site.
                2.  A graphic, or other method, that indicates what skills and respective level of proficiency George has; preferrably something that can be understood within 15-20 sec.
                3.  One Click access to George's Work History
                4.  A skills summary page needs to be present
                5.  An Education and/or Professional Development page needs to be present

    -   #### Casual Visitor Experience
        1.  As a Casual/AdHoc Visitor, I want to see some cutting edge layout and responsiveness so I can learn how to enhance my future sites.
            -  ##### Acceptance Criteria -- Duplicated in Testing below
                1.  Mobile experience on Home page should not require a scroll to view entire Home page content
                2.  The Desktop Home page should offer more initial information on site content and offer a more robust nav that will not be displayed on the mobile view Home
                3.  Use at least one advanced Bootstrap component on the site.

### Further Testing

-   The Website was tested on Google Chrome, Internet Explorer, Microsoft Edge and Safari browsers.
-   The website was viewed on a variety of devices such as Desktop, Laptop, iPhone7, iPhone 8 & iPhoneX.
-   A large amount of testing was done to ensure that all pages were linking correctly.
-   Friends and family members were asked to review the site and documentation to point out any bugs and/or user experience issues.

### Known Bugs
-   On tablet viewports the My Profile Section overflows on the Credentials Section on Home page.
-   On mobile view social nav icons do not center properly

## Deployment

### Project Folder Structure
-   All secondary html pages are located in the <pages/> folder.
-   All images are located in the <images/> folder
-   Any document content (eg resume pdf) is located in the <content/> folder
-   The <css/> folder is located directly off the root folder

### Hosting www.georgelychock-caree.com

The project was deployed to my hosting service:

1. URL: http://www.georgelychock-career.com/pages/test/glcareerupdate/pages/workhistory.html
2. All files were uploaded via FileZilla FTP.

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