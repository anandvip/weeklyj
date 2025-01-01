# Weekly Journal

## Overview
Weekly Journal is a web application that allows users to maintain a weekly journal. Users can sign in with their Google account, create new journal entries, and view or edit existing entries.

## Features
- **User Authentication**: Sign in and sign out using Google authentication.
- **Journal Management**: Create, view, and edit journal entries.
- **Firebase Integration**: Store and retrieve journal entries using Firestore.
- **Responsive Design**: A flexible layout that adapts to different screen sizes.

## Technologies Used
- **HTML**: For structuring the web page.
- **CSS**: For styling the web page.
- **JavaScript**: For interactive functionality and Firebase integration.
- **Firebase**: For authentication and Firestore database.

## Firebase Configuration
The application is configured to use Firebase services. The Firebase configuration object is included in the JavaScript:

```javascript
const firebaseConfig = {
    apiKey: "AIzaSyB00L-6PsCK5LMAVbUPXgNNF0BywlZKqwk",
    authDomain: "weekly-journal-9df9c.firebaseapp.com",
    projectId: "weekly-journal-9df9c",
    storageBucket: "weekly-journal-9df9c.appspot.com",
    messagingSenderId: "267644429656",
    appId: "1:267644429656:web:8a5b8a73960f9adf5af12d"
};
