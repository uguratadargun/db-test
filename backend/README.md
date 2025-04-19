# Simple Node.js Backend

A basic Express.js API ready to be deployed to a free hosting service.

## Setup

1. Clone the repository
2. Install dependencies:
   ```
   npm install
   ```
3. Create a `.env` file (or use the existing one)
4. Run the development server:
   ```
   npm run dev
   ```

## Deployment Options

This API can be deployed for free to various platforms:

### Render

1. Create an account at [render.com](https://render.com)
2. Create a new Web Service
3. Connect your repository or upload your code
4. Set the build command to `npm install`
5. Set the start command to `npm start`
6. Deploy!

### Railway

1. Create an account at [railway.app](https://railway.app)
2. Create a new project
3. Deploy from GitHub or upload your code
4. Add environment variables if needed
5. Your app will be automatically deployed

### Fly.io

1. Create an account at [fly.io](https://fly.io)
2. Install the Flyctl CLI
3. Run `fly launch` in your project directory
4. Follow the prompts to deploy

## API Endpoints

- `GET /`: Welcome message
- `GET /api/status`: Server status and timestamp
