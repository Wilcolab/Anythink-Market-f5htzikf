# My Express App

This project is a simple Express server application that listens on port 8001. It is set up to use Nodemon for automatic code updates during development.

## Project Structure

```
my-express-app
├── src
│   └── server.js        # Entry point of the application
├── package.json         # Project configuration and dependencies
├── yarn.lock            # Dependency version locking
├── Dockerfile           # Instructions to build the Docker image
└── README.md            # Project documentation
```

## Getting Started

To get started with this project, follow the instructions below.

### Prerequisites

Make sure you have [Node.js](https://nodejs.org/) and [Yarn](https://yarnpkg.com/) installed on your machine.

### Installation

1. Clone the repository:
   ```
   git clone <repository-url>
   cd my-express-app
   ```

2. Install the dependencies:
   ```
   yarn install
   ```

### Running the Server

To start the server with automatic code updates, run:

```
yarn start
```

The server will be running on [http://localhost:8001](http://localhost:8001).

### Building the Docker Image

To build the Docker image for the application, run:

```
docker build -t my-express-app .
```

### Running the Docker Container

To run the Docker container, use the following command:

```
docker run -p 8001:8001 my-express-app
```

The server will be accessible at [http://localhost:8001](http://localhost:8001) from your host machine.