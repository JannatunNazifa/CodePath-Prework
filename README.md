# Pre-work - *Memory Game*

**Memory Game** is a Light & Sound Memory game to apply for CodePath's SITE Program. 

Submitted by: Jannatun Nazifa

Time spent: 11 hours spent in total

Link to project: https://glitch.com/edit/#!/concise-rightful-stick?path=script.js%3A107%3A22

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
* [x] Game button appearance change goes beyond color (e.g. add an image)
* [ ] Game button sound is more complex than a single tone (e.g. an audio file, a chord, a sequence of multiple tones)
* [ ] User has a limited amount of time to enter their guess on each turn

The following **additional** features are implemented:

- [ ] List anything else that you can get done to improve the app!

## Video Walkthrough (GIF)

If you recorded multiple GIFs for all the implemented features, you can add them here:

Scenario 1: Winning the game with two mistakes:
![](https://i.imgur.com/vcUf3F5.gif)

Scenario 2: Losing the game after three mistakes:
![](https://i.imgur.com/mJbyH92.gif)
![](gif3-link-here)
![](gif4-link-here)

## Reflection Questions
1. If you used any outside resources to help complete your submission (websites, books, people, etc) list them here. 

Antiya Kumar Gupta ( CodePath Prework Slack channel)
JavaScript Tutorial | setInterval & clearInterval - YouTube (https://www.youtube.com/watch?v=3yfJYA0RKVs&t=18s)
CSS Reference Guide (https://www.w3schools.com/cssref/default.asp)
MDN Web Docs- Math.random() (https://developer.mozilla.org/en-US/docs/web/javascript/reference/global_objects/math/random)
CSS color codes & names (rapidtables.com)
Learn CSS Position In 9 Minutes - YouTube (https://www.youtube.com/watch?v=jx5jmI0UlXU)


2. What was a challenge you encountered in creating this submission (be specific)? How did you overcome it? (recommended 200 - 400 words) 

I was excited to add flower images at the center of the game buttons to make it more fun! However, I was struggling to position the images relative to each separate button. If I were to add an image to the ‘index.html’ file as an element, it would be positioned at a random place in the webpage. In order to solve this, I researched on Youtube and Google about CSS Positioning. I got to learn about absolute and relative positioning but soon I came to realize that it was not the best choice for my specific project. Since there were six buttons and six different images, I was having a hard time not to make the computer confused about which button is the parent element of which image I posted my question in the Slack webdev channel and one of the CodePath TAs referred me to a code that used the ‘background-image’ property. I read independently about the other background properties such as size, position, repeat etc. A combination of all of these properties , while added to the CSS code for the buttons when it was ‘lit’, was the perfect solution to my problem. I learned that even though an answer can sound very obvious, it might not be applicable to all problems. Hence, it is a good practice to look for multiple angles while tackling an issue and use the most efficient one.

Another challenge I faced was to generate a random clue sequence every time the game restarts. From the hints, I knew I had to use math.random() to generate a random number, but I was confused how would I correspond that number to the pattern the game follows. I remembered I did something similar in a programming course before.. I knew which array was telling the computer the pattern, but instead of predetermined values, I have to now put different values each time. From my past projects I realized that I can do so with a for loop. I created a loop with the variable i that will loop 8 times and used pattern[i] syntax to target the ith element of the array. This roadblock taught me to pay close attention to all the resources available to me, and sometimes the most valuable of those are my knowledge and experiences taken from past projects. 


3. What questions about web development do you have after completing your submission? (recommended 100 - 300 words) 

After completing the project, I have a general idea about how to get a basic webpage up and running. It made me reflect on the webpages I have visited, and connect my newly gained knowledge to comprehend how some of the elements there might have been implemented. But I am curious to know how web developers handle elements that need to be updated constantly such as product sale numbers, member numbers, number of friends in a social media app etc. I am also curious about the security aspect of a webpage. How do one make sure no one can access the code of their webpage and alter it? How can one create safety to keep their member data private?Additionally,  I have noticed that the game I created does not look the same on a computer screen and a mobile screen. It becomes almost impossible to play the game on a mobile screen because all the buttons don't show up at the same time and the user has to scroll down everytime or they might miss a clue. From there, I am curious to know how a webpage can be modified in a way so that it shows up in a suitable format depending on which device it is being used in.

4. If you had a few more hours to work on this project, what would you spend them doing (for example: refactoring certain functions, adding additional features, etc). Be specific. (recommended 100 - 300 words) 

If I had more time, I would like to play around with the colors and images to create different themes like garden, space etc that the user can choose from according to their taste. I would also like to add distractions that would pop up here and there in the webpage and the user would have to click on it while keeping track of the pattern. If they miss to click two or more of the distractions they would lose the game. This could create an additional challenge and make the game more interesting. This distraction would vary in appearance depending on the theme, for the garden the distraction can be a butterfly and for the space the distraction can be some scary looking aliens!  



## Interview Recording URL Link

[My 5-minute Interview Recording]
(https://www.loom.com/share/8ddc0c01578845aa9ba67b7806658d8e)


## License

    Copyright [Jannatun Nazifa]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
    
