# Keyboard Shortcuts

The site is intended for users who wish to learn and contribute Keyboard Shortcuts.  The site helps to improve their speed and accuracy of typing while coding.   

The live link can be found here - [Keyboard Shortcuts]( https://dmascoredeclan.github.io/keyboard-shortcuts/)

The site has 5 pages.  Only 4 of the pages are visible from the Nav Bar.  
dummy-page.html, simulates someone leaving the site after REGISTERING and clicking on an email verification link to be brought back to the site to LOGIN.

I wanted the site to be a bit whimsical and playful in terms of colours and I wanted to demonstrate my ability to make the site responsive.

What I learned from this project is that DESIGN is the key to rapid development.  Once you know what you're trying to achieve, its much easier to code the HTML and CSS.  I also learned, keep it simple.

The last update to this file was: **June 12th, 2023**

## Site Owner Goals 
- To provide the user with information about how to use static Keyboard Shortcuts instead of using a Mouse and Screen. 
- To provide the user with clear instructions on how to complete learn and use shortcuts while typing/programming
- To create a community that contributes to the body of knowledge

## User Stories
### First time user
  - As a first time user I want to understand how the simultaeneous pressing of keys can quickly produce an outcome that takes five or six times longer to produce using the Mouse and Screen.
  - As a first time user I want to be able to intuitively navigate the website and have a positive emotional experience. 
  - As a first time user I want to be able to browse keyboard shortcuts content without having to disclose my details through register.

### Registered User / Contributor
  - As a returning user I want to have access to more than the most recent shortcuts contributed by others.    
  - As a returning user I want to be able to contribute keyboard shortcuts for additional application to help others use keyboard shortcuts.



## Design

### Imagery
I wanted the Hero image to help Users equate the physical keyboard with the intended Shortcut.  I used screenshots of specific part of the Hero image to visually demonstrate the shortcut and then repeated the shortcut with keylike buttons, styled with CSS.  This allowed the Shortcuts page to be more densely populated with tips by only showing keylike buttons instead of having to create screenshots for subsequent shortcuts.

### Colours
The colour scheme of the website is bubble-gum pink, lime green and light blue.  These colours represent playfulness.  I wanted fixed Nav-Bars and Footers to facilitate constant easy navigation.

### Fonts
The Titillium Web font is the main font used throughout the whole website. This font was imported via [Google Fonts](https://fonts.google.com/). I used Sans Serif as a backup font, in case for any reason the main font isn't being imported into the site correctly.

### Wireframes
Wireframes were produced using Balsamiq. 

 <details>

 <summary>Desktop Wireframe</summary>

![Desktop Wireframe](/.devcontainer/docs/README-images/kbs-wireframe-desktop.png)
 </details>

 <details>
    <summary>Mobile Wireframe</summary>

![Mobile Wireframe](/.devcontainer/docs/README-images/kbs-wireframe-mobile.png)
 </details>



## Keyboard-Shortcuts Features:
This site has a home page that gives a taste of they types of screenshots that are helpful.  However, it encourages you to Contribute by having a Register and a Login page.  Features that I would like to have but am currently unable to code are the ability for someone to contribute a Shortcut Tip through a form that would be displayed on the HOME page in the format of the current Home Page.

### Navigation

 - The fully responsive navigation bar includes links to the Logo, Home, Register, Login and Shortcuts on separate pages.
 - All pages have a Fixed Nav-Bar and Footer.  The background space between the top and bottom remains white with the exception of the Hero image.
 - The current page is denoted by emphasising the active portion of the Nav-Bar
 - When hovering over subsequent Page choices, that page link underlines and becomes bold

### The Landing Page Image
 - The landing page includes a wonderfully playful image of a keyboard and six articles with a catchy phrase, a colourful shortcut image and text describing in words how to use the shortcut.  The purpose was to link the idea of the keyboard with the shortcut, then introduce the standard symbology of keyboard shortcuts so that in the Shortcuts page, the symbology could be used exclusively.
 - The CSS nth-of-type was used to cycle through pink, blue and green for the Heading, Content and Border

### Register
 - a simple four field input form, styled consistent with the Home page using html validation.
 - Once you hit REGISTER, the page brings you to a simulation of clicking on a VERIFICATION link to validate your email address.
 - Upon validating your address, the site brings you to the Login page.

### Login
 - a simple two field input form, styled consistent with the Home page using html validation.
 - Pressing LOGIN brings you to a Shorcuts page with much more shortcuts
 - Pressing REGISTER returns you to the Register page

### Shortcuts
 - a two column table with Shortcuts styled like keys on the left.  The left column is sorted by alphabetical order and the right column describes the outcome of using the shortcut

### Footer
 - Hovering over the Footer icons, represented by Font-Awesone icons, enlarges them 
 - The footer section includes links to Keyboard Shortcuts Facebook, LinkedIn, Youtube and Instagram pages.
 - The links will open to a new tab to allow easy navigation for the user. 
 - The footer facilitates users to find and follow Keyboard Shortcuts on social media

### Features Left to Implement
- Burger button for the mobile nav bar.
- A CONTRIBUTE page that allows registered users to add a shortcut that would remain on the home page until its displaced by 6 more recent contributions.





## Keyboard-Shortcuts Validations:
![Am I Responsive](/.devcontainer/docs/README-images/kbs-am-i-responsive.png)


<details> 
<summary>Lighthouse Score: </summary>  

![Lighthouse Score](/.devcontainer/docs/README-images/kbs-lighthouse-score.png) 
</details> 


## Accessibility improvement
The colour pickers support these colours working together and were colour picked from the original HERO Keyboard Image.  

### HTML Validation Results:
This is my Code Institute Project 1 assignment.  This sites 5 pages have been validated with (https://validator.w3.org/).  

<details> 
<summary>index.html</summary>  

![Index Score](/.devcontainer/docs/README-images/kbs-index-validation.png) 
</details> 


<details>
<summary>register.html</summary>

![register](/.devcontainer/docs/README-images/kbs-register-validation.png)
</details>

<details>
<summary>login-page.html</summary>

![login-page](/.devcontainer/docs/README-images/kbs-login-page-validation.png)
</details>

<details>
<summary>dummy-page.html</summary>

![dummy-page](/.devcontainer/docs/README-images/kbs-dummy-page-validation.png)
</details>

<details>
<summary>references.html</summary>

![references](/.devcontainer/docs/README-images/kbs-references-validation.png)
</details>


### CSS Validation Results:

Here are the results for the CSS Validation: 

<details>
<summary>CSS</summary>

![CSS](/.devcontainer/docs/README-images/kbs-css-validation.png)
</details>


## Testing
Manual testing has enusred that the FORMs work at all viewport sizes and that HOVERing on the footer elements works when there is a seperate physical keyboard, (HOVERing does not feature with touch screens).  
Tests were carried out on Chrome, Bing, Firefox at multiple different viewport sizes. 

## Bugs
There are no remaining bugs as far as I can identify.  Bugs that arose throughout were primarily around the use of FLEX, which took me 2 weeks to conquer.  Other bugs were, the incorrect relative referencing and incorrect case sensitivity for the PNGs in the site.

## Credits:
### Content
- Table contents for references.html were taken from: https://www.computerhope.com/shortcut.htm
- The Hero Image was taken from https://matrixkeyboards.com
### Other Resources Used
- [Love running and Coders Coffee House](https://codeinstitute.net/ie/)
- [Content and Inspiration](https://natureofwriting.com/courses/essay-writing/lessons/the-writing-process/topic/keyboard-shortcuts/)

- [Mozilla](https://developer.mozilla.org/)
- [Font Awesome](https://fontawesome.com/)
- [Google Fonts](https://fonts.google.com/)
- [W3Schools](https://www.w3schools.com/)
- [Stack Overflow](https://stackoverflow.com/)

### Acknowledgments
My mentor Antonio for his support and advice.

The Code Institute slack community for their quick responses and very helpful feedback!