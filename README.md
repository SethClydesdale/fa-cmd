# FA CMD

This project aims to develop a simple command-line tool for Forumotion forums that will allow you to perform certain tasks with ease. The command tool is embedded in an HTML page and then opened in a new window via a link of your choosing. If you have a Forumotion forum and wish to test this tool out feel free to follow the installation instructions below.

## Installation
To install the command interpreter go to your Admin Panel > Modules > HTML Pages Management > New 

Title : FA CMD

Do you wish to use your forum header and footer ? : YES

Use this page as homepage ? : NO

Then paste [this file](https://raw.githubusercontent.com/SethClydesdale/fa-cmd/master/cmd.html) into the HTML page source and click submit.

After it's save go to the page and copy the URL from the addressbar ( or the path for that matter ; e.g. /h1- ), then go to Display > Headers and Navigation > New Menu

Name the link what you like and set the permissions as you wish. However, make sure to paste the following into the redirection URL.
```javascript
javascript:window.open('/h7-','_blank','height=300,width=800');
```
Just make sure to replace the **7** with your HTML page ID. After this you can access the command tool from anywhere you want.

## Demo
![](http://i68.servimg.com/u/f68/18/45/41/65/captur10.gif)
