# Event Tracker

Event Tracker is a React-based application designed to help users manage their schedules effectively. This application allows users to view, create, and manage events on a calendar. It features an intuitive interface and supports both daily and weekly views.

<img src="screencapture.png" alt="Event Tracker Image" width="50%">

## 🔨 Project Features

- **Event Management:** Add, update, and delete events on the calendar.
- **Calendar Views:** Switch between daily and weekly views to manage your schedule.
- **Customizable:** Personalize event details including start and end times, descriptions, and colors.
- **Responsive Design:** The app is designed to be used on both desktop and mobile devices.

## ✔️ Technologies and Techniques Used

This project was developed using the following technologies:

- `React`
- `TypeScript`
- `SCSS`
- `Recoil` for state management
- `JSON Server` for mock API

## 🛠️ Running the Project Locally

To run the project locally, follow these steps:

1. **Install Dependencies:** Run `npm install` to install the necessary dependencies.
2. **Set Up JSON Server:**
   - Ensure you have `json-server` installed globally (`npm install -g json-server`).
   - Create a `db.json` file in the root directory with the following structure:

     ```json
     {
       "eventos": [
         {
           "descricao": "Study React",
           "inicio": "2022-01-15T09:00",
           "fim": "2022-01-15T13:00",
           "completo": false,
           "id": 101
         },
         // Add more events as needed
       ]
     }
     ```

   - Start the JSON Server with the command `json-server --watch db.json --port 8080`.
3. **Start the React Application:** Run `npm start` to launch the application.
4. **Access the Application:** Open <a href="http://localhost:3000/">http://localhost:3000/</a> in your browser.

## 📚 Course Information

This project was developed as part of the **Integrating Your React Project with APIs** course offered by Alura. The course provides a comprehensive guide on integrating React applications with APIs and managing application state.
