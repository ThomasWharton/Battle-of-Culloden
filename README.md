# Battle of Culloden

![Responsive Mockup](docs/screenshots/am_i_responsive.png)

## Introduction

Battle of Culloden is a website giving a brief history of the Battle of Culloden and information regarding the visitor centre for the battlefield itself. 

This site is aimed at tourists of Scotland looking to plan a day out with the ability to book a guided tour around the museum and battlefield.

## Table of Contents

  * [UX](#ux)
    + [User Goals](#user-goals)
    + [User Stories](#user-stories)
    + [Site Owner Goals](#site-owner-goals)
    + [Requirements](#requirements)
    + [Expectations](#expectations)
  * [Design Choices](#design-choices)
    + [Fonts](#fonts)
    + [Icons](#icons)
    + [Colours](#colours)
    + [Structure](#structure)
  * [Wireframes](#wireframes)
  * [Features](#features)
    + [Navigation Bar](#navigation-bar)
    + [Home Section](#home-section)
    + [History Section](#history-section)
    + [Visitor Centre Section](#visitor-centre-section)
    + [Contact Information Section](#contact-information-section)
    + [Book a Tour Section](#book-a-tour-section)
    + [Footer](#footer)
    + [Features to be Implemented](#features-to-be-implemented)
  * [Technologies Used](#technologies-used)
    + [Languages](#languages)
    + [Libraries & Framework](#libraries---framework)
    + [Tools](#tools)
  * [Testing](#testing)
    + [Validator Testing](#validator-testing)
    + [Wave Testing](#wave-testing)
    + [Lighthouse Testing](#lighthouse-testing)
  * [Deployment](#deployment)
  * [Credits](#credits)

## UX

### User Goals

* Easy to navigate.
* Quality and necessary content.
* Asthetically pleasing with relevant images.
* Easy to find contact information.
* Booking form for guided tours.

### User Stories

* As a user, I want a website where I can find basic information on the Battle of Culloden.
* As a user, I want a website which is easy to navigate.
* As a user, I want easy to read information regarding the visitor centre.
* As a user, I want to easily find contact information for the centre.
* As a user, I want to be able to book a guided tour.
* As a user, I want pricing information on entry to the visitor centre and guided tours. 

### Site Owner Goals

* To attract tourists to the visitor centre.
* To increase the amount of guided tours being booked.
* To give potential visitors clear and concise information on the visitor centre.

### Requirements
* Easily navigated on a variety of screen sizes.
* Clear and easy to read information.
* Asthetically pleasing design to keep users engaged.
* Easy to find contact information.
* Easy to use booking form.

### Expectations
* I expect all navigation links to function correctly.
* I expect the website to look good on a variety of screen sizes.
* I expect any social media links to navigate to a new tab.
* I expect to know a form has been successfully submitted and that all relevant fields have been filled in correctly.
* I expect all information provided to be accurate.

## Design Choices

### Fonts

To add more character to the site, [Google Fonts](https://fonts.google.com/ "Google Fonts") was used to select 3 fonts to be used across the site. For the page logo, [Cinzel](https://fonts.google.com/specimen/Cinzel/ "Cinzel") was used as this fits the "history" aesthetic of the site and catches the eye of the user to create an immediate interest. For headers and navigation links, [Playfair Display](https://fonts.google.com/specimen/Playfair+Display "Playfair Display") was selected to make them stand out from the main text, it also blends well with theme of the site. Lastly, for the main text, [Noto Sans](https://fonts.google.com/noto/specimen/Noto+Sans "Noto Sans") was used as this compliments the other fonts, as well as being easy to read.

### Icons

Icons were selected from the website [Font Awesome](https://fontawesome.com/ "Font Awesome"). These icons are used to represent the navigation element on smaller screens and for social media links in the footer.

### Colours

The initial colour (demin) was selected due to it being the blue colour in the Scottish flag and would therefore fit the theme of Scottish history. The hexcode for demin was found using the website [Flag Color Codes](https://www.flagcolorcodes.com/scotland "Flag Color Codes"). [Coolors](http://coolors.co "Coolors") was then used to create the colour palette for the website with the first selection of denim being locked in and the rest of the palette following suite. 

The colours and their uses are listed below.

![Colour Palette](docs/screenshots/colour_scheme.png)

* #005EB8 - This colour will be used for the header, footer and form elements. 
* #009CFC - This colour will be used for the table and list borders.
* #0076AC - This colour will be used as a background colour for sections and elements, as well as for text.
* #878E8D - This colour will be used for box shadows and a small amount of text.
* #FFFFFF - This colour will be used as a background colour for sections and elements, as well as for text.

### Structure

The site will be built with mobile first mindset with the Samsung Galaxy S8+ (360px) being the smallest screen size for styling of site. Using [Bootstrap breakpoints](https://getbootstrap.com/docs/5.0/layout/breakpoints/ "Bootstrap breakpoints"), screen size breakpoints will be selected for media queries to add optimised styling for different viewing purposes. The break points are shown below.

| Screen Size | Breakpoint|
| ------------|-----------|
| x-small     | <576px    |
| small       | >= 576px  |
| medium      | >= 768px  |
| large       | >= 992px  |
| x-large     | >= 1200px |

## Wireframes

Wireframes have been developed to give a general structure and layout to the site on various device sizes. The wireframes were created using [Balsamic](https://balsamiq.com "Balsamic"). The first wireframe was created with mobile screen size in mind and scaled up to tablet and desktop sizes. A one-page website is used to allow the user to quickly access all content available. This is especially true for mobile users who will be scrolling down continuously, rather than navigating through different pages. 

The wireframes are linked below:

### [Desktop Wireframe](docs/wireframes/boc-desktop.png)
### [Tablet Wireframe](docs/wireframes/boc-tablet.png)
### [Mobile Wireframe](docs/wireframes/boc-mobile.png)

## Features

### Navigation Bar

The navigation bar is fixed to the top of the screen to allow for easy access to different sections within the site. It is fully responsive in regards to different screen sizes and will change from a hamburger style drop down menu to a horizontal list on screen sizes greater than 992px. It also features the logo for the website to immediately capture the attention of the user.

* Desktop (>= 992px)
    * The navbar spans the entire width of the device and is complete with all links to direct to the different sections of the site. This allows for easy and clear access to all content for the user.

*Navbar large*<br>
![Navbar Desktop](docs/screenshots/navbar_large.png)

    
* The links will change colour when hovered over for better visibility for the user.

*Navbar hover* <br>
![Navbar Hover Effect](docs/screenshots/nav_hover.png)

* Small devices (<992px)
    * As the screen size decreases, the navigation menu becomes too long to fit into the navbar and remain aesthetically pleasing. Therefore on devices with a screen size of 992px or less, the navigation menu will be toggled on and off via a hamburger icon. When checked, the navigation menu will appear as a dropdown list.

*Navbar Small*<br>
![Navbar Small](docs/screenshots/navbar_small.png)

*Navbar dropdown*<br>
![Navbar Dropdown](docs/screenshots/nav_dropdown.png)

### Home Section

* The home section features the hero image which is an artist deptiction of the battle of Culloden. The image is very striking and works to create an interest for the user to learn more.

*Hero image*<br>
![Hero Image](assets/images/the_battle_of_culloden.webp)

### History Section

* The history section sets the scene with images and text content to build on the users initial interest in the battle. The images included are another depiction of the battle (similar to the hero image) and of both opposing side leaders. Each image is accompanied by some text, giving the user some basic information on the battle and the two forces.

*Large Screen Size*<br>
![History Large](docs/screenshots/history_large.png)

*Small and Medium Screen Size*<br>
![History Small](docs/screenshots/history_small.png)

### Visitor Centre Section

* The visitor centre section has 3 subsections. The subsections are for the museum, cafe and battlefield.

* Museum Subsection
    * The museum subsection has some information on what users will hope to find in the museum with a couple of images of sample artifacts.
    * The user will also be given information regarding the opening/closing times of the museum.
     
*Desktop*<br>
![Museum Desktop](docs/screenshots/museum_large.png)

*Tablet*<br>
![Museum Tablet](docs/screenshots/museum_medium.png)

*Mobile*<br>
![Museum Mobile](docs/screenshots/museum_small.png)

* Cafe Subsection
    * The cafe subsection includes a sample menu and the opening/closing times of the cafe.

*Desktop*<br>
![Cafe Desktop](docs/screenshots/cafe_large.png)

*Tablet*<br>
![Cafe Tablet](docs/screenshots//cafe_medium.png)

*Mobile*<br>
![Cafe Mobile](docs/screenshots/cafe_small.png)


* Battlefield Subsection
    * The battlefield subsection features an image of Leanach cottage which is situated on the battlefield. This image gives the user an idea of the beauty to be found whilst exploring the battlefield.
    * The image is accompanied by some text describing the battlefield and other landmarks to be found.

*Large Screen Size*<br>
![Battlefield Large](docs/screenshots/battlefield_large.png)

*Smaller Screen Size* <br>
![Battlefield Smaller](docs/screenshots/battlefield_small.png)

### Contact Information Section

* The contact information section contains the telephone number, email and postal address of the visitor centre.
* A google maps preview is embedded in this section with the ability to open up google maps in another tab. This allows users to easily plan travel to the visitor centre. 

*Desktop*<br>
![Contact Desktop](docs/screenshots/contact_large.png)

*Tablet*<br>
![Contact Tablet](docs/screenshots/contact_medium.png)

*Mobile*<br>
![Contact Mobile](docs/screenshots/contact_small.png)

### Book a Tour Section
* The book a tour section includes information on the tours, such as how often they take place and pricing information for different group sizes.

*Tablet*<br>
![Tour Tablet](docs/screenshots/tour_medium.png)

*Mobile*<br>
![Tour Mobile](docs/screenshots/tour_small.png)

* There is also a booking form where the user can give information such as their name, email address, telephone number, group size, date of tour and special requirements.

*Desktop*<br>
![Tour Section Large](docs/screenshots/tour_large.png)

*Form on smaller screen*<br>
![Form Small](docs/screenshots/form_small.png)

* Upon successful submission of the form, the user will be brought to a thank you page, confirming successful booking of a tour. The thank you page will include a link to navigate back to the main page.

*Thank you page*<br>
![Thank You Page](docs/screenshots/thank_you_page.png)


### Footer

* The footer section is styled to match the page header to maintain consistency. 
* The footer contains links to social media pages tied to the visitor centre. When clicked, these links will open in a new tab so the user does not have to navigate back to Battle of Culloden site.
* There is a hover effect to highlight the links, intended to improve the user experience.

*Footer*
![Footer](docs/screenshots/footer.png)

### Features to be Implemented

* Thank you page to include link to pay for tour in advance.
* Social media links would link to official visitor centre pages and not home pages of social media sites.

## Technologies Used

### Languages

* [HTML](https://en.wikipedia.org/wiki/HTML "HTML")
* [CSS](https://en.wikipedia.org/wiki/CSS "CSS")

### Libraries & Framework

* [Google Fonts](https://fonts.google.com "Google Fonts")
* [Font Awesome](https://fontawesome.com "Font Awesome")

### Tools

* [GitHub](https://github.com "GitHub")
* [Gitpod](https://gitpod.io "Gitpod")
* [Balsamic](https://balsamiq.com "Balsamic")
* [Bootstrap](https://getbootstrap.com "Bootstrap")
* [Coolors](http://coolors.co "Coolors")
* [DevTools](https://developer.chrome.com/docs/devtools "DevTools")
* [W3C Markup Validation](https://validator.w3.org/#validate_by_input "W3C Markup Validation")
* [W3C CSS Validation](https://jigsaw.w3.org/css-validator/#validate_by_input "W3C CSS Validation")
* [WAVE Web Accessibility Evaluation Tool](https://wave.webaim.org/ "WAVE Web Accessibility Evaluation Tool")

## Testing

Testing has been carried out extensively throughout the building process to ensure all features work as intended. Features have been tested on multiple platforms and the site is fully responsive on different screen sizes. All of the navigation links work correctly. The booking form submits successfully when all necessary fields are filled in and links to a thank you page. The social media links in the footer all successfully navigate to the correct pages in another tab.

### Validator Testing

The HTML and CSS code have been validated using [W3C Markup Validation](https://validator.w3.org/#validate_by_input "W3C Markup Validation") and [W3C CSS Validation](https://jigsaw.w3.org/css-validator/#validate_by_input "W3C CSS Validation"). All code has validated successfully without errors.

*HTML Validation*<br>
![HTML Validation](docs/screenshots/w3c_html.png)

*CSS Validation*<br>
![CSS Validation](docs/screenshots/w3c_css.png)

### Wave Testing

Testing has been completed using [WAVE Web Accessibility Evaluation Tool](https://wave.webaim.org/ "WAVE Web Accessibility Evaluation Tool") to ensure the site is fully accessible to those with impairments. The tests completed with minimal errors and those that do remain are intended, therefore will not be rectified. 

*Wave Test Results*<br>
![Wave Test Results](docs/screenshots/wave_report.png)

*Wave Errors*<br>
![Wave Errors](docs/screenshots/wave_errors.png)

* The empty form label error refers to the label used for the hamburger icon for the navigation menu on smaller screen sizes. As an icon is used for this and there is no text content, it sees the label as empty and therefore gives this error. After some research, I fixed this error by added a p element with a class of sr-hidden. Through this class I could add some text but have its visibility set to hidden. This makes the text only visible for screen readers.

* The two empty table headers errors refer to the opening/closing times tables header for the column containing the days of the week and are were originally intended to be blank. To fix this, content of **Day** was added and given the class of sr-only to hide it from regular viewing but making it accessible for screen readers.

*Wave Results After Fixing Errors*<br>

![Wave No Errors](docs/screenshots/wave_noerrors.png)


### Lighthouse Testing

The lighthouse function within devtools has been used to test the site for mobile and desktop. The site scores well across the board with room for some minor improvements. As these are minor and the site performs well, these are not deemed necessary to resolve. The lighthouse function proved useful in optimising the site with regards to reformating images and for optimising accessibility.

*Desktop Lighthouse Results*<br>
![Desktop Lighthouse Results](docs/screenshots/lighthouse_desktop.png)

*Mobile Lighthouse Results*<br>
![Mobile Lighthouse Results](docs/screenshots/lighthouse_mobile.png)

The site scores full marks for accessibility and search engine optimisation with some small improvements to be made with performance and best practices. It is also worth noting that the site performs slightly better on desktop than on mobile. This is in regards to rendering the images used on the site.

## Deployment

The site was deployed using GitHub. The steps for deployment are as follows:

1. Navigate to repository for GitHub project.
2. Navigate to settings tab.
3. Navigate to page settings under **Code and automation**.
4. Under "Build and deployment" select **Deploy from branch** as source.
5. Ensure the main branch is selected and click save.
6. After these steps have been completed, the page should go live within a few minutes.
7. Your live project will be viewable from http://**your-username**.github.io/**your-project-title**/

## Credits

I would like to thank my mentor [Simen Daehlin](https://github.com/Eventyret "Simen Daehlin") for all his advice. For helping me with how to start/structure my project, optimise my code and for the encouragement to give me confidence in my abilities. 
