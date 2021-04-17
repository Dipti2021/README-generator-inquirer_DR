# README-generator-inquirer_DR
![License: Dipti](https://img.shields.io/badge/license-Dipti'sCode-yellow.svg)
![License: GPL v3](https://img.shields.io/badge/License-GPLv3-blue.svg)
![Project:no](https://img.shields.io/badge/Project-14-green.svg)



Generated a readme file using js npm and inquirer package.

## Table of Contents
* [Introduction](#introduction)
* [Demo of the Application](#web)
* [Installations](#installations)
* [Pseudocode](#details)
* [Special Features](#features)
* [Credits](#credits)

 ## Introduction 
 I have worked and added functions to the code where a part of it was already provide to me.This app generates a __README__ file based off the  user input. This app is mainly working from the "index.js" file and parts of it have been exported from "generateMarkdown"  file. Both of them being JavaScript codes.In order to start the code, you need to install the inquirer package and for that you should have npm installed. If not then you can do it using the following commands that need to be written in your terminal. 
 ```
npm init
```
```
npm install
```


 
 The application will begin by typing the following command in the terminal and pressing the "enter" key:
 ```
node index.js
```
The user will be greeted with a welcome message and will be then prompted to answer the questions.Once the user answers all the questions, a __README__ file is generated.
 
 
 
 ## Demo of the Application
 The following shows how I created this app and how it generates the file

![(https://www.youtube.com/watch?v=o8hkjz1TQuQ)


The working of the code quiz has been divided into the following parts:

PAGES | FUNCTIONS
------------ | -------------
LANDING PAGE |The quiz asks the player some code related questions. The questions are mainly based on Javascript techniques but it has been made using the concepts of HTML and CSS as well. We start the quiz by clicking the "Begin" button on the landing page along with the data that displays the remaining time and score points accumulated as the quiz progresses.
QUESTIONS PAGE | Once the quiz is started, the user is presented with a question, along with 4 possible answers.For each question, 4 options will be presented and the player has to select the correct option.Each correct answer increments your score by one and every incorrect answer decreases your working time by 5 seconds.
LAST PAGE | Once the user reaches the last question,after clicking an option for it his/her final score is displayed along with a finished prompt. Also, the player is asked to enter their initials in order to store their score. If the initials are anything else but alphabets, then he is prompted to enter the correct initials.The current and all the previous scores are stored in the local storage after clicking the Submit button.This list of saved scores can be seen by clicking the "View High Scores" button at any given time.

 
 ## Installations
   * [The URL of the Github repo](https://github.com/Dipti2021/Code_Quiz_DR)
   * [The URL of the deployed application](https://dipti2021.github.io/Code_Quiz_DR/)
 
 ## Pseudocode 
   1. Timer and score button are created that start at point 0
   2. Begin button is pressed in order to start the quiz.
   3. As soon as the quiz starts , the timer starts decrementing.
   4. Each question is presented on a new page.
   5. Choose one of the choice out of the 4 to finalise your answer.
   6. For every right or wrong answer, the player is notified.
   7. For correct answer score is added and for every wrong answer 5 seconds are deducted from the time.
   8. At theend, your score is displayed.
   9. All the past scores(if any) are also stores and they can be checkedat the end of the game or by clicking the Your Scores Button.
   10. The scores are stored in the local storage, on pressing the clear scores, the data gets deleted from the local storage a swell.


 ## Special Features:
The quiz has the following codes included
 * One HTML Page: index.html, which acts as a landing page for the quiz with all the necessary id's , classes, sectons et al mentioned
 * One CSS Page: style.css, which included a minimal styling required for the  html code
 * Two JS Pages: script.js and quiz.js, where the first file contains all the necessary declarations, conditions, storage formats and functions while the later has all the    set of questiond required to be answered

  All the js and css files are linked to the main html file

    
 
 ## Credits
    The homework has been assigned to me by the Carleton University Coding Bootcamp, our instructor and the TA's
