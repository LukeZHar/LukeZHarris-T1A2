# LukeZHarris-T1A2

**Written and published by _Luke Harris_**

[Link to my published portfolio website](https://lukezharris-t1a2.netlify.app/)

[Link to my github repository](https://github.com/LukeZHar/LukeZHarris-T1A2)

# Description

## Purpose

The purpose of this website is to showcase my coding abilities at this point in the course by creating a portfolio website.
It will also be used to attract future employers after I have completed the course and have added more to the site with real blogs and projects.

## Functionality / features

### HTML:5 (HyperText Markup Language)

The whole website is coded with HTML:5 using semantics (very few div).

- The use of < header >, < footer >, and < main > to define the sections of code
  - Inside of the < body >
- The use of < h1 >, < h2 >, < h3 > and < h4 > to create different sizes of heading
- The use of < nav > for my navbar
- The use of < section > to create my groups of code.
- The use of id="" and class="" thoughout to easily link to my CSS styling code.
- The use of src="" and href="" to link in websites, images and CSS styling.
  - Used inside < Link >, < img > and < a >.
- The use of < ul > and < li > for making unordered lists.
- The use of < Strong > and < em > to make a bold and italic style.
- The use of < form > for creating my forms.
  - Used < input > and < label > to make my input bubbles and text on the contact page
- The use of < button > for creating my buttons on my about, blog and contact page
- The use of < article > for my blog posts
- The use of < i > for the icons brought over from **fontawesome**
- The use of < p > for writing my paragraphs

### CSS (Cascading Style Sheets)

The whole website is Styled through the use of CSS. The styling code is linked to the HTML elements.

1. A base style.css page was created for the Header, footer and all the elements inside.
2. Then overriding .style pages were created for each indiviual page.

- The Display used was Flexbox to keep my styling the same across all pages.
- The use of @import for bringing in a font
  ![import screenshot](./docs/Features/import.png)
- The use of @media to change the styling depending on the use of phone, ipad and desktop, started with mobile first.  
  ![media screenshots](./docs/Features/Media%20screen%20mid%20range.png)  
  ![media screenshots](./docs/Features/media%20screen%20large.png)
- The use of @keyframes for making animations
  ![keyframes screenshot](./docs/Features/keyframes.png)
- The use of :root for storing my different colors that i can access through var()
  ![Root code](./docs/Features/Root%20content.png)
- The use of (\*) for storing my box-sizing and font
  ![Font and box-sizing](./docs/Features/starcode.png)
- (#) linking to my id="" and (.) linking to my class=""
- The use of :hover to change the style when hovering ontop of the element  
  ![Hover code](./docs/Features/logo%20hover%20code.png)

### Components

#### Header

Is the top part of the page the holds the navbar and logo that users use to navigate through the pages.

Mobile view  
![Header for moble](./docs/Layout/Header%20mobile.png)

Desktop view  
![Header for Desktop](./docs/Layout/Header%20big.png)

- #### Navbar

  ![Navbar](./docs/Features/Navbar.png)

- #### Navbar link code

  ![navbar link code](./docs/Features/Navbar%20link%20code.png)

- #### Navbar hover

  ![navbar hover](./docs/Features/navbar%20hover.png)

- #### Navbar hover code

  ![navbar hover code](./docs/Features/navbar%20hover%20code.png)

- #### Logo

  ![logo](./docs/Features/linked%20logo.png)

- #### Logo link code

  ![logo link code](./docs/Features/Logo%20link%20code.png)

- #### Logo hover

  ![logo hover](./docs/Features/Logo%20hover.png)

- #### Logo hover code
  ![logo hover code](./docs/Features/logo%20hover%20code.png)

#### Body

A small snippit of the background image that will be used across the whole site and some flexbox code  
![Background image](./docs/Features/Background%20image.png)

- #### Background image and flexbox code

  ![Background image and flex code](./docs/Features/background%20image%20and%20flexbox.png)

- #### Flexwrap code for blog and project's
  ![Flexwrap code](./docs/Features/Flex%20wrap.png)

#### Footer

Is the bottom part of the page that users can find the social links, address/mobile, copyright info and back to top shortcut

Mobile view  
![footer mobile view](./docs/Layout/Footer%20mobile.png)

Destop view  
![footer desktop view](./docs/Layout/Footer%20big.png)

- #### Icons

  ![icon screenshot](./docs/Features/Linked%20icons.png)

- #### Icon link code

  ![icon link code](./docs/Features/Logo%20link%20code.png)

- #### Icon hover

  ![icon hover](./docs/Features/linked%20icons%20hover.png)

- #### Icon hover code

  ![icon hover code](./docs/Features/linked%20icons%20hover%20code.png)

- #### Back to top

  ![back to top](./docs/Features/Back%20to%20top.png)

- #### Back to top code
  ![back to top code](./docs/Features/Back%20to%20top%20code.png)

#### Home

The main page that visiters will start at, which will have a fade in and typing animation to catch their attention, with a picture of me and a brief paragraph about me and my current studies.

Home page mobile view  
![home page mobile screenshot](./docs/Layout/home%20mobile.png)

Home page Desktop view  
![home page mobile screenshot](./docs/Layout/home%20big.png)

- #### Homepage Fade-in Animation

  ![Fade-in animation half fade](./docs/Features/Fade-in%20effect.png)  
  ![Fade-in animation end](./docs/Features/fade-in%20effect%20end.png)

- #### Homepage Typing Animation

  ![Typing animation halfway](./docs/Features/Typewriter%20effect.png)  
  ![Typing animtion end](./docs/Features/Typewriter%20effect%20complete.png)

- #### Homepage Animation code
  ![Fade-in animation code](./docs/Features/Animation%20fade-in.png)  
  ![Typerwriter animation code](./docs/Features/Animation%20typing.png)  
  ![Animation code](./docs/Features/Fade-in%20and%20typing%20effect%20link%20code.png)

#### About

This page will have a picture of me along side an about me section that will have a brief description, Interests, Skills, Tools, Certificates, Work history and my Resume. I added some icons, because I personaly think it attracts attention to the lists.

About page mobile view  
![About page mobile view](./docs/Layout/about%20mobile.png)

About page Desktop view  
![About page Desktop view](./docs/Layout/about%20page%20big.png)

- #### Resume button

  ![Resume button](./docs/Features/Resume%20button.png)

- #### Resume button hover

  ![Resume button hover](./docs/Features/Resume%20hover.png)

- #### Resume button hover code
  ![Resume hover code](./docs/Features/Resume%20hover%20code.png)

#### Blog

This page will have 5 blogs with a different heading on each but lorem for the description, a read more button and 1 image. I added a hover effect to the button so visitors can see where they are clicking and catches their attention.

Blog page mobile view  
![Blog page mobile view](./docs/Layout/blog%20mobile.png)

Blog page desktop view  
![Blog page Desktop view](./docs/Layout/Blog%20big.png)

- #### Read more button

  ![Read more button](./docs/Features/read-more%20button.png)

- #### Read more button hover

  ![Read more button hover](./docs/Features/read-more%20hover.png)

- #### Read more button hover code

  ![Read more button hover code](./docs/Features/Read-more%20hover%20code.png)

- #### Blog-page

  Once read more is clicked it will take you to this page which is just a basic blog page with a background, text and image.

  Blog post mobile view  
   ![Blog post mobile view](./docs/Layout/blog-page%20mobile.png)

  Blog post desktop view  
   ![Blog post Desktop view](./docs/Layout/blog-post%20big.png)

#### Project's

This page will have a circular look to the projects outlined with no links just 1 image and a title.

Project's page Mobile view  
![Project's page mobile view](./docs/Layout/projects%20mobile.png)

Project's page Desktop view  
![Project's page Desktop view](./docs/Layout/Projects%20big.png)

#### Contact

This page will have my email and a form visiters can fill out to get into contact with me, and a submit button that links to a thank you page. The submit page has a hover effect attached and the input has a box shadow and scale effect.

Contact page mobile view  
![Contact page mobile view](./docs/Layout/Contact%20mobile.png)

Contact page Desktop view  
![Contact page Desktop view](./docs/Layout/contact%20big.png)

- #### Form input box shadow

  ![Input box shadow](./docs/Features/background%20shadow.png)

- ### Form input focus code

  ![Input box code](./docs/Features/Focus%20form%20input%20code.png)

- #### Submit button

  ![Submit button](./docs/Features/submit%20button.png)

- #### Submit button hover

  ![Submit button hover](./docs/Features/submit%20hover.png)

- #### Submit button hover code

  ![Submit button hover code](./docs/Features/Submit%20hover%20code.png)

- #### Thank you

  This page will have an animated colourful thank you text with a colorful border and scale up and down. Animation catches the eye.

  Thank you small view  
   ![Thank you small animation](./docs/Layout/thank%20you%20small.png)

  Thank you mid view  
   ![Thank you mid animation](./docs/Layout/Thank%20you%20mid.png)

  Thank you large view  
   ![Thank you large animation](./docs/Layout/Thank%20you%20larger.png)

  - #### Thank you animation code
    ![Linked thank you code](./docs/Features/Linked%20animation%20colorful-text.png)  
    ![Thank you animation code](./docs/Features/Animation%20colourful-text.png)

# Screenshots

## Sitemap

![A screenshot of my sitemap from draw.io](./docs/Sitemap/Sitemap%20for%20T1A2.png)

My core 5 pages (Home, About, Blog, Project's and contact) will be linked together through a nav bar so it's easy to navigate from one page to the next.
![A screenshot of my navbar desktop](./docs/Features/Navbar.png)

The logo at the top will link back to the _**Home page**_.  
![A screenshot of my logo](./docs/Features/linked%20logo.png)

Resume will be accessable through the about page by clicking the _**Resume**_ button.  
![A screenshot of my Resume button](./docs/Features/Resume%20button.png)

Blog post will be accessable through the blog page by clicking the _**Read More**_ button.  
![A screenhot of my Read-more button](./docs/Features/read-more%20button.png)

Thank you page will only be accessable through the contact page by clicking the _**Submit**_ button.  
![A screenshot of my submit button](./docs/Features/submit%20button.png)

## Wireframes

My decision making progress for my website aesthetic was a more sleek design I wanted all my pages to have the same theme of header, footer and background.  
I chose a dark and light theme as a personal preference, I enjoy how light and dark come together to make each other stand out.
I did add a spash of color in the text and image choices to really make it **POP**.

#### Homepage

![A screenshot of my Homepage wireframe](./docs/Wireframe/Home%20page.png)

#### About page

![A screenshot of my About page wireframe](./docs/Wireframe/About%20page.png)

#### Blog page

![A screenshot of my Blog page Wireframe](./docs/Wireframe/Blog.png)

- #### Sub Blog post page
  ![A screenshot of my Blog post page Wireframe](./docs/Wireframe/Blog-post.png)

#### Project's page

![A screenshot of my Project's page Wireframe](./docs/Wireframe/Projects%20page.png)

#### Contact page

![A screenshot of my Contact page Wireframe](./docs/Wireframe/Contact%20page.png)

- #### Sub Thank you page Animation normal
  ![A screenshot of my Thank you page normal Wireframe](./docs/Wireframe/Thank-you%20page%20animation%20normal.png)
- #### Sub Thank you page Animation Scaled
  ![A screenshot of my Thank you page zoomed Wireframe](./docs/Wireframe/Thank-you%20page%20animation%20zoom.png)

## Trello

I found Trello to be incredibly useful in keeping myself in line with completeing work by setting dates and making checklists for inline items that need to be completed for each page

- #### Trello Board start

  ![A screenshot of my Trello board 20th May](./docs/Trello%20board/Trello%2020th%20may.png)

- #### Trello Board end

  ![A screenshot of my Trello board 1st June](./docs/Trello%20board/Trello%20board%201.6.png)

- #### Trello Board Checklist
  ![A screenshot of my Trello board Checklist](./docs/Trello%20board/Trello%20checklist.png)

## Target audience

This content is designed to be viewed by **Coder Academy** for my T1A2 assessment.  
In the future to be viewed by **Employers** after I fix it up when completing the course.

## Tech stack (e.g. html, css, deployment platform, etc)

The tech stacks used in this portfolio include:

Tools:

- VSCode for writing the HTML code and designing with CSS.
- Github repository for storing my commited work.
- Netlify for deploying the final website.

Code:

- HTML:5
- CSS

# Refrences

### Websites used

[Link to AIT student portal](https://ait.instructure.com/)

[Link to Canva](https://www.canva.com/)

[Link to CDNjs](https://cdnjs.com/libraries/font-awesome)

[Link to colorkit](https://colorkit.co/contrast-checker/a7bfed-262626/)

[Link to Draw.io](https://app.diagrams.net/)

[Link to ED](https://edstem.org/)

[Link to Favicon](https://favicon.io/favicon-generator/)

[Link to Figma](https://www.figma.com/)

[Link to Fontawesome](https://fontawesome.com/icons)

[Link to Github](https://github.com/)

[Link to Google fonts](https://fonts.google.com/)

[Link to Netlify](https://app.netlify.com/)

[Link to Trello](https://trello.com)

Background image reference: Photo by Alexandru Acea on Unsplash

Blog image reference: Photo by Pankaj Patel on Unsplash
