# Udacity Feed Reader Project

## Introduction

From this site you can view the news on 4 interesting web pages. The application gathers news from the sites using a Feedreader through a Google API.

## Running the application

To run the Feedreader simply start the index.html file - it will be loaded in your default browser

## What feeds are being fed to me here?

You'll get news on:
1. The Udacity blog
2. CSS Tricks
3. HTML5 Rocks
4.Linear Digressions

## What tests are run?

There are a total of four test suites. One for the RSS feeds themselves,one for testing the Menu, one for the initial entires, and one for the content changes (new feed selection).

### Tests in the RSS feed

1. Test if the allFeeds variable is defined and is not empty.
2. A test that loops through each feed in the allFeeds object and ensures it has a URL defined and that the URL is not empty.
3. A test that loops through each feed in the allFeeds object and ensures it has a name defined and that the name is not empty.
### Tests in the Menu

1. A test that ensures the menu element is hidden by default.
2. A test that ensures the menu changes visibility when the menu icon is clicked.

### Tests for Initial Entries

1. A test that ensures when the loadFeed function is called and completes its work, there is at least a single .entry element within the .feed container.

### Tests for new Feed Selection (content changes)

1. A test that ensures when a new feed is loaded by the loadFeed function that the content actually changes.
 
## Contributing

This Project does not accept contributing at the moment as it is a test to test my testing skills.


