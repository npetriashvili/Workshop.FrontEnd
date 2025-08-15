# Workshop Guide: Front-End Task

Welcome, Back-End Team! Your mission is to display a new piece of data in our React application.

## Your Goal

Display the `jobTitle` property (which you just added to the API) on the user's profile page.

### Step 1: Find the File

The main file you'll need to modify is the user profile component:

* Path: `src/UserProfile.js`

You may also need to check the API URL in `src/api.js` to ensure it matches the port your .NET API is running on.

### Step 2: Run the Project

1. Open a terminal or command prompt in the front-end project folder.

2. Run `npm install` to download all the necessary packages. (You only need to do this once).

3. Run `npm start` to build the project and open it in your browser. The page will automatically reload if you make changes to the code.

### Step 3: Your Task

1. In `src/UserProfile.js`, find the `return (...)` block. This is the HTML-like code (called JSX) that gets rendered to the page.

2. Add a new element to display the `jobTitle` from the `user` object. For example: `<h3>{user.jobTitle}</h3>`.

3. Save the file and look at your browser. The page should update automatically to show the new job title.

**Remember:** Your front-end partner is your "Navigator." They can't touch the keyboard, but they are here to guide you and answer any questions you have about React, JSX, or VS Code!
