# IPL 2021 Cricket Game

## Table of Contents
- [Introduction](#introduction)
- [Demo](#demo)
- [About the Project](#about-the-project)
- [Features](#features)
- [Used For](#used-for)
- [Improvements](#improvements)
- [Problems Faced](#problems-faced)
- [Technologies Used](#technologies-used)
- [Links](#links)
- [Getting Started](#getting-started)

## Introduction
IPL 2021 Cricket Game is an interactive web-based cricket game that allows users to experience the excitement of the Indian Premier League (IPL). Players can select two teams out of the participating franchises. The game follows the standard T20 format, where each team gets to bat and bowl for 20 overs.

## Demo


https://github.com/yashksaini/IPL-2021/assets/101442489/26959eda-c376-42bf-9d40-c1ea46185328



## About the Project
IPL 2021 Cricket Game is a thrilling gaming experience for cricket enthusiasts. It captures the essence of the IPL tournament and offers an immersive cricket simulation. The game is developed using HTML, CSS, and JavaScript, making it easily accessible on various devices.

Users can enjoy the excitement of the toss, team selection, and strategic decision-making in the game. The dynamic generation of runs and live score updates add realism to the gameplay. Whether you're a cricket lover or simply seeking entertainment, IPL 2021 Cricket Game provides hours of fun.

The team winning the toss decides whether to bat or bowl first. Players can then select their playing XI from a squad of 25 players, ensuring a balance of at least one wicketkeeper, six bowlers, and a maximum of four overseas players. 

The game simulates the cricketing experience, generating random runs (0, 1, 2, 3, 4, 6, 'W') for each ball. 

The scorecard and overs are updated dynamically based on the runs scored. The second innings is a chase, where the second batting team aims to chase down the target set by the first team.

## Features
- Team selection from participating franchises
- Toss to decide batting or bowling
- Player selection with squad restrictions
- Dynamic generation of random runs
- Live scorecard and over updates
- T20 format with 20 overs per team
- Challenging chase in the second innings
- Random runs according to the number of wickets fall

## Used For
- Entertainment
- Cricket simulation
- Strategic decision-making
- Enjoying IPL experience
- Multiple Screen handling with JavaScript

## Improvements
- Add player profiles and statistics for an enhanced experience
- Implement more realistic ball physics and player animations
- Include commentary and sound effects to amplify excitement
- Create multiplayer mode for head-to-head matches
- Add powers to players

## Problems Faced
- Implementing random run generation for each ball
  - Developed a function to generate random runs (0, 1, 2, 3, 4, 6, 'W') for each ball, simulating real cricket scenarios.
- Ensuring squad restrictions for player selection
  - Implemented logic to enforce the squad restrictions, ensuring that each team selects the required number of players based on the given criteria.
- Updating the scorecard after each ball
  - Implemented logic to display the scorecard as an array of objects for the team.

## Technologies Used
- HTML
- CSS
- JavaScript

## Links
- [Live Demo](https://2021ipl.netlify.app/)
- [GitHub Repository](https://github.com/yashksaini/IPL-2021)

## Getting Started
To run the IPL 2021 Cricket Game locally, follow these steps:
1. Clone the GitHub repository: `git clone https://github.com/yashksaini/IPL-2021.git`
2. Navigate to the project directory: `cd IPL-2021`
3. Open the `index.html` file in your preferred web browser.
