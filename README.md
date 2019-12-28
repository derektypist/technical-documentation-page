# Technical Documentation Page

Welcome to the Technical Documentation Page.  The purpose of this project is to provide a technical documentation page
similar to https://codepen.io/freeCodeCamp/full/NdrKKL

## UX

This project is about computing documentation for careers and interests in computing.  Users can select a computing topic (e.g. JavaScript) via the navigation menu.
Further links (e.g. w3schools.com) are provided in the reference section.

Information Architecture of the Computing Documentation.  It is structured into Introduction, HTML5, CSS3, JavaScript, etc.
The Organising Principle is Topics or Interests.

### User Stories

User Stories are taken from https://www.freecodecamp.org/learn/responsive-web-design/responsive-web-design-projects/build-a-technical-documentation-page

As a user, I can see a main element with a corresponding id=main-doc, which provides the main content (technical documentation).

As a user, within the #main-doc element, I can see several section elements, each with a class of main-section.  Minimum of 5.

As a user, I expect the first element within each .main-section should be a header element, 
which contains text that describes the topic of that section.

As a user, I expect each section element with the class of main-section
should also have an id that corresponds with the text of each header contained within it. Any spaces should be replaced with underscores (e.g. The section that contains the header "JavaScript and Java" should have a corresponding id="JavaScript_and_Java").

As a user, I expect the .main-section elements should contain at least 10 p elements total (not each).

As a user, I expect the .main-section elements should contain at least 5 code elements total (not each).

As a user, I expect the .main-section elements should contain at least 5 li items total (not each).

As a user, I can see a nav element with a corresponding id="navbar".

As a user, I expect the navbar element should contain one header element which contains text that describes the topic of the technical documentation.

As a user, I expect Additionally, the navbar should contain link (a) elements with the class of nav-link. There should be one for every element with the class main-section.

As a user, I expect the header element in the navbar must come before any link (a) elements in the navbar.

As a user, I expect each element with the class of nav-link should contain text that corresponds to the header text within each section (e.g. if you have a "Hello world" section/header, your navbar should have an element which contains the text "Hello world").

As a user, when I click on a navbar element, the page should navigate to the corresponding section of the main-doc element (e.g. If I click on a nav-link element that contains the text "Hello world", the page navigates to a section element that has that id and contains the corresponding header.

As a user, On regular sized devices (laptops, desktops), the element with id="navbar" should be shown on the left side of the screen and should always be visible to the user.

As a user, My Technical Documentation page should use at least one media query.

## Features

Fixed Vertical Navigation Bar.  Ability to go to a topic without leaving the web page.

## Technologies

This project uses HTML5, CSS3 (Internal) and Bootstrap 4.4.1.  Other technologies include the font libraries
(e.g. Roboto) at https://fonts.google.com.

