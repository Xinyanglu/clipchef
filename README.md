# ClipChef Monorepo

Welcome to the ClipChef project! This is a monorepo containing both the frontend and backend applications.

## Project Structure

- `clipchef-frontend/`: Expo/React Native mobile application.
- `clipchef-backend/`: AWS SAM (Serverless Application Model) backend using Python.

## Prerequisites

- **Node.js**: v20 or higher (required for ES2023 features like `toReversed`).
- **AWS SAM CLI**: For local backend development and deployment.
- **Python 3.13**: For backend development.

## Quick Start

### Frontend

To start the Expo development server:

```bash
npm run frontend:start
```

### Backend

To build and start the backend locally:

```bash
npm run backend:build
npm run backend:start
```

## Available Scripts (at Root)

- `npm run frontend:start`: Start the frontend application.
- `npm run frontend:install`: Install frontend dependencies.
- `npm run backend:build`: Build the backend with SAM.
- `npm run backend:start`: Start the backend API locally.
- `npm run backend:deploy`: Deploy the backend to AWS.
- `npm run install-all`: Install both root and frontend dependencies.
