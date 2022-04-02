# Pre-work - *Memory Game*

**Memory Game** is a Light & Sound Memory game to apply for CodePath's SITE Program. 

Submitted by: **Aerny Jiang**

Time spent: **2** hours spent in total

Link to project: (https://glitch.com/edit/#!/foamy-reminiscent-door)

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
![](https://i.imgur.com/loD300D.gif)
![](https://i.imgur.com/mS2EZPY.gif)

## Reflection Questions
1. If you used any outside resources to help complete your submission (websites, books, people, etc) list them here. 
[https://www.w3schools.com/colors/colors_names.asp https://www.the-art-of-web.com/javascript/creating-sounds/ ]

2. What was a challenge you encountered in creating this submission (be specific)? How did you overcome it? (recommended 200 - 400 words) 
[While working on task 2 of this submission, I came across a problem with the software used to record gifs. I wanted to use QuickTime because it doesn’t require any downloading, but since it only works on Mac, and I’m on Windows, I decided to go with Recordit. However, after downloading Recordit, I could not get the application to open. I tried clicking on the Recordit icon on my desktop and even tried manually opening it through File Explorer with no success. I turned to my best friend, Google, which said that I should be able to find an icon on my taskbar which I would have to click to launch the tool. However, the icon was nowhere to be found. So, I decided to reinstall the application, hoping that I would have a better outcome, but I was out of luck. The Recordit help page directed me to contact them by email if the application wouldn't open or work, but I knew it would take time to hear back. I also knew how important it was to record the gif and complete my submission in a timely manner. To overcome this, I decided that it was more time effective to use an alternative software to record the gif even though I was trying to avoid downloading more applications. I downloaded LICEcap, and to my surprise, it launched and was very easy to use. After getting my gif maker software to work, I was able to record two gifs and link them onto my GitHub submission. 
]

3. What questions about web development do you have after completing your submission? (recommended 100 - 300 words) 
[After working on this project, I am wondering how to make websites that are more dynamic and unique. How can I animate icons and create smooth transitions to flow from one page to the next? This also leads me to wonder what aspects a developer should keep in mind when developing a website to ensure that a user’s experience is enjoyable. While console logging as part of the playClueSequence method, I was blown away by that fact that I was effectively using it because I used to open the Developer’s Tools panel by accident and didn’t have any idea what it did before. I actually used to think that I had broken the website when it unintentionally opened. Now that the console part has been demystified to me, I have questions on how to  use the rest of the panel’s tools like the “Elements” tool and am interested in learning more about them. Finally, since this project focused on the frontend, I wonder what backend and fullstack development are all about. If I were to create a global leaderboard for this game that keeps track of the most wins in the world, how would I go about implementing it? Is this a backend and database developer’s responsibility or can it be done in frontend? Putting everything together, how could I connect the frontend to the backend so that they are one unified project? 
]

4. If you had a few more hours to work on this project, what would you spend them doing (for example: refactoring certain functions, adding additional features, etc). Be specific. (recommended 100 - 300 words) 
[To take this project to the next level, I would add a function that continues adding a random clue as long as the player guesses correctly. To do so, I would initialize the pattern variable as an empty array for keeping track of the clues and using it to check against the player’s guesses. I would use a while loop that checks for correct guesses and the Math.random function to generate a random number between 1 and 4, making sure to append the generated number to the pattern variable at the end of each iteration. This new function makes it so that the game could potentially go on forever as long as the player guesses every clue correctly. Taking this aspect into account, I would alter the way a player can win by making it so that winning means guessing more clues correctly than before and losing means guessing less clues correctly than before. To implement this feature, I would keep track of the number of total clues that were guessed correctly at the end of each game by initializing an array with 0 as its first element and appending the length minus 1 of the pattern array when the game stops. I would also revise the guess function by having it continue if the guess is correct and writing an else statement with an if conditional statement that calls the winGame function only if the length of this pattern array is greater than the lengths stored in the array of previous lengths and calls loseGame otherwise.]



## Interview Recording URL Link

[My 5-minute Interview Recording](https://ucsd.zoom.us/rec/share/E_eYJML3QGulw-DtWHflzvaXXX1acgnPHdBqZ2ej8iLNplEWG2EQGWTtbuBXkinJ.hLocVAoiKvKBEPjT )


## License

    Copyright [Aerny Jiang]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.