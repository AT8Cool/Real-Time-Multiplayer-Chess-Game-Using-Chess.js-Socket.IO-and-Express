# Real-Time-Multiplayer-Chess-Game-Using-Chess.js-Socket.IO-and-Express

Dive into the strategic world of chess with this real-time multiplayer chess game. Built using Chess.js for game logic, Socket.IO for seamless real-time communication, and Express for a robust server-side framework, this chess clone allows players to compete against each other from different locations.

## Features

- Real-time multiplayer chess gameplay
- Move validation using Chess.js
- Live game updates via Socket.IO
- Simple and intuitive web interface
- Support for standard chess rules

## Installation

1. Clone the repository:
   ```
   git clone https://github.com/AT8Cool/Real-Time-Multiplayer-Chess-Game-Using-Chess.js-Socket.IO-and-Express.git
   cd Real-Time-Multiplayer-Chess-Game-Using-Chess.js-Socket.IO-and-Express
   ```

2. Install dependencies:
   ```
   npm install
   ```

3. Start the server:
   ```
   npm start
   ```

4. Open your browser and navigate to `http://localhost:3000`

## Usage

- Open the application in multiple browser tabs or windows to simulate multiplayer.
- Players can join a game and make moves in real-time.
- The game enforces chess rules and validates moves.

## Deployment

This application can be deployed to platforms like Heroku, Vercel, or any Node.js hosting service.

### Heroku Deployment

1. Create a Heroku account and install the Heroku CLI.
2. Login to Heroku:
   ```
   heroku login
   ```
3. Create a new Heroku app:
   ```
   heroku create your-app-name
   ```
4. Push the code to Heroku:
   ```
   git push heroku main
   ```
5. Open the app:
   ```
   heroku open
   ```

Make sure to set the PORT environment variable if needed (Heroku does this automatically).

## Technologies Used

- **Chess.js**: For chess game logic and move validation
- **Socket.IO**: For real-time communication between clients and server
- **Express**: For the server-side framework
- **EJS**: For templating the views

## Contributing

Contributions are welcome! Please fork the repository and submit a pull request.

## License

This project is licensed under the MIT License. 
