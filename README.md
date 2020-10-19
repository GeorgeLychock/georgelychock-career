## georgelychock-career.com
### My User Centric Frontend Development Milestone Project

<h1 align="center">George Lychock Career Website</h1>

[View the live project here.](http://www.georgelychock-career.com/pages/test/index.html)

This is the main career website for George Lychock. It contains all the job, education, and professional development information for George Lychock. This site will replace my Bootstrap3 site that currently exists at www.georgelychock-career.com. I plan to use a hybrid of the existing content, learned modules from the CI lesson plan, and other resources I have found along the way, but all the code will be completely new and any 'borrowed' code will be documented below.

<h1  align="center"><img src="http://www.georgelychock-career.com/images/glcareer-opener-03-750w.png"></h1>

-   ## User Experience (UX)
    Since this site will almost always be accessed by first-time users, the focus will be on a more simple, not busy design and navigation. Very few images. Precise and succinct content, fewer words, more content flow. My old career site, based on Bootstrap3 was too word heavy. The mobile experience needs to be completely flawless and error free as I suspect that up to 25% of the traffic will be via mobile device.

-   ### User stories

    -   #### General User Experience
        
    1.  As a Site Visitor, I want to be able to easily navigate throughout the site to find content.
        -   ##### Acceptance Criteria
            * Main Content should never be more than **two clicks** away from home.
            * Home should never be more than **one click** away from anywhere on the site.
            * Nav dropdown is required, giving access to any main content page [caeeer objectives, education, skills, work history, and professioanl development.]

    2.  As a Site Visitor, I want to be able to see a similar experience whether desktop, tablet, or mobile, so that I can later access information in a similar manner if I change devices.
        -   ##### Acceptance Criteria
            * All content, with exception of imagery, has to be accessible from desktop, tablet, or mobile device.

    -   #### Recruiter and HR Contact Experience

        1. As a Recruiter, I want to easily understand what types of information about George Lychock will be available so I can determine if George has minimum requirements to be considered further. 


    -   #### Hiring Manager Experience

        1. No goals at present.

    -   #### Casual Visitor Experience
        1. No goals at present.

-   ### Design
    -   #### Colour Scheme
        -   TBD. Most like using a white main background to give a more professional look as opposed to black.
    -   #### Typography
        -   TBD.
    -   #### Imagery
        -   Images will be kept to a minimum, most likely just a hero image of something that corresponds to George's PD or Education. Also, a sidebar image will be used for all secondary pages.
    -   #### Iconography
        -   Use icons in nav elements, social media elements

*   ### Wireframes

    -   Home Page Wireframe - [View](https://github.com/GeorgeLychock/ssu-fullstackdev-user-centric-bs/blob/master/_documentation/_wireframes/georgelychock-career-desk-01.pdf)

    -   Mobile Wireframe - [View](https://github.com/GeorgeLychock/ssu-fullstackdev-user-centric-bs/blob/master/_documentation/_wireframes/georgelychock-career-smart-01.pdf)

    -   Contact Us Page Wireframe - [View](https://github.com/)

## Requirements
-   ### Business Reqs
    -   #### UX
        -   Smartphone first design; to replicate a native app as closely as possible
        -   Re-work Smartphone UX into a desktop experience
        -   wireframes for both scenarios need to be approved prior to prod dev (dev can spend up to 5% of BP budget prior to approval)
-   ### Structure Reqs
    -   Persistent nav footer on Smartphone viewports
    -   Resume download to be present at top on all screens
-   ### Navigation Reqs
    -   Persistent Back button


## Approved Features and Initial Release Strategy

Release 1
-   Responsive on all device sizes
-   Reveal a pitch, a hero image, contact information
-   Method to show skill set
-   Method to download resume
-   Design and Apply structure
-   Define Look and Feel

Release 2
-   Apply Look and Feel
-   Method to view my work history
-   Method to see what I have been working on in Professional Development

Release 3
-   Method to show education history
-   Method to show what I work on outside of my main career

Release 4
-   Method to connect to my github repo
-   Method to quickly get to my social media sites



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
    - Balsamiq was used to create the [wireframes](https://github.com/) during the design process.
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

-   The full-screen hero image code came from this [StackOverflow post](https://stackoverflow.com)

-   [Bootstrap4](https://getbootstrap.com/docs/4.4/getting-started/introduction/): Bootstrap Library used throughout the project mainly to make site responsive using the Bootstrap Grid System.

-   [MDN Web Docs](https://developer.mozilla.org/) : For Pattern Validation code. Code was modified to better fit my needs and to match an Irish phone number layout to ensure correct validation. Tutorial Found [Here](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/input/tel#Pattern_validation)

### Content

-   All content was written by the developer.

-   Psychological properties of colours text in the README.md was found [here](http://www.colour-affects.co.uk/psychological-properties-of-colours)

### Media

-   All Images were created by the developer.

### Acknowledgements