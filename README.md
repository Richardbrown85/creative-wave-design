# Creative Wave Design website

[View deployed site here](https://richardbrown85.github.io/creative-wave-design-website/)

### Devices mock up

![Device mock ups](<README images/Final-mock-up.webp>)

### About the website

A website design for graphic design company called Creative Wave Design based in the U.K.
The website will feature projects of work, gallery of work and an enquiry form for logo or visual branding job.
The goal of this website is to showcase work but the primary goal of the website is to create leads on potential clients.

### The business goals

* Build brand awareness.
* Provide high quality examples of work on a projects page and gallery.
* Create more leads for potential clients.
* Eyecatching and engaging content to keep potential clients on the site and turn them into leads.

### The client goals

* Clear and easy to fill out enquiry form.
* Search for high quailty images of work.
* Examples of reasoning behind concepts and ideas.

# UX

### The ideal client

* Business owner (small or large).
* Would like a new logo or branding designing for their business.
* Mainly U.K based (but can be outside of the U.K)

## User stories

### User story 1:
As a potential client I want to view Creative Wave Design projects of pervious work so that I can see their design style.

### Acceptance Criteria

* Portfolio displays logos and branding work by business type (Shop, contracters/builders, community centres)
* Each project section shows logo, concept and brief project description of work.

### Development Tasks

* Design responsive project layout.
* Make it easily accessible with navigation between each project section.

### User story 2:

As a small business owner I want to easily request a quote for a logo design service so that I can understand the pricing
and timeline before committing to work with Creative Wave Design.

### Acceptance Criteria

* Enquiry form is prominently accessible from homepage and navigation.
* User is directed to success page after submitting form with response time.
* Form validates all required fields before submission.

### Development Tasks

* Design user-friendly enquiry form.
* Form must validate all required fields before submitting.
* Success page with relevant information on such as response time and option to go back to homepage.

## Research before starting wireframe mock ups

I conducted a little bit of research on other websites for graphic designer before starting my own mock up of my 
design. They are as followed and links provided.

* Seeside Studios  https://www.seesidestudio.com/
* Made by James  https://themadebyjames.com/
* Abi Connick  https://www.abiconnick.co.uk/

## Creative Wave Design wireframe mockups using Balsamiq

### Home page wireframe
![Home page wireframe](<README images/Homepage-wireframe.png>)

### Projects page wireframe
![Projects page wireframe](<README images/Projects-page-wireframe.png>)

### Gallery page wireframe
![Gallery page wireframe](<README images/Gallery-page-wireframe.png>)

### Enquiry form page wireframe
![Enquiry page wireframe](<README images/Enquiry-form-page-wireframe.png>)

### Success page wireframe
![Success page wireframe](<README images/Success-page-wireframe.png>)

## Features

Every page features a responsive navigation bar with the creative wave deisgn logo in the top left corner which acts as a homepage link as well.
Full desktop view has an enquiry button that links to the enquiry form page. All pages have a footer with social media links for Instagram and Facebook and copyright information.

Every page is styled in the same colour scheme so it creates a consistent look. Every page in desktop view has a full screen background image of
the logo for creative wave design repeated in a symmetric pattern with the opacity set a 60% this was created in Abode illustrator. This is also fixed so the website content scrolls over it. On smaller screens this is set to none with a media query to have a background colour instead
#F9F9F9. 

#### Home

Home page includes a header in over the rainbow (font) with creative waves logo to the right handside in a different.
Because this is a new start up graphic design studio the testimonials are first inline to read to 
gain trust and confidence with new clients.

After that you get examples of logo designs which then continues down to the footer for contact through social media.

#### Projects page

The project page features three cards that present three main projects creative wave design have worked on over the past six months. Each project card has an example of the logo design and a short explanation about the idea, concept and design to give potential clients an idea of the process in logo design and to help them understand it.

#### Gallery page

The gallery page displays logo designs, mock ups and real world photos of the logos. These are laid out in a very simple layout of circles to follow the flow of creative waves logo design. These layout is responsive depending on screen sizes.

#### Enquiry page

The enquiry features a very simple form to fill in with name, email, phone number, enquiry type - helps the client chose the reason of the enquiry, message - for the potential client to write a sort paragraph about their enquiry and then the submit button.

#### Success page

The success page to primaily there to inform the user that their form has successfully been submitted and a response is to be expected within a time frame. This time frame with either be 24 hours, 48 hours or 3 business working days. 

## Typography and Colour Palette

### Typography

1. Primary Font (Paragragh and text):

#### Montserrat

* Style: Modern, geometric sans-serif
* Use: Paragraphs, body of text
* Why: Strong presence, creative feel, and excellent readability

2. Secondary Font (Headers):

#### Over the Rainbow

* Style: Clean, calligraphy handwritten
* Use: Headings, captions, taglines
* Why: Very readable, professional, and pairs beautifully with Montseerat.

### Web-friendly and Accessible:

* Optimized for screens
* Supported across all modern browsers
* Available for Google Fonts (fast CDN, easy integration)
* Highly readable at all sizes

Over the Rainbow grabs attention for headings and taglines.
Montserrat is very legible on long paragraphs and small interface elements.

### Color Palette/Scheme : "Vibrant Ocean"

A high-contrast palette inspired by waves and creativity

* Primary-color: #058095; Blue lagoon
* Secondary-color: #D8F0F0; Swans down
* Highlight-color: #26BFCC; Scooter
* Light-highlight-color: #8BD3D9; Morning glory



## Technologies Used

- This project uses HTML and CSS programming languages.
- Github - VScode was used for the IDE (any can be used) connected to Github for the repository and deployment of website.
- Bootstrap CDN - The project uses Bootstrap V5.3 a grid system was used to structure the website and make it responsive easily and Bootstrap   CSS 5 which is used on the homepage.
- Google fonts - The project uses google fonts to import the selection typography for the website.
- Font Awesome - The project uses font Awesome for social media icons (instagram and facebook).
- Favicon - Favicon link has been used to place the creative wave design in the navbar.
- Adobe illustrator and photoshop - Used for image creating, rendering and sizing.

## Testing

Testing was conducted on the deployed site through Github.

### Manual testing

#### Functionality

| Test | Test Action | Excepted results | Test results |
| ---- | ----------- | ---------------- | ------------ |
| Enquiry form | Test navigation to enquiry form	| Navigation to enquiry form was easily accessible and easy to find | PASS |
| Test the enquiry form | Does the enquiry form have the right fields for the correct data to be collected for new clients | The enquiry form has the correct  fields such as Name, Email, Phone etc | PASS |
| Fill out enquiry form | Fill out enquiry form, does it display a succes message or page | Directed to a success page | PASS |
| Return button (success page) | Does the return button work on the success page properly | The return button directs you back to the home page | PASS |
| Social media links | Test the social media links to see if they work correctly | Social media links direct you to the correct pages when clicked | PASS |
| Navigation | Test the navigation back and forth from page to page. For example - home to gallery, home to projects |	Navigation works correctly | PASS |

#### Browser Compatibility

The deployed site works on the following internet browsers
- Google Chrome
- Firefox
- Edge

#### Responsiveness

The deployed site has been tested across different screen sizes for responsiveness.
The behaviour of the site was to be excepted. The site responded accordingly from 320px through to 2560px.

### Techologies used for testing

- Google Chrome DevTools (Lighthouse)
- W3C HTML Validation https://validator.w3.org/
- W3C CSS Validation https://jigsaw.w3.org/css-validator/
- Wave web accessibilty evaluation tool https://wave.webaim.org/

### Lighthouse (Google Chrome DevTools)

#### Homepage (index.html) - Desktop
![Lighthouse test index.html](<README images/Lighthouse-test-desktop-index.html.png>)
#### Projects page (projects.html) - Desktop
![Lighthouse test projects.html](<README images/Lighthouse-test-desktop-projects.html.png>)
#### Gallery page (gallery.html) - Desktop
![Lighthouse test gallery.html](<README images/Lighthouse-test-desktop-gallery.html.png>)
#### Enquiry page (enquiry.html) - Desktop
![Lighthouse test enquiry.html](<README images/Lighthouse-test-desktop-enquiry.html.png>)
#### Success page (success.html) - Desktop
![Lighthouse test success.html](<README images/Lighthouse-test-desktop-success.html.png>)

### W3C HTML Validation

#### Homepage (index.html) 
![index.html Validation](<README images/HTML-validation-on-index.html.png>)
#### Projects page (projects.html)
![projects.html Validation error](<README images/HTML-validation-on-project.html-errors.png>)
Line 65 needed a closing div element. Correction maded.
![projects.html Validation](<README images/HTML-validation-on-project.html.png>)
#### Gallery page (gallery.html)

#### Enquiry page (enquiry.html)

#### Success page (success.html)


### W3C CSS Validation

#### Style.css (Custom CSS)


## Deployment

This project was developed using [VScode](https://code.visualstudio.com/), commited to git and pushed to GitHub using the built in function within VScode.

This site is hosted using GitHub pages, deployed directly from the master branch. The deployed site will update automatically upon new commits to the master branch. In order for the site to deploy correctly on GitHub pages, the landing page must be named index.html.

These are the steps that can be taken to deploy the page on GitHub pages from it's [GitHub repository](https://github.com/Richardbrown85/creative-wave-design-website):

    1. Log into GitHub.
    2. From the list of repositories on the screen, select Richardbrown85/creative-wave-design-website.
    3. From the menu items near the top of the page, select Settings.
    4. Scroll down to the GitHub Pages section.
    5. Under Source the drop-down menu should display Deploy from a branch
    6. On selecting Main Branch the page is automatically refreshed, the website is now deployed.
    7. Scroll back up to the GitHub Pages section to retrieve the link to the deployed website.

The deployed site can also be found on the repository page on the right handside under Deployments.

To run locally, you can clone this repository directly into the editor of your choice by pasting git clone into your terminal. This can be found on the main repository page, clicking the code button and copy [Clone https](https://github.com/Richardbrown85/creative-wave-design-website.git). To cut ties with this GitHub repository, type git remote rm origin into the terminal.

## Credits

### Content
- The welcome paragraph on the homepage was a prompt using ChatGBP.
- The testimonials on the homeapge were written by clients. 

### Media
- All media used belongs to Creative Wave Design (Me aka Richard Brown)

### Code
 - Custom CSS code was written by me.
 - Some HTML was copied directly from Bootstrap V5.3

#### Disclaimer

The content of this website is my own piece of work which I am otherwise the sole author. I understand both the meaning and consequences of plagiarism.






  
  
  





















