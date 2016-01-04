# Project Overview

A web-based application that reads RSS feeds.


## How to run this Project?

Run python -m SimpleHTTPServer 8080 or simly open the index.html in your browser.

## Performed Tests
 * Tests following: 
 * RSS Feeds
 *          are defined
 *          have defined and non-empty URLs
 *          have defined and non-empty Names
 * The menu
 *          is hidden by default
 *          changes visibility when the menu icon is clicked
 * Initial Entries
 *          has entry
 *          New Feed Selection
 *          changes the content
 
# Steps taken to complete the project

1. Returned the allFeeds variable to a passing state.
2. Wrote a test that loops through each feed in the allFeeds object ensuring it has a URL defined and that the URL is not empty.
3. Wrote a test that loops through each feed in the allFeeds object ensuring it has a name defined and that the name is not empty.
4. Wrote a new test suite named "The menu".
5. Wrote a test that ensures the menu element is hidden by default. 
6. Wrote a test that ensures the menu changes visibility when the menu icon is clicked. 
7. Wrote a test that ensures when the loadFeed function is called and completed its work.
8. Wrote a test that ensures when a new feed is loaded by the loadFeed function that the content actually changes. 
9. All tests are passing.
