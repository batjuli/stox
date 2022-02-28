# stox :money_with_wings:

## Installation Guide

Assuming that node and npm are installed properly, from the root project directory run:

1. `npm install`
2. `npm run installer`

## Quick Start

From root project directory run:

1. `npm run dev`

Note that a valid MongoDB URI, as well as AlphaVantage and NewsAPI keys are needed for proper functionality. These can be added in the file `backend/keys.js`.

## About stox

Stox is a stock portfolio management web app, implemented using the MERN stack (MongoDB, ExpressJS, React, and NodeJS).

This project was completed from scratch as part of uni coursework, in a team of five. Final mark was 96/100.

### Functionalities

- User authentication and authorisation
- View stock information and history
- Create watchlists and portfolios
- Summaries of earnings from portfolios
- View trending stocks among other users
- Relevant stock news sentiment analysis

![stox_walkthrough](https://user-images.githubusercontent.com/81475247/155943950-6556c481-20e3-4745-aa2c-d9071e85b273.gif)

### APIs

- **AlphaVantage:** Retrieval of historical and current stock information
- **NewsAPI:** Retrieval of recent, stock-relevant news stories
