# FeedReader

Download repository to your computer. Open file index.html in a browser.

## Project

This is a project made by Udacity. The application allows you to read RSS feeds of four websites. The websites are:
1. Udacity Blog
2. CSS Tricks
3. HTML5 Rocks
4. Linear Digressions

## Instructions

There is a menu icon in the left up corner. Once you click on it, you'll see the list of all websites you can get articles from. Choose any of the websites and read the list of RSS feed articles. 

## Tests

The application was tested using [Jasmine](http://jasmine.github.io/).

### Next tests were added

1. Test that loops through each feed in the allFeeds object and ensures it has a URL defined and that the URL is not empty.
2. Test that loops through each feed in the allFeeds object and ensures it has a name defined and that the name is not empty.
3. Test that ensures the menu element is hidden by default. You'll have to analyze the HTML and the CSS to determine how we're performing the hiding/showing of the menu element.
4. Test that ensures the menu changes visibility when the menu icon is clicked. This test should have two expectations: does the menu display when clicked and does it hide when clicked again.
5. Test that ensures when the loadFeed function is called and completes its work, there is at least a single .entry element within the .feed container.
6. Test that ensures when a new feed is loaded by the loadFeed function that the content actually changes.

### How to check test results

Download repository to your computer. Open file index.html in a browser. The test results will be displayed at the bottom of the page.
