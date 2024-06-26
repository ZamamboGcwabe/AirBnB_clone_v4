Resources
Read or watch:

Selector
Get and set content
Manipulate CSS classes
Manipulate DOM elements
Document ready
Introduction
GET & POST request
HTTP access control (CORS)
Learning Objectives
At the end of this project, you are expected to be able to explain to anyone, without the help of Google:

General
How cool it is to request your own API
How to modify an HTML element style
How to get and update an HTML element content
How to modify the DOM
How to make a GET request with JQuery Ajax
How to make a POST request with JQuery Ajax
How to listen/bind to DOM events
How to listen/bind to user events
Requirements
General
Allowed editors: vi, vim, emacs
All your files will be interpreted on Chrome (version 57.0)
All your files should end with a new line
A README.md file, at the root of the folder of the project, is mandatory
Your code should be semistandard compliant with the flag --global $: semistandard *.js --global $
All your JavaScript must be in the folder scripts
You must use JQuery version 3.x
You are not allowed to use var
HTML should not reload for each action: DOM manipulation, update values, fetch data…
GitHub

More Info
Import JQuery
<head>
    <script src="https://code.jquery.com/jquery-3.2.1.min.js"></script>
</head>
Before starting the project…
You will work on a codebase using Flasgger, you will need to install it locally first before starting the RestAPI:

$ sudo apt-get install -y python3-lxml
$ sudo pip3 install flask_cors # if it was not installed yet
$ sudo pip3 install flasgger
If the RestAPI is not starting, please read the error message. Based on the(ses) error message(s), you will have to troubleshoot potential dependencies issues.

Here some solutions:

jsonschema exception
$ sudo pip3 uninstall -y jsonschema 
$ sudo pip3 install jsonschema==3.0.1
No module named 'pathlib2'
$ sudo pip3 install pathlib2
