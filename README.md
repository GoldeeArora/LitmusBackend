## Guess Game Backend

The Connect Game Backend is built using Node.js, and it provides the API endpoints necessary for the Connect Game to function. This README file provides instructions on how to set up and run the backend server.

### Installation

To install the Guess Game Backend, follow the steps below:

1.Clone this repository to your local machine using git clone https://github.com/GoldeeArora/LitmusBackend.git

2.Navigate to the project directory using cd LitmusBackend

3.Install the required dependencies using npm install

4.Create a .env file in the root directory, and add the following variables:
  MONGO_URI
  
5.Run the server using npm start

### API Endpoints

The Connect Game Backend provides the following API endpoints:

### GET /app/user/findAllUser
    This endpoint returns an array of JSON object containing list of all users.
    
### GET /app/leaderboard/findRanking
    This endpoint returns an array of JSON object containing list of all users sorted according to score and ranks of users who have completed the game
    
### POST /app/image/fetchLevelImages
    This endpoint returns an array of 4 images for the level the current user is on.
    
### Technologies Used
The Connect Game Backend was built using the following technologies:

1.Node.js: a JavaScript runtime for building server-side applications

2.Express: a Node.js framework for building web applications

3.MongoDB: a NoSQL document database used to store high scores data
