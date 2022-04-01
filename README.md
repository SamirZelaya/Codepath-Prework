# Pre-work - *Button Memory Game*

**Button Memory Game** is a Light & Sound Memory game to apply for CodePath's SITE Program. 

Submitted by: **Samir Zelaya**

Time spent: **11** hours spent in total

Link to project: (https://glitch.com/edit/#!/buttonmemorygame?path=style.css%3A1%3A0)

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
![Win Path Video](https://user-images.githubusercontent.com/102774013/161187796-0f6e612c-ec1c-48d4-a1f0-8a93c1687da3.gif)
![Lose Path Video](https://user-images.githubusercontent.com/102774013/161188565-7472c124-798b-4b72-83f2-61939e05c61a.gif)

## Reflection Questions
1. If you used any outside resources to help complete your submission (websites, books, people, etc) list them here. 
- CodePath
- Jude Surin(Friend)

2. What was a challenge you encountered in creating this submission (be specific)? How did you overcome it? (recommended 200 - 400 words) 
Throughout my time doing the coding for the project, I encountered several obstacles. One of them was the programming languages, which I've have not learned about. HTML and CSS were very new to me. However, the instructions to make the memory game showed me how to do it. Next, making the stop and start button switch and disappear was a bit of trouble. I solved it by changing the hidden to add or remove. Another problem I encountered was the sound check for the last button. I kept changing the frequency to match the rhythm of the button sounds, from lowest to highest pitch. The big problem I dealt with was the game automatically making the player lose even if they clicked the right button in the third round. I thought it was the nested if-statements that caused the conundrum, but it was not. Then, I checked my variables to see if the "progress" or "guessCounter" were set to the wrong number, but it was not. I asked my friend to help me, and he showed me that I declared the "guessCounter" in the function "playClueSequence". "guessCounter" is supposed to be set to 0 and not as a variable. With exporting the project to GitHub, it became a problem because I did not know how to. Though, I followed the video and it aided me to export it. The final problem was to figure out how to record the game. I attempted to use some of the given links to aid in recording, however, it only supported MacBook's. So, I found LICEcap and it worked successfully. The only thing is that it does not include audio. 

3. What questions about web development do you have after completing your submission? (recommended 100 - 300 words) 
I have a handle of questions about web development. Since I'm only starting in the field of technology and programming, I have concerns of my career field and if it's actually for me. In the workplace, will we be able to collaborate with others on projects? Will there be any C++ programming languages used in the coding? What other programming languages will web development have? Is there any training before you start your actual work in the job? Can web development behave as a virtual job only? Does web development handle game projects like this memory game? Are the hours for being a web developer flexible? Can being a web developer be incredibly stressful? What are the promotions after a back-end or front-end developer? Is web development a stable job to have? 

4. If you had a few more hours to work on this project, what would you spend them doing (for example: refactoring certain functions, adding additional features, etc). Be specific. (recommended 100 - 300 words) 
In all honesty, I would expand the game. I would add more buttons with distinct colors. I would add transparent background music while the project is running. I would add a home screen and a results screen. I could also add a function that takes the user's input when it asks for their name, and displays it alongside the you win message, or you lose message. I would add a timer for the player when the game starts. I would add the buttons to randomly generate one pattern. I would also like to add more lives for the player when they choose wrong. Lastly, I would add a difficulty selection where the patterns will sound faster if harder.  



## Interview Recording URL Link

[My 5-minute Interview Recording] https://mail.google.com/mail/u/2?ui=2&ik=56f3b15b9e&attid=0.1&permmsgid=msg-a:r-9148577792150401234&th=17fe44ae363499e9&view=att&disp=safe&realattid=f_l1g6hbxf0


## License

    Copyright [Samir Zelaya]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
