# Project Description
This repository was created from an old hw assignment. The idea is to create a stub of a website that can be 
used with WebStorm to work with Bootstrap, SASS(SCSS), BrowserSync, GULP, GitHub Pages, and web templates 
with partial html files. Cloning this repository will allow one to build a project with these tools and 
view it live in the browser. HTML snippets for your header, footer, and main menu will be included as 
partials with each web page (made in the src folder) and when the site is saved/built it will automatically 
add the same bit of html to the version of the page created in the docs folder. Browser sync will update 
the version in docs and your browser without having to press the refresh button.

This stub was based off the assignment created by Keith Williams and uses the public domain parts listed 
above.

# Prerequisites
1. Install Node.js
2. Read the Gulp article to explain how to install Gulp globally i.e. npm install -g npm install gulp-cli -g on windows or sudo install -g npm install gulp-cli -g on mac

# Install Instructions
1.  Clone the repository in WebStorm
2.  Run npm install to install the dependencies
3.  Add a run configuration for "Gulp" and put in "serve" as an argument

![WebStorm Gulp Config](screenshots/gulp.png)
