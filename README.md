# Drum Set


In this project we have a set of buttons on the screen corresponding to different keys on the keyboard. And each button has a corresponding <audio> element on the page. The goal is to play the corresponding audio when a valid key is pressed on the keyboard.

So after detecting which key is pressed using the keyCode attribute, we select the corresponding <audio> element using a pre-specified data-key attribute in HTML and call the audioElement.play(); method on it.
