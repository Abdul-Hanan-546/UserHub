# UserHub – Flutter Firebase App

UserHub is a Flutter mobile application developed as an internship project.  
The main purpose of this app is to practice Firebase authentication, Firestore
integration, and proper app flow using Flutter.

## Features
- Splash Screen on app start
- User Sign Up (Email & Password)
- User Login
- Google Sign-In
- Forgot Password (Email reset)
- Firebase Authentication
- Cloud Firestore user storage
- Real-time Users List
- User profile image (Google users)
- Refresh users list
- Delete user from Firestore
- Loading & error handling screens

## Technologies Used
- Flutter
- Firebase Authentication
- Cloud Firestore
- Google Sign-In
- Provider (State Management)

## App Flow
1. App starts with Splash Screen  
2. Authentication check (Login / Sign Up)  
3. User is redirected to Users List after successful login  
4. Users are loaded from Firestore in real time  

## Notes
- Firebase is required to run this project
- Google Sign-In and Email/Password authentication must be enabled
- Firestore database must be created in Firebase Console

## Purpose
This project was created for learning and internship purposes to understand
real-world Flutter app development with Firebase backend integration.
