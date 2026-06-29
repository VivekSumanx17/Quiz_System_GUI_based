# Quiz Management System (Java Swing + Database)

A GUI-based Quiz Management System developed using Java Swing and Database integration. 
This project allows users to attempt quizzes through an interactive interface, fetches 
questions from a database, and automatically evaluates scores.

# Project Overview

This application replaces traditional console-based quizzes with a Graphical User Interface (GUI)
built using Java Swing. Quiz questions are stored in a database, making the system dynamic, 
scalable, and easy to update without changing the source code.

# Features

  Interactive GUI using Java Swing
  Multiple-choice questions (MCQs)
  Questions loaded dynamically from database
  Automatic score calculation
  Next / Submit button navigation
  User-friendly design
  Easy to extend with more questions

# Technologies Used

  Java (JDK 8+)
  Java Swing (GUI)
  JDBC (Database Connectivity)
  MySQL / SQLite (any one can be used)

# Set Up Database

  file::- question.ibd 
  this file is dataset file of MYSQL. Save it in you localhost and use it.

 this Query for connecting database 

    String url = "jdbc:mysql://localhost:3306/quiz_db";
    String user = "root";               /* Enter your mysql username
    String password = "your_password";  /* Enter your mysql password

# How to run this on console:-

    javac -cp ".;mysql-connector-j-9.4.0.jar" QuizSystem.java
    java -cp ".;mysql-connector-j-9.4.0.jar" QuizSystem
    
# Sample Flow

  Application opens with GUI window
  Question displayed with 4 options (Radio Buttons)
  User selects an answer and clicks Next
  Final score displayed at the end

# Future Enhancements

  Login system for users
  Admin panel to add/update questions
  Timer-based quiz
  Store user scores in database
  Result analysis with charts

 <img width="611" height="491" alt="Screenshot 2026-06-29 141323" src="https://github.com/user-attachments/assets/44ab4d94-b5f1-456b-bed1-26e2811f5f38" />
 <img width="1441" height="496" alt="Screenshot 2026-06-29 141336" src="https://github.com/user-attachments/assets/9e6a799f-0f42-4eaa-be59-19c8aa92a384" />
<img width="485" height="363" alt="Screenshot 2026-06-29 141412" src="https://github.com/user-attachments/assets/3f83eb5b-0a4a-4041-a815-2a4baf3a384f" />

