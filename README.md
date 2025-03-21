# DesirableDifficult Backend

A robust backend server for the DesirableDifficult Dutch language learning application, built with Node.js, Express, and TypeScript.

## Features

- User authentication and authorization
- AI-powered language learning assistance
- Practice session management
- User progress tracking
- Secure API endpoints
- Rate limiting and security measures

## Tech Stack

- Node.js
- Express.js
- TypeScript
- MongoDB with Mongoose
- OpenAI API integration
- JWT for authentication
- Jest for testing

## Prerequisites

- Node.js (v14 or higher)
- MongoDB
- OpenAI API key

## Installation

1. Clone the repository:
```bash
git clone https://github.com/li6834300/DesirableDifficult-Backend.git
cd DesirableDifficult-Backend
```

2. Install dependencies:
```bash
npm install
```

3. Create a `.env` file in the root directory and add your environment variables:
```bash
cp .env.example .env
```
Then edit the `.env` file with your configuration values.

## Available Scripts

- `npm start` - Start the production server
- `npm run dev` - Start the development server with hot-reload
- `npm run build` - Build the TypeScript code
- `npm test` - Run tests
- `npm run lint` - Run ESLint

## Project Structure

```
src/
├── config/         # Configuration files
├── controllers/    # Route controllers
├── middleware/     # Custom middleware
├── models/         # Database models
├── routes/         # API routes
├── services/       # Business logic
├── types/          # TypeScript type definitions
└── index.ts        # Application entry point
```

## API Documentation

The API provides endpoints for:
- User authentication (login, register, logout)
- Practice sessions
- User progress tracking
- AI-powered language learning assistance

## Security

- JWT-based authentication
- Password hashing with bcrypt
- Rate limiting
- CORS enabled
- Helmet for security headers
- Environment variable protection

## Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Contact

Your Name - [@your_twitter](https://twitter.com/your_twitter) - email@example.com

Project Link: [https://github.com/li6834300/DesirableDifficult-Backend](https://github.com/li6834300/DesirableDifficult-Backend) 