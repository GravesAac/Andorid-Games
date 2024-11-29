# Andorid Games -- CSC207 Project

## Description

**Android Games** is an Android app that features a collection of three mini-games: **Tetris**, **Rhythm Game**, and **Maze**.

### Features

- **REST API Server**  
  Manages individual user accounts through a login page, local statistics for each game, and global leaderboards.

- **Tetris Game**  
  - Dynamic acceleration for gameplay.  
  - Custom 7-piece generation algorithm ensures an even spread of player-desired pieces.

- **Rhythm Game**  
  - Two game modes:  
    - **Song Mode**: Notes are tuned to the beat with specific intervals.  
    - **Random Mode**: Notes are generated randomly with increasing difficulty over time.

- **Maze Game**  
  - Recursive random maze generation algorithm.  
  - Offers two types of controls for navigation.

- **Wrapper Game Mode**  
  - Play through all three games sequentially.  
  - Scores and statistics are cumulative across the games.

---

## Installation Guide

1. **Set up the REST API:**
   - Open IntelliJ IDEA.  
   - Navigate to: **Check out from Version Control -> Git -> Clone the following repository:**  
     `https://github.com/mooncrest/CSC207RestApi`
   - Open `rest api/src/main/java/CSC207/CSC207RestApi/Csc207RestApiApplication.java` and run the file with the **Application configuration**.

2. **Set up the Android app:**
   - Clone the project into Android Studio.

3. **Configure IP Address:**
   - Find your computer’s IP address and copy it.  
   - Open `phase2/app/src/main/java/uoft/csc207/gameapplication/Utility/GameRequestService/RestApiConnector.java` and replace the `String URL` value with your IP address.  
     - Don’t forget to append the `:8080/` suffix!

4. **Run the app:**
   - Use the **Pixel 3 XL emulator** with **Android 9.0** in Android Studio.

5. **Log in:**
   - Use the following credentials:  
     - Username: `admin`  
     - Password: (No password required)  
   - Alternatively, create a new account and log in.

