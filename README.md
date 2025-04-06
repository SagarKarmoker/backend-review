# Chai Aur Backend

A TypeScript-based Express backend project for learning and development purposes.

## Description

This project is a simple Express.js backend application written in TypeScript. It provides a foundation for building RESTful APIs and web applications with modern JavaScript features and type safety.

## Features

- TypeScript for type safety and modern JavaScript features
- Express.js for handling HTTP requests
- Nodemon for automatic server restarts during development
- Structured project organization

## Prerequisites

- Node.js (v14 or higher recommended)
- npm or yarn

## Installation

```bash
# Clone the repository (if applicable)
# git clone <repository-url>

# Navigate to the project directory
cd chai-aur-backend

# Install dependencies
npm install
```

## Available Scripts

```bash
# Start the development server with hot-reload
npm run dev

# Build the project for production
npm run build

# Start the production server
npm start
```

## Project Structure

```
├── src/                  # Source directory
│   ├── index.ts          # Application entry point
├── dist/                 # Compiled JavaScript files (generated)
├── package.json          # Project dependencies and scripts
├── tsconfig.json         # TypeScript configuration
├── .gitignore            # Git ignore file
└── README.md             # Project documentation
```

## Development

To start the development server:

```bash
npm run dev
```

The server will restart automatically when you make changes to the source files.

## Building for Production

To build the project for production:

```bash
npm run build
```

This will compile TypeScript files to JavaScript in the `dist` directory.

## Running in Production

To run the application in production mode:

```bash
npm start
```

## Dependencies

### Main Dependencies

- express: Fast, unopinionated, minimalist web framework for Node.js

### Development Dependencies

- typescript: JavaScript with syntax for types
- nodemon: Monitor for any changes in your source and automatically restart your server
- ts-node: TypeScript execution and REPL for Node.js
- ts-node-dev: Tweaked version of ts-node that enables watching files
- @types/express: TypeScript definitions for Express
- @types/node: TypeScript definitions for Node.js

## License

ISC