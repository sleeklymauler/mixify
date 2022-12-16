# mixify

Mixify was my final group project for the Fall 2022 Software Development Methods and Tools class at the University of Colorado Boulder.

The full project can be found on my student github repository [here](https://github.com/luse9638/mixify).

## Requirements
This final project involved implementing a website with the following features:
- A login page
- A registration page
- A home page
- A server that allows the UI to communicate with the database
- A database that stores user information
- Passwords must be hashed and stored in the database
- Session Management - The user must be able to log in and out of the application and the session must be maintained
- Application is built within Docker containers

## Contributions

The share of the group project that I implemented included:
- allowing the user to log in to the website using their Spotify account
- making requests to the Spotify API to gather information about the user, such as their username, profile picture, and most listened to songs, as well as storing all of this in the database
- updating the current and potential friends tables in the database and displaying this information on the website
- session management so multiple users could use the website
