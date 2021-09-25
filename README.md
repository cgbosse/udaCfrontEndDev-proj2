# Project Description - Udacity Project 2 - Dynamic Landing Page

Description adapted from the Udacity Project Specifications - https://review.udacity.com/#!/rubrics/2658/view
<br>

This project requires me to build a multi-section landing page, with a dynamically updating navigational menu based on the amount of content that is added to the page. I am to use js in combination with HTML and CSS.<br>
<br>

# Rubric

## Interface and Architecture
<br>

CRITERIA | MEETS SPECIFICATIONS
-------------- | -------------------------------
Architecture | The project structure should be like the one shown below. All files shown must be present and the app must successfully render a home page with clear design and functionality added when index.html is loaded in the browser. No errors should display in console.

``` 
/css
- styles.css    
/js
- app.js
index.html
README.md
```
CRITERIA | MEETS SPECIFICATIONS
-------------- | -------------------------------
Usability | All features are usable across modern desktop, tablet, and phone browsers.
Styling | Styling has been added for active states.
HTML Structure | There are at least 4 sections that have been added to the page.<br>
<br>  

## Landing Page Behavior

CRITERIA | MEETS SPECIFICATIONS
-------------- | -------------------------------
Navigation | Navigation is built dynamically as an unordered list. Start with empty ul and dynamically build navigation using Append, appendChild, and innerHTML.
Section Active State | It should be clear which section is being viewed while scrolling through the page.
Scroll to Anchor | When clicking an item from the navigation menu, the link should scroll to the appropriate section.

<br>

## Documentation

CRITERIA | MEETS SPECIFICATIONS
-------------- | -------------------------------
README | The ReadMe file should replace the given texts on the README template with specific information for this project. It doesn’t have to be thorough, but should have some basic information, eg. project description, usage, dependencies, and use correct the markdown syntax. <br> *[References: markdown guide and example of README contents](https://www.markdownguide.org/basic-syntax/)*
Comments | Comments are present and effectively explain longer code procedures as described in the [Udacity JavaScript Style Guide - Comments](http://udacity.github.io/frontend-nanodegree-styleguide/javascript.html#comments).
Code Quality | Code is formatted with consistent, logical, and easy-to-read formatting as described in the [Udacity JavaScript Style Guide - Code Formatting](http://udacity.github.io/frontend-nanodegree-styleguide/javascript.html#formatting).

<br>
<br>
<br>

## Suggestions to Make Your Project Stand Out!

```
* Add an active state to your navigation items when a section is in the viewport.
* Hide fixed navigation bar while not scrolling (it should still be present on page load).<br>
            *Hint: setTimeout can be used to check when the user is no longer scrolling.*   
* Add a scroll to top button on the page that’s only visible when the user scrolls below the fold of the page.
* Update/change the design/content.
* Make sections collapsible.
```
