# Event Planning and Reminder System

A simple Node.js Express application for managing events and reminders.

## Features

- User registration and login
- Create events with optional reminders
- List upcoming events with sorting options
- Automated testing with GitHub Actions

## Setup

1. Clone the repository
2. Install dependencies: `npm install`
3. Start the server: `npm start`
4. Run tests: `npm test`

## API Endpoints

- `POST /register` - Register a new user
- `POST /login` - Login with username and password
- `POST /events` - Create a new event (requires authentication)
- `GET /events` - List upcoming events (requires authentication)

