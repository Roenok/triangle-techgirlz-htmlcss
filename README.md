# Building a Website - Triangle Techgirls

These are the slides and practice files for the Triangle Techgirlz HTML/CSS workshop. They were developed by Sylvia Richardson, based on the official Girl Develop It Core HTML/CSS curriculum. 

This is a one-day, four-hour workshop. Each of the slides and practice files are customizable according to the needs of a given class or audience.

## Topics
This workshop covers
* The basics of HTML, including tags
* The layout of a simple HTML page
* The differences between HTML and CSS
* How to use CSS to customize page styles

## Theme customization

You can change theme colors by changing the theme css to any of the following options:
```html
  <link rel="stylesheet" href="css/theme/gdidefault.css" id="theme">
  <link rel="stylesheet" href="css/theme/gdilight.css" id="theme">
  <link rel="stylesheet" href="css/theme/gdisunny.css" id="theme">
  <link rel="stylesheet" href="css/theme/gdicool.css" id="theme">
```
You can change the text editor theme by changing the highlight.js css to the following options:
```html
  <link rel="stylesheet" href="lib/css/dark.css">
  <link rel="stylesheet" href="lib/css/light.css">
```
You can change transition by changing the reveal transition property in Reveal.initialize
```javascript
  Reveal.initialize({
  				transition:  'default', // default/cube/page/concave/zoom/linear/none
  			});
```
