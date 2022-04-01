# Pre-work - *Memory Game*

**Memory Game** is a Light & Sound Memory game to apply for CodePath's SITE Program. 

Submitted by: **Cam Nhung Tran**

Time spent: **2** hours spent in total

Link to project: https://dog-periwinkle-romano.glitch.me/

## Required Functionality

The following **required** functionality is complete:

* [X] Game interface has a heading (h1 tag), a line of body text (p tag), and four buttons that match the demo app
* [X] "Start" button toggles between "Start" and "Stop" when clicked. 
* [X] Game buttons each light up and play a sound when clicked. 
* [X] Computer plays back sequence of clues including sound and visual cue for each button
* [X] Play progresses to the next turn (the user gets the next step in the pattern) after a correct guess. 
* [X] User wins the game after guessing a complete pattern
* [X] User loses the game after an incorrect guess

The following **optional** features are implemented:

* [ ] Any HTML page elements (including game buttons) has been styled differently than in the tutorial
* [ ] Buttons use a pitch (frequency) other than the ones in the tutorial
* [ ] More than 4 functional game buttons
* [ ] Playback speeds up on each turn
* [ ] Computer picks a different pattern each time the game is played
* [ ] Player only loses after 3 mistakes (instead of on the first mistake)
* [ ] Game button appearance change goes beyond color (e.g. add an image)
* [ ] Game button sound is more complex than a single tone (e.g. an audio file, a chord, a sequence of multiple tones)
* [ ] User has a limited amount of time to enter their guess on each turn

The following **additional** features are implemented:

- [ ] List anything else that you can get done to improve the app!

## Video Walkthrough (GIF)

If you recorded multiple GIFs for all the implemented features, you can add them here:

Showing Start/Stop and each button working 

![](http://g.recordit.co/z8LGRovWD1.gif)

Showing the game progressing with each correct answer

![](http://g.recordit.co/JhiI2MLbsW.gif)

Showing the game winning 

![](http://g.recordit.co/y29wEBX5PN.gif)

Showing the game losing 

![](http://g.recordit.co/EpbJsi3vKB.gif)

## Reflection Questions
1. If you used any outside resources to help complete your submission (websites, books, people, etc) list them here. 

	https://www.w3schools.com/howto/howto_js_add_class.asp
	https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/addressing-merge-conflicts/resolving-a-merge-conflict-on-github 
	https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/addressing-merge-conflicts 

2. What was a challenge you encountered in creating this submission (be specific)? How did you overcome it? 

	One of the challenges I encountered in creating this submission was that I didn’t know how to write the code in HTML when dealing with a class attribute. I tried a few test methods before I finally looked it up on Google on how to add class attributes. Another challenge I encountered was when I finished writing the code was that although the program was starting and playing the sequence of sounds, the buttons were not lighting up when the sound was being played. However, the buttons did light when the user clicked on the squares. I reviewed my code and realized that I had forgotten a semicolon in the CSS file in the active button lines. I had to go through the steps of the debugging process to find the tiny error. 

3. What questions about web development do you have after completing your submission? 

	I manually coded a sequence of numbers in an array to have the buttons make sounds and light up. I was wondering how you would implement an API that already has an array of random numbers to refer to be able to play different sequences of lights and sounds for each new starting game.? Or would it be less of a hassle to create a random number generator in the HTML file itself? To have the game be timed, do we have to refer to a system clock or do other files or programs need to be imported in HTML?

4. If you had a few more hours to work on this project, what would you spend them doing (for example: refactoring certain functions, adding additional features, etc). Be specific. 

	If I had a few more hours to work on this project, I would learn more about CSS to style the webpage more. I would learn more about the different fonts, color options as well as built in tools that CSS is able to import to make it more robust.  I would have a changing background for different themes depending on the day, as Google does on their primary search engine webpage. I would add different sequences of lights, so there would be variety in the game. I would also add a timer that counts down so that the player has to play the game in a specific time frame.

## Interview Recording URL Link

[My 5-minute Interview Recording](your-link-here)


## License

    Copyright [Cam Nhung Tran]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
