# Pre-work - *Memory Game*

**Memory Game** is a Light & Sound Memory game to apply for CodePath's SITE Program. 

Submitted by: **Surina Hankins**

Time spent: **4** hours spent in total

Link to project: https://seed-southern-sneeze.glitch.me

## Required Functionality

The following **required** functionality is complete:

* [x] Game interface has a heading (h1 tag), a line of body text (p tag), and four buttons that match the demo app
* [x] "Start" button toggles between "Start" and "Stop" when clicked. 
* [x] Game buttons each light up and play a sound when clicked. 
* [x] Computer plays back sequence of clues including sound and visual cue for each button
* [x] Play progresses to the next turn (the user gets the next step in the pattern) after a correct guess. 
* [x] User wins the game after guessing a complete pattern
* [x] User loses the game after an incorrect guess

The following **optional** features are implemented:

* [x] Any HTML page elements (including game buttons) has been styled differently than in the tutorial
* [x] Buttons use a pitch (frequency) other than the ones in the tutorial
* [x] More than 4 functional game buttons
* [x] Playback speeds up on each turn
* [x] Computer picks a different pattern each time the game is played
* [x] Player only loses after 3 mistakes (instead of on the first mistake)
* [ ] Game button appearance change goes beyond color (e.g. add an image)
* [ ] Game button sound is more complex than a single tone (e.g. an audio file, a chord, a sequence of multiple tones)
* [ ] User has a limited amount of time to enter their guess on each turn

The following **additional** features are implemented:

- [x]Easy difficulty: pattern length = 4, player loses after 3 mistakes
- [x]Hard difficulty: pattern length = 8, player loses after 1 mistake

## Video Walkthrough

Here's a walkthrough of implemented user stories:
* [x] Easy win <p><img src="http://g.recordit.co/3sMTcBtErE.gif" width=250><br></p>
* [x] Easy lose <p><img src="http://g.recordit.co/JefcutXy0P.gif" width=250><br></p>
* [x] Hard lose <p><img src="http://g.recordit.co/UeFdm1zaiu.gif" width=250><br></p>


## Reflection Questions
1. If you used any outside resources to help complete your submission (websites, books, people, etc) list them here. 
<p> https://www.w3schools.com/cssref/pr_font_font-style.asp, https://www.w3schools.com/jsref/jsref_random.asp, https://www.w3schools.com/js/js_arrays.asp, https://www.w3schools.com/cssref/css_colors.asp, https://www.w3schools.com/js/js_function_parameters.asp
</p>

2. What was a challenge you encountered in creating this submission (be specific)? How did you overcome it? (recommended 200 - 400 words) 
<p>
At first my buttons weren't working properly, after going through some debugging with the console I realized that my name for the buttons in index.html was different from script.js. I also saw some difficulty when adding things related to the frequencies. I had to look more closely at the code so that I understood it better. Before, I just copy pasted the code and had a basic understanding of it. By going through it and testing each frequency myself, I understood it better and was able to implement some of the optional features. I had a lot of trouble trying to implement a timer. I tried looking up a lot of stuff, but in the end I couldn't figure out how to display my timer variable on the page in html. Because I had limited time I decided it was okay to leave out, and instead decided to implement my own feature to make up for it.
 </p>

3. What questions about web development do you have after completing your submission? (recommended 100 - 300 words) 
<p>
I want to know everything about it. How do you display changing variables on webpages? How do pages store user data such as logins or data from saved online games? How do malware and pop-up ads work? Can you also make objects in JS like you do in C++, how do they work, and what would you use them for?
</p>

4. If you had a few more hours to work on this project, what would you spend them doing (for example: refactoring certain functions, adding additional features, etc). Be specific. (recommended 100 - 300 words) 
<p>
I would have figured out a way to display a timer so that the player would have limited time. I'd implement this in my two difficulty settings, so that on the harder setting the player would be timed, but not on the easy difficulty. I would also display the amount of attempts/strikes left. If I had even more time and the knowledge to do so, I'd make my difficulty settings more detailed. On the easy mode clueHoldTime wouldn't decrease and there would be unlimited attempts. I would change my current hard difficulty to be "medium" with 3 strikes, and make a new hard difficulty with an even longer pattern, shorter clueHoldTime, and no strikes. I would also potentially give the player the option to choose the pattern length manually.
</p>



## License

    Copyright Surina Hankins

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
