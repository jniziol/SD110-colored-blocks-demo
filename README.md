# Colored Blocks

A JavaScript practice application to practice using DOM selectors and events.

First, download the the [starter files from this respository.](https://github.com/jniziol/colored-blocks/tree/main/colored-blocks-starter-files)

Push yourself and try to complete this without making any changes to the HTML file.

You will need to update the JavaScript file perform the following tasks:

Add a single event listener (not a loop that adds 1 event listener to each div, just 1 event listener total! Delegate the event...) that will listen for clicks on any of the `color` divs on the page and invoke a function on click.

When a `color` div is clicked do the following:

- Set the background color of the clicked `color` div to the color value set in the `color-picker` input, if there is one. If there is not one, use the `randomColor()` function to generate a random color.

- If a `color` div has already been *colored*, it should not be colored again. 

- Add the color name, or number, to the *colored* div as text, that corresponds to the background color that was assigned to it.

- After the *colored* div has been colord, clear the value from the input, so that it's ready for new input.

- Once all the divs have been colored (ie. clicked), pop up an alert indicating that the page has been completely colored.

You can see a working demo, [here](https://jniziol.github.io/SD110-colored-blocks-demo/)

> Notice that the Javascript file is __NOT__ being loaded by the HTML. You will need to update your HTML to ensure that it it loading the JS file.

### NOTE

There is a known timing bug that occurs with `ALERT`. Your last square will __NOT__ be colored until after the alert pops up. This is a known issue with the Web Api. Do not fret, it is not an issue with your code.
