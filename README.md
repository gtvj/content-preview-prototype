# Content preview prototype

Quick and dirty prototype demonstrating how a content preview might work in a multi-page format. This is definitely not 
production quality frontend code but I'm confident this approach would be robust (working across screen resolutions etc.)
as well as compatible with WCAG.

## Overview

There are three pages: 

* "What branch would you like to view" allows users to enter a branch with autocomplete functionality provided through `<datalist>`
* "What page would you like to view" allows users to select the page (again using `<datalist>`)
* "Content viewer" simulates the rendering of a single page within an `iframe` (hard-coded as the Accessibility Statement for the time-being). This basic viewing implementation could be enhanced - potentially by applying JavaScript through [progressive enhancement](https://www.gov.uk/service-manual/technology/using-progressive-enhancement) - to provide additional functionality (such as switching to another branch, page or language).

## Getting up and running

* Install dependencies with `npm install`
* Run a development server with `npm run dev`
* Visit `localhost:3002`