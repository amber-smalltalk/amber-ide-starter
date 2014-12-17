# Amber Smalltalk IDE starter menu

Hidden modal dialog to open Amber IDEs
This is a library to be used within a project.
There is an index.html that demonstrates the functionality.

## How to try

So to just try it, clone it, bower install, amber config, amber serve and point the browser to http://localhost:4000

## How to install into a project

Include as devDependency in your Amber project:

```
bower install amber-ide-starter-dialog --save-dev
```

run ```grunt devel``` to regenerate config, include the loading snippet from README into index.html


`require(['amber-ide-starter-dialog'], function (s) { s.start(); });` 

and see it open itself after amber loads while in development, and just fail it load while in production. 

![Screenshot](Screenshot.png)

