# Defiso webpage
This webpage is built on top of the Adobe Business Catalyst platform. The easiest way to 
create a working copy is by using the partner portal tools. Please contact [Novium](http
://noviumdesign.se) for a isolated copy.

Most of the code can whoever be accessed by the web UI. Installing tracking-codes etc.

## Dependencies
1. Ruby
2. Compass
3. Sass
4. Bower
5. Foundation globally installed

## How to make changes?
The basic rule is that all .js and .css is compiled locally and uploaded to server by sFTP. 
Please DO NOT edit CSS or JS on server. It will be overwritten in build. All code for forms 
is pasted in the app.js file.

Please make sure that this code is added before ```</body>``` to all pages where forms are 
used.

```<script src="//defiso.worldsecuresystems.com/CatalystScripts/ValidationFunctions.js"></script>```

Use $```compass watch``` to watch for changes and build css.
