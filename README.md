# AI-Teaching-Assistant
This is a project created by Daniel Stapley and Kai Sandberg in order to help the BYU Dean of FHSS, Doctor Laura Walker.


## Project Purpose
The purpose will be to create a web application that supports the teaching or learning process in any desired topic. The application will prompt the user to input a subject, and it will retrieve and output informational clips from YouTube. The application will use AI to analyze information obtained by calling YouTube's API to find the three most relevant videos on the inputted subject. We will then allow the user to choose their desired clip length, and output one clip each from the chosen videos. 

## General Project Plan
- Create the web application using `flask` as back-end support
- Based on user input, retrieve data from YouTube's database
- Prompt ChatGPT using the OpenAI API, have it analyze the data and return the three most relevant videos
- Use the `PyScene` SHOT model to suggest and output a clip with the specified length for each video
