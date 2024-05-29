# PassBox

A secure and user-friendly password manager built with React, Node.js, and MongoDB.

This application allows users to safely store and manage their passwords, ensuring strong encryption and easy access across devices.

## Features

- User registration and login with OAuth authentication
- Secure password storage with client-side encryption
- Password generation for creating strong and unique passwords
- Bundling with Vite
- State management using MobX
- Data storage with MongoDB
- UI built with Ant Design
- Unit testing with Jest and React Testing Library

## Getting Started

### I run the following commands to initialize the project:

- npm init -y
- npm install react react-dom mobx mobx-react-lite antd bcrypt jsonwebtoken mongoose vite @vitejs/plugin-react
- npm install -D jest @testing-library/react @testing-library/jest-dom
- npm install --save-dev eslint @eslint/js eslint-plugin-react globals
- npx eslint --init
- npm install -D typescript @types/react @types/react-dom @types/node @types/jest
- nvm use 18.17.1
- npm run lint

### Prerequisites

- Node.js (v18 or higher)
- MongoDB (v4 or higher)

### Installation

1. Clone the repository:
   git clone https://github.com/valentino22/PassBox

2. Install the dependencies:

   cd PassBox

   npm install

3. Set up environment variables:

- Create a `.env` file in the project root.
- Define the following variables:
  ```
  MONGODB_URI=your-mongodb-connection-string
  JWT_SECRET=your-jwt-secret
  OAUTH_CLIENT_ID=your-oauth-client-id
  OAUTH_CLIENT_SECRET=your-oauth-client-secret
  ```

4. Start the development server:
   npm run dev

5. Open your browser and visit `http://localhost:3000` to access the application.

### Running Tests

To run the unit tests, use the following command:
npm test

To run tests in watch mode, use:
npm run test:watch

### Building for Production

To build the optimized production bundle, run:
npm run build

The production-ready files will be generated in the `dist` directory.

## Contributing

Contributions are welcome! If you find any issues or have suggestions for improvements, please open an issue or submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE).
