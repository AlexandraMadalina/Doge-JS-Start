# Doge-JS-Start

This is a class exercise created by our coach [Lambelin Rafael](https://github.com/rafaello104)


I follow this exercises during my training as JuniorWeb Developer at BeCode in maart 2019.
This is our initiation exercise in Javascript to manipulate DOM elements.

## Objectives

- Learn how to target elements
- Learn how to listen to events
## Instructions

- Create a simple html page with one button in the middle of the page
- Give this button the id "doge"
- Give this button the text Doggo

**Now we're going to do some modifications to the doge button, do them step by step:**

- When the page is finished loading, change the text to "Woof!"
- When you hover over the button "Woof!" should disappear and a little doggo icon should appear instead
- When you click the button a picture of a [doge](http://www.stickpng.com/cat/memes/doge?page=1) should show up somewhere on the page
- When you click the button again, the picture should disappear

To change the text of the button change when the page finishes loading, I have used `window.onload` function , I identified the button by his id and changed it's value.

To make the button transform into a dog icon on hover, I added the `onmouseover` event to the button and changed the display property of the icon (that already exists in DOM) from ` display: none` to `display: inline`, and the display property of the button to `display: none`. 
