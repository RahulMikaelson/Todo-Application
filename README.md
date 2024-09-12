# Todo App

This project contains a simple **Todo** app built with **React**, which serves as a common frontend for two separate backend implementations: one using **Spring Boot** and the other using **Express.js**.

Users can interact with either backend, while the frontend remains the same, providing flexibility and showcasing different backend technologies.

## Features

- **React Frontend**: Single-page application for managing todos.

- **Spring Boot Backend**: Java-based backend with REST API.

- **Express.js Backend**: Node.js-based backend with REST API.

## Setup Instructions

### Prerequisites

- **Node.js** and **npm** (for React and Express.js).

- **Java** and **Maven** (for Spring Boot).

### Frontend Setup

1. Navigate to the `Frontend` directory:

```bash

cd todo-frontend-react

```

2. Install dependencies:

```bash

npm install

```

3. Start the React development server:

```bash

npm run dev

```

### Spring Boot Backend Setup

1. Navigate to the `Spring Boot Backend` directory:

```bash

cd todo-backend-java

```

2. Build and run the Spring Boot application:

```bash

mvn spring-boot:run

```

### Express.js Backend Setup

1. Navigate to the `Express Backend` directory:

```bash

cd todo-backend-node

```

2. Install dependencies:

```bash

npm install

```

3. Start the Express server:

```bash

node index.js

```

## Switching between Backends

To switch between using the **Spring Boot** or **Express.js** backend, update the API base URL in the React frontend configuration.
