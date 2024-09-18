# Quiz App

This is a React-based Quiz application configured to use AWS Amplify and Cognito for authentication. The app includes a series of quiz questions and answers, which are managed via a simple UI.

## Features

- **Authentication**: Integrated with AWS Cognito for secure user authentication.
- **Quiz Component**: Displays and manages quiz questions and answers.
- **Hard-Coded Data**: Uses a local file (`quizData.js`) for quiz questions and answers.

## Getting Started

To get started with this project, follow these instructions to set up the development environment and configure AWS Amplify.

### Prerequisites

Ensure you have the following installed:

- [Node.js](https://nodejs.org/) (for running the React app and managing dependencies)
- [Git](https://git-scm.com/) (for version control)

### Installation

1. **Clone the Repository**

   ```bash
   git clone https://github.com/yourusername/quiz-app.git
   cd quiz-app

Set Up AWS Amplify
Note: The Amplify deploy is not live after September 18, 2024, due to cost considerations. To set up Amplify on your own, follow these steps:

2. **Initialize Amplify**

    ```bash
    amplify init

3. **Add authentication**

    ```bash
    amplify add auth

3. **Deploy your Amplify configuration**

    ```bash
    amplify push

4. **Install AWS Amplify dependencies:**

    ```bash
    npm install aws-amplify @aws-amplify/ui-react

5. **Usage**

Start the React Application

    ```bash
    npm start

This will start the development server and open the application in your default browser.

## Navigate to the Quiz
Once the application is running, you can navigate to the quiz component to start taking the quiz.

## Project Structure
App.js: The main React application configured for AWS Cognito authentication.
Quiz.js: The component that renders the quiz questions and handles user interactions.
quizData.js: Contains hard-coded questions and answers for the quiz.

Contributing
Feel free to open issues or submit pull requests if you have suggestions or improvements.


For further questions or issues, please refer to the AWS Amplify documentation or the React documentation.