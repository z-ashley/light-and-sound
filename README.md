# Pre-work - *Memory Game*

**Memory Game** is a Light & Sound Memory game to apply for CodePath's SITE Program. 

Submitted by: **Ashley Zhao**

Time spent: **2** hours spent in total

Link to project: https://glitch.com/~light-and-sound-codepath

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

* [X] Any HTML page elements (including game buttons) has been styled differently than in the tutorial
* [X] Buttons use a pitch (frequency) other than the ones in the tutorial
* [X] More than 4 functional game buttons
* [ ] Playback speeds up on each turn
* [X] Computer picks a different pattern each time the game is played
* [ ] Player only loses after 3 mistakes (instead of on the first mistake)
* [X] Game button appearance change goes beyond color (e.g. add an image)
* [ ] Game button sound is more complex than a single tone (e.g. an audio file, a chord, a sequence of multiple tones)
* [ ] User has a limited amount of time to enter their guess on each turn



## Video Walkthrough

Here's a walkthrough of implemented user stories:
![](https://i.imgur.com/pPgBEfn.gif)


## Reflection Questions
1. If you used any outside resources to help complete your submission (websites, books, people, etc) list them here. 
w3schools
StackOverflow

2. What was a challenge you encountered in creating this submission (be specific)? How did you overcome it? (recommended 200 - 400 words) 
During my attempt to implement a timer, one major challenge I encountered was that the timer code I found on StackOverflow didn't fully function as expected. The timer would not clear itself upon the countdown to 0, and there were no follow-up posts on the StackOverflow forum post that addressed this issue. I initially tried a brute-force, fast, solution where I literally set the text of the timer as zero upon the counter variable reaching 0, and quickly realized that it was not sustainable. Therefore, I looked into approaches that would take more patience on my end. 
While taking the class Data Structures and Algorithms, I had encountered similar roadblocks while writing code for homework assignments. While programming this submission, I found myself using the strategies that I've learned in that class to find solutions to issues that arise. I included statements that would print to the console in order to isolate where in the code problems are occuring, and I used boolean variables to force functions to stop running. Of course, I heavily utilized the classic strategy of googling the issue and clicking on the first StackOverflow link that appears. 



3. What questions about web development do you have after completing your submission? (recommended 100 - 300 words) 
In what order are different parts of a project implemented? While following the pre-work instructions to create the base project, I was first instructed to create the game's appearance and associated sound effects before finally implementing the game logic. To be honest, I found that implementing the details of appearance such as sound effects counter-intuitive to how I would normally work on a project. I would generally create a barebones skeleton of a UI first, invest my time in implementing logic fully, and then return to adding some more detail to the UI. I suppose that's fairly similar to what I did for this submission, but I did find myself wondering to what extent UI is prioritized during web development and how the relationship between UI and "backend" logic is factored in while structuring a development timeline. 

4. If you had a few more hours to work on this project, what would you spend them doing (for example: refactoring certain functions, adding additional features, etc). Be specific. (recommended 100 - 300 words) 
I would prioritize refactoring the code so that the implementation of individual buttons could be more generalized. To improve code readability, I would also categorize the code in index.html and script.js into separate files within folders. By doing so, different functions of the game would be categorized and more easily accessible than what exists currently, which is a long file with many functions that do separate things. 
To strengthen the playability of the game itself, I would add a more cohesive theme to the game to make it more unique and eye-catching. Currently the buttons feature cat images, so I would expand upon that theme and add more "feline elements", like meowing sound effects depending on win/loss and paw shaped buttons. I'd also take into greater consideration how to retain the attention of the player by increasing the rewards after playing. To generate more serotonin in the player after each round, I would implement achievements and high scores, so the player feels a greater sense of satisfaction.




## License

    Copyright Ashley Zhao

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
