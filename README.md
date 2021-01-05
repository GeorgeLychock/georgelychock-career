## georgelychock-career.com
### My User Centric Frontend Development Milestone Project

<h1 align="center">George Lychock Career Website</h1>

[View the live project here.](https://georgelychock.github.io/georgelychock-career/)

This is the main career website for George Lychock. It contains all the job, education, and professional development information for George Lychock. This site replaces my Bootstrap3 site that currently exists at www.georgelychock-career.com. I used a hybrid of the existing content, learned modules from the CI lesson plan, and other resources I have found along the way, but all the code is completely new and any 'borrowed or sampled' code is documented below and in html files.

-   ## User Experience (UX)
    Since this site will almost always be accessed by first-time users, the focus is on a more simple, less-busy design and navigation. Very few images. Precise and succinct content, fewer words, and more content flow. My old career site, based on Bootstrap3 was too word heavy. The mobile experience needs to be completely flawless and error free as I suspect that up to 50% of the traffic will be via mobile device.

-   ### User stories
    -   #### General User Experience
        -   **Story 1** As a Site Visitor, I want to have a persistent navigation element/method allowing me to jump to any site content quickly.
            -  ##### Acceptance Criteria -- Duplicated in Testing below
                1.  The most detailed Content is never more than **two clicks** away from home.
                2.  Home is always **one click** away from anywhere on the site.
                3.  Nav dropdown (collapse) is *prohibited*
                4.  Either links to sub pages and/or Home should be visible on any page at any scroll point on any viewport.

        -   **Story 2** As a Site Visitor, I want to have a similar experience whether desktop, tablet, or mobile, so that I can later access information in a similar manner if I change devices.
            -  ##### Acceptance Criteria -- Duplicated in Testing below
                1.  All content has to be accessible from desktop, tablet, or mobile device.
                2.  All images should have alt text
                3.  Icons should be consistent across viewports
                4.  Indentation (margins and padding) should be structurally similar across viewports
                5.  Pages and sections use the same names throughout the site ie when referring to Work History, it's not later referred to Work Experience or Job Summary etc somewhere else in the site or on site nav
                6.  All fonts are consistent for each section and element across all viewports
                7.  All documents and links to external sites should open a new tab in the browser
                8.  Any page or internal site links should never open a new browser tab

    -   #### Recruiter and HR Contact Experience
        -   **Story 3** As a Recruiter, I want to easily understand what types of information about George Lychock will be available so I can determine if George has minimum requirements to be considered further. 
            -  ##### Acceptance Criteria -- Duplicated in Testing below
                1.  Upon landing at the site an immediate indication needs to be present that communicates to the user what main categories of information are available to view.
                2.  Access to the most recently published resume must be present on all pages, all viewports.
                3.  Access to George's Profile page must be present on all pages, all viewports.

    -   #### Hiring Manager Experience
        -   **Story 4** As a Hiring Manager, I want to quickly access more detailed information that shows me George is a good candidate for the position.
            -  ##### Acceptance Criteria -- Duplicated in Testing below
                1.  A link to George's most relavent published resume (one that aligns with LinkedIn, Indeed, etc.) needs to be accessible and immediately present upon entering the site.
                2.  A graphic, or other method, that indicates what skills and respective level of proficiency George has; preferrably something that can be understood within 15-20 sec.
                3.  One Click access to George's Work History
                4.  A Skills summary page needs to be present
                5.  An Education and/or Professional Development page needs to be present

    -   #### Casual Visitor Experience
        -   **Story 5** As a Casual/AdHoc Visitor, I want to experience what is presently considered a basic, but effective and pleasing layout and responsiveness so I can learn by example and enhance my skills.
            -  ##### Acceptance Criteria -- Duplicated in Testing below
                1.  Mobile experience on Home page should not require a scroll to view entire Home page content (portrait view)
                2.  The Desktop Home page should offer more initial information on site content and offer a more robust nav that will not be displayed on the mobile view Home
                3.  Use at least one advanced Bootstrap components on the site.

-   ### Design
    -   #### Colour Scheme
        -   The color scheme is dictated by the hero image color profile. The image is an original photo taken by myself at a machine shop class in 2018. The final color scheme will have to be iterated over to the R2 release given time contraints. The desire is to ultimately have a brighter/whiter color scheme.
    -   #### Typography
        -   Two Google fonts, Montserrat is used for headings and titles, Raleway is used for all running text and nav items.
    -   #### Imagery
        -   Images are kept to a minimum. A hero image that corresponds to my PD/Education is used. There is an image of me on a profile page/section.
    -   #### Iconography
        -   Icons are used in nav elements, social media elements, using Font Awesome icons.
    -   #### Profile Page
        -   The Profile page has a different look and feel and Content Area struture than the other pages of the website; this will probably be upgraded in a R2 of the site.

-   ### Project Folder Structure
    -   All secondary html pages are located in the pages/ folder.
    -   All images are located in the images/ folder
    -   Any document content (eg resume pdf) is located in the content/ folder
    -   The css/ folder is located directly off the root folder

-   ### Wireframes

    -   Desktop and Tablet Wireframe - [View](https://github.com/GeorgeLychock/georgelychock-career/blob/main/_documentation/_wireframes/georgelychock-career-desk-01.pdf)

    -   Mobile Wireframe (No Scrolling Home Version) - [View](https://github.com/GeorgeLychock/georgelychock-career/blob/main/_documentation/_wireframes/georgelychock-career-smart-01-no-scrolling-home.pdf)

## Requirements
-   ### Business Reqs
    -   Smartphone first design; to replicate a native app as closely as possible
    -   Re-work Smartphone UX into a desktop experience
    -   Smartphone experience should be substantially different than desktop, yet retain many of the elements and content reuse.
    -   Wireframes for both scenarios need to be created prior to dev work.
    -   Site navigation needs to be simple, no dropdowns, no nav button on smartphone view

-   ### Structure Reqs
    -   Desire to have Home landing page non-scrolling on all viewports, this might not be attainable, and it may be more desirable to have scrolling on desktop but non-scrolling on smartphone, I will iterate to finalize this requirement
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
    -   Mobile landing page experience will be a single screen with nav icons and no scrolling to add'l content
    -   Desktop and tablet experiences will have a scrolling Home page with a hero image, nav icon section, social media links section, profile section, and a cerifications section
    -   Download button and connected text should float right, md and higher viewports
    -   A My Profile link should float right with the Resume link on the smartphone top banner area

*   ### Future Reqs
    *   *Capture furture release reqs here*
    *   Add a "About Hero Image" modal or link to page ref
    *   Add a timeline graphic to the Work History page
    *   Review adding Profile and Creds section on L1 pages
    *   Apply minor column structure to desktop view for Skills and Work History pages
    *   Update profile picture
    *   Add a Soft Skills progress bar section to Skills page

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
    - Google fonts were used to import the 'Montserrat' and 'Raleway' fonts into the style.css file which is used on all pages throughout the project.
3. [Font Awesome:](https://fontawesome.com/)
    - Font Awesome was used on all pages throughout the website to add icons to nav items.
4. [jQuery:](https://jquery.com/)
    - jQuery came with Bootstrap.
5. [Git](https://git-scm.com/)
    - Git was used for version control by utilizing Visual Studio on my Linux laptop to commit to Git and Push to GitHub.
6. [GitHub:](https://github.com/)
    - GitHub is used to store the projects code after being pushed from Git.
7. [Fireworks:](https://www.adobe.com/ca/products/fireworks.html)
    - Fireworks was used to create and size the images for the website.
8. [Balsamiq:](https://balsamiq.com/)
    - Balsamiq was used to create the [wireframes](https://github.com/GeorgeLychock/georgelychock-career/blob/main/_documentation/_wireframes/) during the design process.
9. [Jira:](https://www.atlassian.com/software/jira)
    - Jira was used to track spints and work logs for all work done on the site.


## Testing

The W3C Markup Validator and W3C CSS Validator Services were used to validate every page of the project to ensure there were no syntax errors in the project.

-   [W3C Markup Validator (Nu)](https://validator.w3.org/nu/)
    - [Results-index.html](https://github.com/GeorgeLychock/georgelychock-career/blob/main/_documentation/validation/w3c-nu-html-index-screenshotfrom2021-01-05.png) ERROR See Known Bugs Below
    - [Results-workhistory.html](https://github.com/GeorgeLychock/georgelychock-career/blob/main/_documentation/validation/w3c-nu-html-workhistory-screenshotfrom2021-01-04.png) NO ERRORS
    - [Results-skills.html](https://github.com/GeorgeLychock/georgelychock-career/blob/main/_documentation/validation/w3c-nu-html-skills-screenshotfrom2021-01-04.png) NO ERRORS
    - [Results-portfolio.html](https://github.com/GeorgeLychock/georgelychock-career/blob/main/_documentation/validation/w3c-nu-html-portfolio-screenshotfrom2021-01-05.png) ERROR See Known Bugs Below
    - [Results-education.html](https://github.com/GeorgeLychock/georgelychock-career/blob/main/_documentation/validation/w3c-nu-html-education-screenshotfrom2021-01-05.png) ERROR See Known Bugs Below
    - [Results-profile.html](https://github.com/GeorgeLychock/georgelychock-career/blob/main/_documentation/validation/w3c-nu-html-profile-screenshotfrom2021-01-05.png) ERROR See Known Bugs Below
-   [W3C CSS Validator (Jigsaw)](https://jigsaw.w3.org/css-validator/#validate_by_uri+with_options) - [Results](https://github.com/GeorgeLychock/georgelychock-career/blob/main/_documentation/validation/jigsaw-css-screenshotfrom2021-01-04.png)
-   [Lighthouse](https://jigsaw.w3.org/css-validator/#validate_by_uri+with_options)
    - [Results: Desktop Report - Home (index)](https://github.com/GeorgeLychock/georgelychock-career/blob/main/_documentation/validation/gl-career-lighthouse-desktop-index.jpg)
    - [Results: Mobile Report - Home (index)](https://github.com/GeorgeLychock/georgelychock-career/blob/main/_documentation/validation/gl-career-lighthouse-mobile-index.jpg)

-   ### Testing User Stories from User Experience (UX) Section
    -   #### General User Experience
        -   **Story 1** As a Site Visitor, I want to have a persistent navigation element/method allowing me to jump to any site content quickly.
            -  ##### Acceptance Criteria -- Duplicated in Testing below
                1.  The most detailed Content is never more than **two clicks** away from home.
                2.  Home is always **one click** away from anywhere on the site.
                3.  Nav dropdown (collapse) is *prohibited*
                4.  Either links to sub pages and/or Home should be visible on any page at any scroll point on any viewport.
            -   ##### Results
                -   (1 and 2) PASS Since there is only only sub level of pages, user is never more than 1 click from home or one click from most detailed information available.
                -   (3) PASS No nav icon nor dropdown exists'
                -   (4) PASS Every sub page has at least the Home icon visible at all times, all ports. [Screenshot](https://github.com/GeorgeLychock/georgelychock-career/blob/main/_documentation/testing/screenshots/userst-1_4-screenshotfrom2020-11-23.png)

        -   **Story 2** As a Site Visitor, I want to have a similar experience whether desktop, tablet, or mobile, so that I can later access information in a similar manner if I change devices.
            -  ##### Acceptance Criteria Duplicated in Testing below
                1.  All content has to be accessible from desktop, tablet, or mobile device.
                2.  All images should have alt text
                3.  Icons should be consistent across viewports
                4.  Indentation (margins and padding) should be structurally similar across viewports
                5.  Pages and sections use the same names throughout the site ei when refering to Work History, it's not later referred to Work Experience or Job Summary etc somewhere else in the site or on site nav
                6.  All fonts are consistent for each section and element across all viewports
                7.  All documents and links to external sites should open a new tab in the browser
                8.  Any page or internal site links should never open a new browser tab
            -   ##### Results
                -   (1) PASS All site content is accessible from any viewport, although path to content may differ depeding on device tested.
                -   (2) PASS See Nu validation above.
                -   (3) PASS The same font awesome icons are used across all pages.
                -   (4, 5, 6) PASS All nav, headers, and content areas align from left and top consitantly. Names are consistent. Fonts are consistent.
                -   (7, 8) PASS All links open correctly.

    -   #### Recruiter and HR Contact Experience
        -   **Story 3** As a Recruiter, I want to easily understand what types of information about George Lychock will be available so I can determine if George has minimum requirements to be considered further. 
            -  ##### Acceptance Criteria -- Duplicated in Testing below
                1.  Upon landing at the site an immediate indication needs to be present that communicates to the user what main categories of information are available to view.
                2.  Access to the most recently published resume must be present on all pages, all viewports.
                3.  Access to George's Profile page must be present on all pages, all viewports.
                -   ##### Results
                -   (1, 2, 3) PASS All conditions met; links were verified on previous story.
                -   2 and 3 validation can be seen here [Screenshot](https://github.com/GeorgeLychock/georgelychock-career/blob/main/_documentation/testing/screenshots/userstory-3_2-3-screenshotfrom2020-12-30.jpg)

    -   #### Hiring Manager Experience
        -   **Story 4** As a Hiring Manager, I want to access quickly the information that shows me George is a good candidate for the position.
            -  ##### Acceptance Criteria -- Duplicated in Testing below
                1.  A link to George's most relavent published resume (one that aligns with LinkedIn, Indeed, etc.) needs to be accessible and immediately present upon entering the site.
                2.  A graphic, or other method, that indicates what skills and respective level of proficiency George has; preferrably something that can be understood within 15-20 sec.
                3.  One Click access to George's Work History
                4.  A skills summary page needs to be present
                5.  An Education and/or Professional Development page needs to be present
                -   ##### Results
                -   (1, 3, 4, 5) PASS All conditions met; links were verified.
                -   (2) PASS. A skills progress bar graphic exists on the Skills page showing level of technical knowledge of certain software development and project management skills.

    -   #### Casual Visitor Experience
        -   **Story 5** As a Casual/AdHoc Visitor, I want to experience what is presently considered a basic, but effective and pleasing layout and responsiveness so I can learn by example and enhance my skills.
            -  ##### Acceptance Criteria -- Duplicated in Testing below
                1.  Mobile experience on Home page should not require a scroll to view entire Home page content (portrait view)
                2.  The Desktop Home page should offer more initial information on site content and offer a more robust nav that will not be displayed on the mobile view Home
                3.  Use at least one advanced Bootstrap components on the site.
                -   ##### Results
                -   (1) PASS; Scrolling on mobie Home page is minimal but all content is viewable on iPhone6/Safari [Screenshot](https://github.com/GeorgeLychock/georgelychock-career/blob/main/_documentation/testing/screenshots/userstory-5_1-screenshotfrom2020-12-30.jpg)
                -   (2) PASS; Home page on tablet and desktop shows a profile, credentials, and nav bar that is not seen on mobile [Screenshot](https://github.com/GeorgeLychock/georgelychock-career/blob/main/_documentation/testing/screenshots/userstory-5_2-screenshotfrom2020-12-30.jpg)
                -   (2) PASS; Skills page uses the Bootstrap Progress component [BS Doc](https://getbootstrap.com/docs/5.0/components/progress/) [Screenshot](https://github.com/GeorgeLychock/georgelychock-career/blob/main/_documentation/testing/screenshots/userstory-5_3-screenshotfrom2020-12-30.jpg)


### Further Testing

-   The Website was tested on Google Chrome, Firefox and Safari browsers.
-   The website was viewed on a variety of devices such as Desktop, Laptop, iPhone6, iPad8.
-   Testing was done to ensure that all pages were linking correctly.
-   A design professional friend of mine spent 30 minutes with me reviewing the overall design after all pages were constructed and styled.
-   All pages were given at least one cold read.
-   Used Lighthouse to identify areas on improvement which are documented below in Fixed Bugs after Testing.

### Fixed Bugs after Testing
-   Issue: On tablet viewports the My Profile Section overflows on the Credentials Section on Home page.
    -   Fix: Adjusted the row divs style to be completely responsive across all viewports, portrait and landscape. Also adjusted the My Profile links to take up less width.
-   Issue: Hero image does not properly fill the full viewport; mobile viewports either scroll or the site doesn't fil the entire screen leaving a black background visible at bottom.
    -   Fix: This was a major larger issue; properly sizing the hero image to fill the full height of the viewport was a blocker requirement. Started with a fresh shell for the Home page; properly added the hero image to fill full viewport on mobile; added section by section markup from the original Home page and fixed styles as needed. Followed [Bootstrap Documentation on Sizing](https://getbootstrap.com/docs/4.0/utilities/sizing/).
-   Issue: On mobile view social nav icons do not center properly.
    -   Fix: Set padding to rem units on i element (Font Awesome icon).
    -   Justification: I have been using rem units on as much sizing as possible with the intention of a smoother responsiveness between viewports.
-   Lighthouse Issue: Site wasn't using rel="noreferrer" attribute on the a links
    -   Fix: Added the att to all a links
-   Lighthouse Issue: missing meta description tag
    -   Added the meta tag to all pages


### Known Bugs
-   Nu HTML Checker: INDEX, PORTFOLIO, EDUCATION, PROFILE Pages: "The element a must not appear as a descendant of the button element..."
    -   The Bootstrap Modal Component tested with no errors using the a element as a descendant to the button element in the following browswers: FireFox, Chrome, Safari. But, the HTML validator is rejesting the application. For now I will keep the struture as is and recognize the error as something to be addressed in the future.

## Deployment
### Hosting

The project was deployed to GitHub Pages hosting service:

[URL to GitHub Pages Site](https://georgelychock.github.io/georgelychock-career/)

GitHub Pages
The project was deployed to GitHub Pages using the following steps...
   1. Log in to GitHub and locate the [georgelychock-career GitHub Repository](https://github.com/GeorgeLychock/georgelychock-career)
   2. At the top of the Repository (not top of page), locate the "Settings" Button on the menu.
       ◦ Alternatively Click Here for a GIF demonstrating the process starting from Step 2.
   3. Scroll down the Settings page until you locate the "GitHub Pages" Section.
   4. Under "Source", click the dropdown called "None" and select "Master Branch".
   5. The page will automatically refresh.
   6. Scroll back down through the page to locate the now published site link in the "GitHub Pages" section.

## *CLOANING INFORMATION from CODE INSTITUTE README.md template from User Centric Module*
### Forking the GitHub Repository

1. Log in to GitHub and locate the [georgelychock-career GitHub Repository](https://github.com/GeorgeLychock/georgelychock-career)
2. At the top of the Repository (not top of page) just above the "Settings" Button on the menu, locate the "Fork" Button.
3. You should now have a copy of the original repository in your GitHub account.

### Making a Local Clone

1. Log in to GitHub and locate the [georgelychock-career GitHub Repository](https://github.com/GeorgeLychock/georgelychock-career)
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

-   [MDN Web Docs](https://developer.mozilla.org/) : For Semantic Structure reference.

### Content

-   All content was written by the developer.

### Media

-   All Images were created by the developer.

### Acknowledgements