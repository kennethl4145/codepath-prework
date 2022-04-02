# Pre-work - *Memory Game*

**Memory Game** is a Light & Sound Memory game to apply for CodePath's SITE Program. 

Submitted by: Kenneth Lim

Time spent: 3 hours spent in total

Link to project: https://wax-fixed-monarch.glitch.me

## Required Functionality

The following **required** functionality is complete:

* [*] Game interface has a heading (h1 tag), a line of body text (p tag), and four buttons that match the demo app
* [*] "Start" button toggles between "Start" and "Stop" when clicked. 
* [*] Game buttons each light up and play a sound when clicked. 
* [*] Computer plays back sequence of clues including sound and visual cue for each button
* [*] Play progresses to the next turn (the user gets the next step in the pattern) after a correct guess. 
* [*] User wins the game after guessing a complete pattern
* [*] User loses the game after an incorrect guess

The following **optional** features are implemented:

* [*] Any HTML page elements (including game buttons) has been styled differently than in the tutorial
* [*] Buttons use a pitch (frequency) other than the ones in the tutorial
* [ ] More than 4 functional game buttons
* [*] Playback speeds up on each turn
* [*] Computer picks a different pattern each time the game is played
* [ ] Player only loses after 3 mistakes (instead of on the first mistake)
* [ ] Game button appearance change goes beyond color (e.g. add an image)
* [ ] Game button sound is more complex than a single tone (e.g. an audio file, a chord, a sequence of multiple tones)
* [ ] User has a limited amount of time to enter their guess on each turn

The following **additional** features are implemented:

- [ ] List anything else that you can get done to improve the app!

## Video Walkthrough (GIF)

If you recorded multiple GIFs for all the implemented features, you can add them here:
![](https://im4.ezgif.com/tmp/ezgif-4-f3ec2c9dfe.gif)
![](gif2-link-here)
![](gif3-link-here)
![](gif4-link-here)

## Reflection Questions
1. If you used any outside resources to help complete your submission (websites, books, people, etc) list them here. 
Stackoverflow.com
Geeksforgeeks.org
My older friend/mentor John Lee who is an experienced frontend developer

2. What was a challenge you encountered in creating this submission (be specific)? How did you overcome it? (recommended 200 - 400 words) 
A challenge I encountered in creating this submission was trying to implement a way to have a random pattern for the game. As the prework instructions had advised to use the Math.random() function to randomize the pattern, I was a bit unsure of how to implement this even though I was somewhat familiar with the Math.random() function. The original instructions of the game used a set pattern of an array of ints but I was unsure how I could I implement a way to generate a random array of ints from 1-4 everytime I clicked the start button of the game. I was able to overcome this by utilizing StackOverflow to figure out ways I can generate a random ints into an empty array at the start. I ended up finding a way to create a method that uses Math.random() to generate random ints 1-4 and called this method in my Start function where it uses a for loop to call the method to generate the random ints and push them into the empty array that is initialized at the global variables area. However, after testing out this method, I realized that there is some mistake in the code as the game does not work properly sometimes. When I click start, someones no pattern would be set and no clues would be played. Other times, clues less than the cluelength would be played. Because this is the only method I could think of and the limited time I have, I was not able to truly solve this issue.

3. What questions about web development do you have after completing your submission? (recommended 100 - 300 words) 
After completing my submission, I have several questions about web development. First off, I want to learn more about the roles web developers play in the professional field. I want to learn specifically what they do on the daily basis, like what are some things they work on. I also want to learn how web developers learn more about implementing certain algorithms into their projects and work.

4. If you had a few more hours to work on this project, what would you spend them doing (for example: refactoring certain functions, adding additional features, etc). Be specific. (recommended 100 - 300 words) 
If I had a few more hours to work on this project, I would first off try to complete all the optional features. One of the things I would definitely like to do is revamp the appearance of the game to add a moving gif or videoclip as a background of the site. I would love to give the text of the heading a bit more flare by adding some unique effects or gradients to it. Moreover, I would definitely spent more time debugging my javascript code for randomizing the pattern as my method is faulty, leading to a faulty buggy game. I was also unsuccessful in trying to show an image on each button when the buttons were pressed during the game. I was able to add an image to each button and sucesssfuly set the visibility to hidden but my lack of html and css has held me back from finding a way to show the image when the button is clicked. This project was the first project that had exposed me to front-end development and with more time, I would have been able to learn more syntax and ways to spice up the game.



## Interview Recording URL Link

[My 5-minute Interview Recording]https://vimeo.com/695115095


## License

    Copyright [Kenneth Lim]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.