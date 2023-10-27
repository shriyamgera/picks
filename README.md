## Betting Website

This is a web application for a betting website built using React JavaScript and the MERN stack (MongoDB, Express, React, and Node.js).

## Features

- User authentication and authorization using JWT (JSON Web Tokens)
- Ability to place bets on various sports events
- Live updates of sports events and betting odds
- Account management for users, including viewing betting history and account balance
- Admin panel for managing sports events, betting odds, and user accounts

## Technologies Used

- React: A popular JavaScript library for building user interfaces
- Redux: A state management library for managing global state in the application
- Node.js: A JavaScript runtime for server-side development
- Express: A web application framework for Node.js
- MongoDB: A NoSQL database for storing and managing data
- Mongoose: An Object Data Modeling (ODM) library for MongoDB
- Passport: A middleware for user authentication and authorization
- Axios: A popular HTTP client for making API requests
- Tailwind: A CSS framework for building responsive web pages
- Socket.io: A library for real-time bidirectional communication between the client and server

These technologies are subject to change in future as we build our website.

## Installation

1. Clone the repository: `git clone <repository-url>`
2. Navigate to the project directory: `cd betting-website`
3. Install the dependencies for the client: `cd client && npm install`
4. Install the dependencies for the server: `cd ../server && npm install`
5. Set up environment variables:
   - Create a `.env` file in the `server` directory
   - Define the following environment variables:
     ```
     PORT=<port-number>
     MONGODB_URI=<mongodb-uri>
     SECRET_KEY=<secret-key-for-jwt>
     ```
6. Start the client and server concurrently: `npm run dev`
7. Open your web browser and go to `http://localhost:3000` to access the betting website.

## Usage

- Register an account or log in to an existing account
- Browse sports events and view the betting odds
- Place bets on sports events
- View account balance, betting history, and open bets
- Admins can manage sports events, betting odds, and user accounts through the admin panel

## Contributing

If you would like to contribute to this project, please follow these steps:

1. Fork the repository
2. Create a new branch for your feature/bugfix: `git checkout -b feature-name`
3. Make your changes and commit them: `git commit -m "Description of your changes"`
4. Push your changes to the forked repository: `git push origin feature-name`
5. Create a pull request against the `main` branch of the original repository


## Acknowledgements

- [React](https://reactjs.org/)
- [Redux](https://redux.js.org/)
- [Node.js](https://nodejs.org/)
- [Express](https://expressjs.com/)
- [MongoDB](https://www.mongodb.com/)
- [Mongoose](https://mongoosejs.com/)
- [Passport](http://www.passportjs.org/)
- [Axios](https://axios-http.com/)
- [Bootstrap](https://getbootstrap.com/)
- [Socket.io](https://socket.io/)

## Contact

If you have any questions or suggestions, please feel free to contact the project owner:

- [Utkarsh](mailto:hauntedutkarsh@gmail.com)