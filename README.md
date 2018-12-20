# Feed Reader
This is the project for Udacity's [ Front-End Web Developer](https://www.udacity.com/course/front-end-web-developer-nanodegree--nd001) Nanodegree Program. It was developed using HTMl, CSS, and JavaScript. It focuses on browser based testing using [Jasmine](https://jasmine.github.io/).
The starter code was cloned from [ Feed Reader Testing starter code](https://github.com/udacity/frontend-nanodegree-feedreader).

## Table of Contents

- [Project Overview](#project-overview)
- [Dependencies](#dependencies)
- [Installation](#installation)
- [Tests](#tests)

## Project Overview

A web-based application that reads RSS feeds. Jasmine is used to write a number of tests against a pre-existing application. These will test the underlying business logic of the application as well as the event handling and DOM manipulation.


###  Dependencies

- vanilla.js
- JavaScript
- jQuery
- CSS3
- HTML5
- JasmineJS


### Installation

1. Download or clone the repository
```
  - git clone git@github.com:ShaggyT/feed-reader.git
  - cd feedreader
```
2. Open the client folder and right click on ```index.html``` and choose a browser

3. View in your browser



###  Tests

The Jasmine feedreader.js file tests:

1. RSS Feeds Definitions

  - A test to make sure that the 'allFeeds' variable has been defined and that it is not empty.
  - A test that loops through each feed in the allFeeds object and ensures it has a URL defined and that the URL is not empty.
  - A test that loops through each feed in the allFeeds object and ensures it has a name defined and that the name is not empty.


2. Menu

  - A test that ensures the menu element is hidden by default.
  - A test that ensures the menu changes visibility when the menu icon is clicked.


3. Initial Entries

  - A test that ensures when the loadFeed function is called and completes its work, there is at least a single item in the list.


4. New Feed Selection

  - A test that ensures when a new feed is loaded by the loadFeed function that the content actually changes.
