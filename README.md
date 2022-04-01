# Pre-work - *Memory Game*

**Memory game** is a Light & Sound Memory game to apply for CodePath's SITE Program. 

Submitted by: Owenga Vernon Otieno

Time spent: 6 hours spent in total

Link to project: https://glitch.com/edit/#!/pre-work-memory-game-v-owenga

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
* [X] Playback speeds up on each turn
* [X] Computer picks a different pattern each time the game is played
* [X] Player only loses after 3 mistakes (instead of on the first mistake)
* [ ] Game button appearance change goes beyond color (e.g. add an image)
* [ ] Game button sound is more complex than a single tone (e.g. an audio file, a chord, a sequence of multiple tones)
* [X] User has a limited amount of time to enter their guess on each turn

The following **additional** features are implemented:

- [ ] List anything else that you can get done to improve the app!

## Video Walkthrough (GIF)

If you recorded multiple GIFs for all the implemented features, you can add them here:

![](https://i.imgur.com/SZBuBg7.gif)
![](https://i.imgur.com/RN32EKd.gif)


## Reflection Questions
1. If you used any outside resources to help complete your submission (websites, books, people, etc) list them here. 

W3schools.com saw me through most of the development stages especially through Javascript development. I added a cool font style to my project which I got from cdnfonts.com. The site came in handy providing the CDN that I linked to display the desired text at the top of the page. Stackflow was helpful when it came to adding the timer clock that I implement to count down the time before losing due to the timing aspect. I also used Google to get most of the guidance on how to go about bug fixes in my Javascript code.


2. What was a challenge you encountered in creating this submission (be specific)? How did you overcome it? (recommended 200 - 400 words) 

It was a major challenge implementing the counter clock to my project using functions. I was mostly new to the javascript code syntax used and had to go through multiple codes online to get a firm grip of how to get it right. However, codes on Stackoverflow shade more light giving me insight on how to go about them. One major challenge worth noting was getting the browser to play the tones of the set frequency. It took very long and multiple refreshes to make the buttons produce sound on click. Also, the timer done in the basic version of the game could not account for delay in play when playing the game making it pretty hard to win the game. I spent quite some time trying to figure out how to avoid the barrier searching online for a quick fix. In the end, the timer that I added eliminated the challenge of losing due to imperfect timing. The logic code belt became more difficult with the implementation of the countdown function using setInterval() which was being called several times as well as countDown()  at the same time as the guess() and stopGame functions to reset the countDown() in order to refresh the timer. With this, I had to go through multiple sites on google to see how to effectively do the logic circuit.


3. What questions about web development do you have after completing your submission? (recommended 100 - 300 words) 

Developing the web app using javascript opened an avenue for venturing into frontend development. I am very curious about hot frameworks like AngularJS, React and Vue are incorporated in the development stages. Looking at the current trends, React seems to be taking the other frameworks like AngularJS by storm. My general concern is which frameworks will guarantee relevancy in my future as a web developer. Another area of concern is the painstaking process of using Git for web projects. I am worried about the challenge of clashing pushes to the main repositories for a project being worked on by multiple people. How exactly does that situation work? 


4. If you had a few more hours to work on this project, what would you spend them doing (for example: refactoring certain functions, adding additional features, etc). Be specific. (recommended 100 - 300 words) 

If I were given more time to work on the project I would like to add a few more updates on the general appearance of the web app such as a background image that matches the colors of the buttons I used. Implementation of a volume control slider would also make the web app more impressive. Adding images to the buttons that I would then sync with audio cues that match the images to make the game more specific to practise memorizing a certain topic of interest to the player. This would then require a list of options that would lead to different categories of topics to memorize. Implementing all this would help sharpen my basic HTML, CSS and Javascript coding skills.




## Interview Recording URL Link

Here is a link to my interview video: https://northwestern.zoom.us/rec/share/A6fcMQmttXIc76dFeGOVWOYNqzVgpMF2BjllKEG7BrVm6xTcKz6EqaHV6jRCKW7Z.mPTaTF8-mWJ_uXgX


## License

    Copyright [Owenga Vernon Otieno]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.