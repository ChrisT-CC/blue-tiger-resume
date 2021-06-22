# Blue Tiger Resume

The "Blue Tiger resume" is a resume website for an imagined full stack software developer.


The purpose of this website is to create an on-line presence for a wannabe coder. No real info, based on random full stack software developer resume. The website is for recruiters, potential clients, peers and why not, assessors. 
The look, brand name and colours come from the image used on the main page. 

This website can be easily recreated for a real situation.

Visit live website: [https://christ-cc.github.io/blue-tiger-resume/](https://christ-cc.github.io/blue-tiger-resume/)

![Mockup image](assets/readme/images/blue-tiger-mockup.jpg)

## Table of contents
1. [UX](#UX)
    - [User Stories](#User-stories)
    - [Structure](#Structure)
    - [Skeleton](#Skeleton)
    - [Surface](#Surface)
2. [Features](#Features)
    - [Existing Features](#existing-features) 
        - [Navigation menu](#Navigation-menu)
        - [The landing page](#The-landing-page)
        - [About section](#About-section)
        - [Skills section](#Skills-section)
        - [Clients section](#Clients-section)
        - [The footer](#The-footer)
            - [Social media links](#Social-media-links)
            - [Up arrow](#Up-arrow)
            - [Copyright](#Copyright)
        - [Experience page](#Experience-page)
        - [Contact page](#Contact-page)
    - [Features left to implement](#features-left-to-implement)
3. [Technologies Used](#Technologies-Used)
4. [Testing](#Testing)
5. [Deployment](#Deployment)
6. [Credits](#Credits)


## UX
In this section you'll find elements of UX process.

### User stories

- The developer wants to establish an on-line presence, to find work.
- The owner wants an image and cover text on the main page to visualy explain what the website is about.
- The owner wants floating social media icons always visible, to offer easy acces to further details.
- Recruiters want to see owners name (or brand name) and position to find out what type of coder te owner is.
- Recruiters want to see owner's skills to be able to evaluate coder's level.
- Recruiters want to see owner's past and current jobs to evaluate coder's experience and availability.
- Recruiters want to see past clients to find out if they deal with a genine coder with real clients.
- Any user wants to see a simple to use and clean looking website to have easy access to information.
- Any user wants an easy way to navigate the website to save time and avoid frustration.
- Any user wants a responsive website to be able to use it on their device of choice.
- Any user wants to be able to get in touch with the owner to be able to ask for a service, or just to leave a messege.
- Recruiters want to be able to download a classic resume to use it in their hiring process.

### Structure
The website has a simple structure with 3 different pages and 3 sections on the main page. A minimalistic text content was used with emphasis on visual elements.
- Main page contains a brand hero image and owner position
    - About section gives a short description and links contact page
    - Skills section shows coding skills
    - Clients section presents a portfolio of past clients
- Experience page contains a timeline of past jobs
- Contact page gives owners details and the posibility of contact
- [Site map](assets/readme/wireframes/site-map.pdf)

### Skeleton
In this section wireframes were created. Initial simple, hand drawn wireframes were refined in [Balsamiq](https://balsamiq.com/) and presented below.
- [Main page wireframes](assets/readme/wireframes/main-page.pdf)
- [Experience page wireframes](assets/readme/wireframes/experience-page.pdf)
- [Contact page wireframes](assets/readme/wireframes/contact-page.pdf)

### Surface
In this section you'll find info on website's look and feel. 

The look of the landing page was inspired from [this website](https://wpshopmart.com/html/demo/resume-template-1/index.html).
#### Colours
 The website was designed with anonymity in mind. While searching for an aproprite hero image, the tiger image was found. That image inspired the branding and colours for the project.

A shade of blue, predominant in the tiger's image background, was used  ([ColorZilla](https://www.colorzilla.com/)) as body background colour. Different shades of that blue were used throughout the project, depending on necessity. The blue shades used were obtained with [ColorSpace](https://mycolor.space/).

Light blue from tiger's eye was used to emphasize navigation hovering, the word "Blue" in cover text on main page and other elements.

A light gray was used instead of pure white for most text and other elements. The original light gray was changed with a different, lighter shade after testing for contrast with [WebAIM](https://webaim.org/resources/contrastchecker/).

For hovering over social media icons and up arrow link, a shade of blue was used, similar with facebook blue to offer contrast.

The website's palette saved from [coolors](https://coolors.co/3c4856-212f49-273a58-46719c-75b0d8-f2f2f2-1773ea) can be seen bellow:

![Palette](assets/readme/images/palette.png)

#### Language
A descriptive language was used with a minimalistic text content. [Google Fonts](https://fonts.google.com/) were used to create a clean look. Thick compact font for navigation menu to be visible on smaller screens. A strong font for logo and headers with a suggestet paired font for the rest of the text.

## Features
In this section, you can find implemented features as well as some features left for a future development stage.

## Existing Feature
### - Navigation bar
Responsive and visible on all three pages. Contains brand logo and navigation links to all pages and sections of page. The content of each page and section is self-explanatory, so no active link feedback was used to preserve the color theme throughout.

![Navigation menu](assets/readme/images/nav-bar.jpg)
### -The landing page
Contains a brand image, name and owners position. 
### - About section
Contains an image, a brief description and a link to contact page. The image used, continues the ideea of anonimity.

![About section](assets/readme/images/about-section.jpg)
### - Skills section
Contains a list of skills, each with a level bar, with the appropriate percentage level. Text was used for the skill names instead of logos to help with SEO.

![Skills section](assets/readme/images/skills-section.jpg)
### - Clients section
Displays logos for five former, imagined clients. The same text colour was used for consistency, with real logo colours on hover. This section is responsive. 

![Clients section](assets/readme/images/clients-section.jpg)
### - The footer
Can be found on each page and it has three elements.
   - #### Social media links
   Discreet, always visible, [Font Awesome](https://fontawesome.com/) social media icons. They are floating at the bottom left corner of every page and section. Offers easy access to owner's details.

   ![Social media icons](assets/readme/images/social-icons.jpg)
   - #### Up arrow 
   Discreet, always visible, [Font Awesome](https://fontawesome.com/) double chevron, helps navigate back to the top of the page.

   ![Up arrow link](assets/readme/images/up-arrow.jpg)
   - #### Copyright 
This is a common section on most websites. It was set at the bottom of page on a black background colour. 
### - Experience page
Presents an easy overview of past jobs aranged on a timeline. Each job is shaped as a card with company logo, employment dates and position held with company. The job card is anchored to the timeline with a [Font Awesome](https://fontawesome.com/) briefcase icon. This section is responsive and opens in a different page.

![Experience page](assets/readme/images/experience-page.jpg)
### - Contact page
This page shows contact details and an input form. The form offers the posibility to send a message back to the owner. [Font Awesome](https://fontawesome.com/) icons were used in details section. This section is responsive and opens in a different page.

[Code Institute's](https://codeinstitute.net/) dump form was used to deal with form's data. 

![Contact page](assets/readme/images/contact-page.jpg)
## Features Left to Implement
- **Download resume** - A useful feature in a real resume website. It was not implemented in this project. To implement it, the "resume" word in the logo would be in a `<span>` tag, add a link inside the `<span>` tag with "download" attribute, add the resume file into the project. The styling would be: on hover change size to 75%, change background color to menu background colour, add [Font Awesome](https://fontawesome.com/) download icon. 
- **Projects page** - a useful feature for a real resume website, so the user doesn't have to navigate [GitHub](https://github.com/) repos. 
- **Live social media links**
- **Education page** - was not implemented because the section skills shows developers strenghts and more and more developers are self-taught. Useful feature for a developer with classic education background.
- **Password protected access** to website - a form of control of who gets access to owners personal details. On a job application the owner would sent a one time password to the recruiter with a limited one hour access to the website. 


## Technologies Used
1. [HTML](https://en.wikipedia.org/wiki/HTML) - Programming language used for website structure and content
2. [CSS](https://en.wikipedia.org/wiki/CSS) - Programming language used for styling website
3. [Font Awesome](https://fontawesome.com/) - Social media icon library
4. [Google Fonts](https://fonts.google.com/) - Free font styles to use on website
5. [Compressjpeg](https://compressjpeg.com/) - For compressing image file sizes to maximise loading speed
6. [Balsamiq](https://balsamiq.com/) - Used to create wireframes
7. [Am I Responsive?](http://ami.responsivedesign.is/) - To check responsiveness and for mockups
8. [Gitpod](https://www.gitpod.io/) - IDE (Integrated Development Environment), for writing, editing and saving code
9. [GitHub](https://github.com/) - Code repository hosting platform
10. [ColorZilla](https://www.colorzilla.com/) - Browser extension for sampling colours on a website
11. [ColorSpace](https://mycolor.space/) - Colour palette generator, used choosing colours 
12. [coolors](https://coolors.co/3c4856-212f49-273a58-46719c-75b0d8-f2f2f2-1773ea) - Colour palette generator, used for saving palette for readme
13. [WebAIM](https://webaim.org/resources/contrastchecker/) - contrast checker

## Testing
In this section, you need to convince the assessor that you have conducted enough testing to legitimately believe that the site works well. Essentially, in this part you will want to go over all of your user stories from the UX section and ensure that they all work as intended, with the project providing an easy and straightforward way for the users to achieve their goals.

Whenever it is feasible, prefer to automate your tests, and if you've done so, provide a brief explanation of your approach, link to the test file(s) and explain how to run them.

For any scenarios that have not been automated, test the user stories manually and provide as much detail as is relevant. A particularly useful form for describing your testing process is via scenarios, such as:

1. Contact form:
1. Go to the "Contact Us" page
1. Try to submit the empty form and verify that an error message about the required fields appears
1. Try to submit the form with an invalid email address and verify that a relevant error message appears
1. Try to submit the form with all inputs valid and verify that a success message appears.
In addition, you should mention in this section how your project looks and works on different browsers and screen sizes.

You should also mention in this section any interesting bugs or problems you discovered during your testing, even if you haven't addressed them yet.

If this section grows too long, you may want to split it off into a separate file and link to it from here.

## Deployment
This section describes the process of deploying the project to GitHub Pages.

### Deploying to GitHub Pages
1. Open a browser and navigate to [Github.com](https://github.com/)
2. Log in to GitHub account
3. Click on "Responsitories" or select "Your repositories" from profile menu at the top right corner
4. Select "blue-tiger-resume"
5. Go to "Settings" tab
6. Scroll down until you find "Github pages" and press the link you find there, or just choose "pages" from the left sidebar
7. Under "source" change "none" to  "master" branch and then press "save"
8. Refresh the page (can take a few minutes) and then under "Github pages" you have the new URL for the live project

### Running the project in [Gitpod](https://www.gitpod.io/) 
1. Open a browser and navigate to [Github.com](https://github.com/)
2. Log in to GitHub account
3. Click on "Responsitories" or select "Your repositories" from profile menu at the top right corner
4. Select "blue-tiger-resume"
5. Add "gitpod.io/#" before URL in address bar and press "enter"

### Running the project locally
1. Open a browser and navigate to [Github.com](https://github.com/)
2. Log in to GitHub account
3. Click on "Responsitories" or select "Your repositories" from profile menu at the top right corner
4. Select "blue-tiger-resume"
5. Locate and click on the "Code" button
6. Copy the URL under "HTTPS"
7. In your IDE of choice, create a new repository
8. Type "git clone 'copied URL'" and press enter

## Credits
### Design
The look of the landing page was inspired from [this website](https://wpshopmart.com/html/demo/resume-template-1/index.html).
### Content
Code Institute [readme template](https://github.com/Code-Institute-Solutions/readme-template) and [Love running readme](https://github.com/Code-Institute-Solutions/readme-template) were used to write this readme file.
### Media
The photos used in this website were obtained from the websites below and were edited to better fit the project:
- [Pixabay](https://pixabay.com/)
    - [Blue tiger image](https://pixabay.com/get/g4bf97df2dea64f4fc1cea02179b1e40a68100b0632311e97e175062e25c4d9c457f25ec39d64263accee0ccb35340133.jpg)
- [Rawpixel](https://www.rawpixel.com/?sort=shuffle&page=1&feed=creative-feed)
    - [About photo](https://www.rawpixel.com/?sort=shuffle&page=1&feed=creative-feed)
- [Pngimg](https://pngimg.com/)
    - [Amazon logo](http://pngimg.com/uploads/amazon/amazon_PNG13.png)
    - [Apple logo](http://pngimg.com/uploads/apple_logo/apple_logo_PNG19668.png)
    - [Google logo](http://pngimg.com/uploads/google/google_PNG19642.png)
    - [Microsoft logo](http://pngimg.com/uploads/microsoft/microsoft_PNG20.png)
- [Logos world](https://logos-world.net/)
    - [Facebook logo](https://logos-world.net/facebook-logo/)
### Acknowledgements
- Thanks to my mentor for suggetions and time
- Thanks to my family, friends and peers for suggestions, reviews and feedback
