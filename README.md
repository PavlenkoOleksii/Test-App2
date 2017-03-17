# Web-app queries a github service API
Works as rest for geting data from GitHub (front-end AngularJS back-end Node.js)
Navigation implemented with Angular UI router. 
Web-app queries a github service API (https://developer.github.com/v3/repos/) for repositories catalog content, 
parses the JSON-formatted response and displays the data.  
The data consists of a list of repositories. 
Each list item interactive 
a. Button for showing contributors list, in another view, with possibility to go back.
b. Button to mark/unmark repository as favorite. This info available after page reloads with the using cookie.
