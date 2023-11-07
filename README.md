# UNIKRITI WEBD ASSIGNMENT

## Introduction
Hello, I am Snigdha Parashar, and I'm excited to present my solution for the WEBD (Web Development) assignment. In this assignment, I have developed a comprehensive webpage that features a 3D T-shirt customization tool using the three.js framework. Users can interact with the 3D T-shirt model by adjusting its scale, rotation, and most importantly, changing its color to suit their preferences. I've also integrated a backend system with MongoDB to store and retrieve user color preferences.

## Getting Started
To get started with the project, please follow the steps below:

1. Clone the repository from the GitHub link provided.

2. Install the necessary dependencies for both the frontend and backend. You can do this by running the following commands in the respective project folders:
   ```bash
   # Navigate to the frontend folder
   cd frontend/
   npm install

   # Navigate to the backend folder
   cd backend/
   npm install
3. Start the development server for both the frontend and backend using the following commands:
   ```bash
   # Copy code
   # Start the frontend development server
   cd frontend/
   npm start

   # Start the backend server
   cd backend/
   npm start
4. Visit http://localhost:3000 in your web browser to access the application.

## Usage

<li> Login: To access the T-shirt customization page, use the following login credentials:
  <li>Email: test123@example.com
  <li>Password: testpassword
    <li>T-shirt Customization: Once logged in, you can customize the 3D T-shirt by:
      <li>Adjusting the scale and rotation.
        <li>Changing the T-shirt color to your preference.
          <li>Real-time Preferences Saving: Your color preferences are saved in real-time to the backend database. This functionality is powered by WebSockets, allowing seamless communication between the frontend and backend.
