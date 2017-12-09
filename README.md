![CF](https://camo.githubusercontent.com/70edab54bba80edb7493cad3135e9606781cbb6b/687474703a2f2f692e696d6775722e636f6d2f377635415363382e706e67) Lab 03: jQuery Events
===

## Code Wars Challenge

Complete [today's Kata](https://www.codewars.com/kata/insert-dashes) and follow the submission instructions from Lab 01.

## Lab 03 Submission Instructions
Follow the submission instructions from Lab 01.

## Resources  
[jQuery cheatsheet](https://oscarotero.com/jquery/)

[Template Literals MDN](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Template_literals)

## Configuration
_Your repository must include:_

```
03-jquery-with-events
└──driver-navigator
  ├── .eslintrc.json
  ├── .gitignore
  ├── LICENSE
  ├── README.md
  ├── index.html
  ├── scripts
  │   ├── article.js
  │   ├── articleView.js
  │   └── blogArticles.js
  ├── styles
  │   ├── base.css
  │   ├── layout.css
  │   └── modules.css
  └── vendor
      └── styles
          ├── fonts
          │   ├── icomoon.eot
          │   ├── icomoon.svg
          │   ├── icomoon.ttf
          │   └── icomoon.woff
          ├── icons.css
          └── normalize.css
```

## User Stories and Feature Tasks

*As a user, I want to be able to filter my articles so that I can selectively view articles by author or by category.*

- Complete the new requirements for setting `data-<attributes>` in your `toHtml()` method.
- Complete the methods for handling filter events when selecting an option from a drop down menu via Authors and Categories so that only the selected articles are displayed on the screen.

*As a user, I want to be able to preview each article so that I can easily view the results and select the one I want to read further.*

- Add an event to reveal a complete article if the user would like to see more of it beyond the teaser.

*As a user, I want tab-based navigation so that I can easily visit other sections of my site.*

- Complete the method `articleView.handleMainNav()` for implementing tab-based event navigation on the page.

*As a developer, I want my code to be thoughtfully organized, easy to read, and executing efficiently.*

- Review and understand the new JS file, `articleView.js`
- Add any new script tags to your HTML.
- Refactor concatenation using template literals.
- Render the app upon page load.

### Stretch Goal

*As a user, I want to be able to collapse an expanded article to the teaser view so that I can more easily scan over a series of articles.*

- Build in functionality such that a user can click on "Show Less" to collapse a full article into a teaser.

## Documentation
_Your README.md must include:_

```md
##JQUERY AND EVENTS 
AUTHORS: Alicia Lycan & Tiger Hsu

**Version**: 1.0.0

## Overview

To create a way to be able to filter articles so they can selectively viewed by author or category. Then
add ability to preview each article to easily view each results and select one to read further.
Create tab-based navigation to view diffrenet sections of site.

## Getting Started

1. Make a copy of the starter code and rename it with your name.
2. Next, open the html file and add scripts.
3. Next, open .js files and complete TODO and response items.
4. Open in browser and confirm responsiveness to see if code if functional.
5. Upload final edits to git-hub. 

## Architecture

The application uses basic HTML, CSS, JavaScript, DOM manipulation, and JQuery.

## Change Log

12-07-2017 6:00pm - Completed file setup, and articleView.js TODOs.

12-07-2017 9:00pm - Added hide/show methods and complete articleView.js responses.

12-09-2017 11:00am - Application has fully responsive design. 


## Credits and Collaborations

This application was pair programmed by Alician Lycan and Tiger Hsu.
