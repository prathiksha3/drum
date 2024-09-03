# Drum Kit Project
# Overview
This project is a simple interactive drum kit built using HTML, CSS, and JavaScript. Users can play different drum sounds either by clicking on the drum buttons displayed on the screen or by pressing specific keys on their keyboard. Each key corresponds to a different sound, allowing users to create their own rhythms.

# Features
Interactive UI: Click on the drum buttons to produce sounds.

Keyboard Support: Use the keyboard keys w, a, s, d, j, k, l to play drum sounds.

Responsive Sound: Both mouse clicks and keypresses trigger different sounds, making the experience more interactive.

# Technologies Used
HTML5: Used for creating the structure of the page.

CSS3: For basic styling.

JavaScript: Adds interactivity and sound effects using Audio objects.

# How It Works
Event Listeners: JavaScript adds click event listeners to each drum button. When clicked, the corresponding sound plays.

Keypress Event Listener: Another event listener detects keyboard keypresses. If a user presses any of the specified keys, the corresponding drum sound is played.

Switch Statement: The switch statement in the JavaScript code is used to map each key or button click to the correct sound file.
