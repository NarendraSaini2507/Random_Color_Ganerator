# Random_Color_Ganerator

Random Color Generator

Overview

This project is a simple random color generator created using HTML, CSS, and JavaScript. It generates random colors and displays them in a grid. Clicking on a color copies its hex code to the clipboard and displays it in an overlay.

Features

Generates 25 random colors dynamically.

Displays each color's hex code.

Click on a color to copy its hex code to the clipboard.

An overlay appears when a color is clicked, showing the selected color and its hex code.

Smooth transition effect for the overlay.

Project Structure

index.html - The main HTML file containing the structure of the application.

style.css (embedded) - The CSS file for styling the layout, colors, and animations.

JavaScript (inside index.html) - Generates colors, updates the UI, and handles the click event for copying hex codes.

How It Works

The script generates 25 random colors using Math.random() and converts them to hex format.

Each color is displayed inside a div element with its hex code.

When a user clicks on a color, an overlay appears, displaying the color and its hex code.

The hex code is automatically copied to the clipboard.

The overlay disappears after 0.5 seconds.

How to Run

Download or copy the index.html file.

Open index.html in a web browser.

Click on any color box to copy its hex code.

Customization

To generate more or fewer colors, change the loop limit in JavaScript (for(var i = 1; i<=25; i++)).

Modify the CSS to adjust the color box size, font size, or overlay appearance.

Change the animation duration in .overlay CSS for a different transition effect.
