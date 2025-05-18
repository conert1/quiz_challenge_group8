# quiz_challenge_group8
BBD_Challenge

# Tech Quiz App

An interactive web-based quiz app built with **HTML**, **CSS**, **JavaScript**, and **Firebase**. Users can choose a quiz category, answer timed questions, and view a real-time leaderboard. Great for testing your knowledge in tech domains like JavaScript, Backend, Databases, and AI!

## Features

-  Selectable quiz categories
-  Timed multiple-choice questions
-  Live progress bar and timer
-  Instant feedback on answers
-  Leaderboard with filter by category
-  Firebase Firestore integration for real-time data
 
## Technologies Used

- **HTML5** & **CSS3**
- **Vanilla JavaScript**
- [**Firebase Firestore**](https://firebase.google.com/docs/firestore) – for storing quiz data and scores


## Firebase Setup

This project uses Firebase Firestore to fetch questions and save scores.

### Firestore Collections:
- `categories`: stores documents for each category (e.g., `javascript`, `backend`) containing:
  ```js
  {
    numberOfQuestions: 10,
    questions: [
      {
        question: "What is a closure?",
        options: ["...", "...", "...", "..."],
        correct: "..."
      },
      ...
    ]
  }


{
  name: "Alice",
  score: 90,
  category: "ai",
  timestamp: <Firebase Server Timestamp>
}


## How It Works

    User enters their name and selects a category.
    Questions are fetched from Firestore and shuffled.
    A timer (10 seconds/question) begins.
    User selects answers; results are tracked and scored.
    Final score and detailed answer review are shown.
    Score is saved to the Firestore scores collection.
    Leaderboard updates in real time with filter options.


## Admin side  

This is the Admin Panel for the Tech Quiz App, a quiz management system built using HTML, CSS, JavaScript, and Firebase Firestore.

Admins can:
    Set the number of quiz questions per category.
    Add questions with options and correct answers.
    Organize quizzes across multiple tech categories


Technologies Used
    Firebase Firestore – Real-time database
    JavaScript (ES6 Modules) – Dynamic logic and Firestore integration
    HTML/CSS – Layout and styling





