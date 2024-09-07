Project Title: Name Prediction App
Overview
The Name Prediction App is a simple web application that predicts a person's age, gender, and nationality based on their name. It leverages three external APIs—Agify, Genderize, and Nationalize—to fetch and display the predictions in a clean and user-friendly interface.

Features
Age Prediction: Estimates the likely age of a person based on their name using the Agify API.
Gender Prediction: Determines the likely gender of a person based on their name using the Genderize API.
Nationality Prediction: Predicts the likely nationality of a person based on their name using the Nationalize API.
Responsive UI: The application is styled to be visually appealing and responsive, making it accessible on both desktop and mobile devices.
Technologies Used
React.js: The front-end library used to build the user interface.
TypeScript: Used for type safety and enhancing the development process.
APIs:
Agify API: For predicting age.
Genderize API: For predicting gender.
Nationalize API: For predicting nationality.
Tailwind CSS: For styling the components.
Installation
To run this project locally, follow these steps:

Clone the repository:

git clone https://github.com/avinashsahni/name-prediction-app.git
cd name-prediction-app

Install dependencies:

npm install

Start the development server:

npm run dev
Open the app: Open your browser and go to http://localhost:3000 to see the app in action.

Usage

Enter a name into the input field.
The app will display the predicted age, gender, and nationality associated with that name.
Code Explanation
API Functions: The app defines three asynchronous functions to fetch data from the respective APIs:

getPredictedAge(name: string): Fetches age prediction.
getPredictedGender(name: string): Fetches gender prediction.
getPredictedNationality(name: string): Fetches nationality prediction.
Prediction Component: The Prediction component receives the name parameter, calls the API functions concurrently using Promise.all, and renders the results in a card-like UI.

Styling: The component is styled using Tailwind CSS, ensuring a modern and responsive design.

Contributing

Contributions are welcome! If you have any suggestions or improvements, feel free to submit a pull request or open an issue.

License

This project is licensed under the MIT License. See the LICENSE file for details.
