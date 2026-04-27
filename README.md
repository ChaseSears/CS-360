# CS-360 Event Tracker App

# Overview
The Event Tracker App is a mobile application developed in Android Studio using Java. The purpose of this app is to allow users to create, view, and manage events in a simple and organized way. The app was designed with a focus on usability and accessibility so that users can easily track important dates and activities.

# Features
- User login, account creation, and guest access
- Event creation with name, date, and time
- Event grid display for viewing all events
- Date and time selection using dialog pickers for accuracy
- Simple and clean user interface design
- Input validation to prevent incorrect data entry

# Technology Used
- Java
- Android Studio
- XML for layout design

# Application Structure
The application is built using multiple activities and layouts:
- MainActivity
  Handles the main screen where users can log in, create an account, or continue as a guest
- EventGridActivity
  Displays the list of events in a grid format
- XML Layout Files
  Define the user interface for each screen

The app follows a basic structure where user interactions trigger actions through buttons, and data is displayed in a grid format.

# How It Works
When the app starts, the user is presented with three options: login, create an account, or continue as a guest. After entering the app, users can create events by entering details such as event name, date, and time. Date and time are selected using dialog pickers to ensure valid input. Once created, events are displayed in a grid layout for easy viewing.

# Installation Instructions
1. Open Android Studio
2. Select “Open an Existing Project”
3. Navigate to the project folder
4. Allow Gradle to sync
5. Run the application using an emulator or a physical Android device

# Future Improvements
- Implement user authentication with saved accounts
- Improve UI design with additional styling and themes

# Challenges and Learning Experience
One of the main challenges during development was ensuring that user input was valid, especially for date and time fields. Using dialog pickers helped solve this issue. Another challenge was structuring the app so that navigation between screens worked smoothly. Overall, this project helped improve my understanding of Android development, UI design, and handling user interactions.

