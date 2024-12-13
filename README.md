# Expense-Tracker
AI Powered Expense Tracker with Budget Forecasting

## Expense-Tracker
An AI-Powered Expense Tracker with Budget Forecasting, designed to help users track their expenses, forecast future budgets, and manage their finances efficiently.

## Features
Frontend: Developed using ReactJS for a responsive and interactive UI.
Backend: Built with Node.js and Express for secure and efficient API handling.
Budget Forecasting: Uses AI models (Linear Regression, ARIMA, LSTM) to predict future expenses based on historical data.
Dynamic Data Handling: Data stored and managed in a MongoDB database.
User Authentication: Secure login and sign-up functionality using JWT (JSON Web Tokens).

## Folder Structure
Frontend: Contains the ReactJS code for the user interface.
Backend: Contains the Node.js/Express API and business logic.
my_env: Placeholder for virtual environment files or sensitive configurations (e.g., .env files).

## Prerequisites
Ensure the following are installed on your system:

1. Node.js (v14 or above)
2. MongoDB (Local or Cloud Instance)
3. Python (if required for AI model integration)

## Setup Instructions
### Step 1: Clone the Repository
bash
git clone https://github.com/Akhil-Chopra/Expense-Tracker.git
cd Expense-Tracker

### Step 2: Backend Setup
1. Navigate to the backend folder:
bash
cd Backend

2. Install dependencies:
bash
npm install

3. Create a .env file in the backend folder with the following variables:
makefile
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret_key
PORT=5000

4. Start the backend server:
bash
npm start

### Step 3: Frontend Setup
1. Navigate to the frontend folder:
bash
cd ../Frontend

2. Install dependencies:
bash
npm install

3. Start the development server:
bash
npm start

4. Open your browser and go to:
arduino
http://localhost:3000


## How to Run the Project

1. Start MongoDB on your local machine or connect to your cloud database.
2. Start the backend server using the instructions above.
3. Start the frontend React server and access the application in your browser.

## AI Models
The AI models (ARIMA, LSTM, Linear Regression) for budget forecasting are implemented in Python. These models are run as a separate service or batch process. For integration:
1. Set up a Python virtual environment and install dependencies from the requirements.txt file.
2. Run the forecasting scripts and connect the outputs to the backend API.

## Troubleshooting
If node_modules is missing, run npm install in both the frontend and backend directories.
Ensure MongoDB is running before starting the backend server.

## Contributors
Akhil Chopra – Developer and Designer.

## License
This project is licensed under the MIT License.

