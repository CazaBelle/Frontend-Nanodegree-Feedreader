# Project Overview

This project is a demonstration on how to test an RSS Feed Reader JavaScript application using the Jasmine framework.
The application being tested is an [RSS Feed Reader provided by Udacity] (https://github.com/udacity/frontend-nanodegree-feedreader). 

# Installation
After downloading this repository, launch the index.html file. It will open up in your predefined browser and automatically run the tests. When the tests finish running, scroll down to the bottom of the page to see the results. 

# Tests Included
The tests included are the following:

1. RSS Feeds
..* Ensure that the RSS feeds are defined.
..* Ensure that each feed has a defined, non-empty URL.
..* Ensure that each feed has a defined, non-empty name.

2. Menu
..* Ensure the menu is hidden by default.
..* Ensure that clicking on the menu icon shows the menu.
..* Ensure that clicking on the menu icon again hides the menu.

3. Initial Entries
..* Ensure that each feed contains at least one feed entry.

4.New Feed Selection
..* Ensure that switching to a new feed actually changes the content.

# How to complete this project?

Review the Feed Reader Testing [Project Rubric](https://review.udacity.com/#!/projects/3442558598/rubric)

1. Take the JavaScript Testing [course](https://www.udacity.com/course/ud549)
2. Download the [required project assets](http://github.com/udacity/frontend-nanodegree-feedreader).
3. Review the functionality of the application within your browser.
4. Explore the application's HTML (**./index.html**), CSS (**./css/style.css**) and JavaScript (**./js/app.js**) to gain an understanding of how it works.
5. Explore the Jasmine spec file in **./jasmine/spec/feedreader.js** and review the [Jasmine documentation](http://jasmine.github.io).
6. Edit the `allFeeds` variable in **./js/app.js** to make the provided test fail and see how Jasmine visualizes this failure in your application.
7. Return the `allFeeds` variable to a passing state.
8. Write a test that loops through each feed in the `allFeeds` object and ensures it has a URL defined and that the URL is not empty.
9. Write a test that loops through each feed in the `allFeeds` object and ensures it has a name defined and that the name is not empty.
10. Write a new test suite named `"The menu"`.
11. Write a test that ensures the menu element is hidden by default. You'll have to analyze the HTML and the CSS to determine how we're performing the hiding/showing of the menu element.
12. Write a test that ensures the menu changes visibility when the menu icon is clicked. This test should have two expectations: does the menu display when clicked and does it hide when clicked again.
13. Write a test suite named `"Initial Entries"`.
14. Write a test that ensures when the `loadFeed` function is called and completes its work, there is at least a single `.entry` element within the `.feed` container.
15. Write a test suite named `"New Feed Selection"`.
16. Write a test that ensures when a new feed is loaded by the `loadFeed` function that the content actually changes.
17. No test should be dependent on the results of another.
18. Callbacks should be used to ensure that feeds are loaded before they are tested.
19. Implement error handling for undefined variables and out-of-bound array access.
20. When complete - all of your tests should pass. 
21. Write a README file detailing all steps required to successfully run the application. If you have added additional tests (for Udacious Test Coverage),  provide documentation for what these future features are and what the tests are checking for.
