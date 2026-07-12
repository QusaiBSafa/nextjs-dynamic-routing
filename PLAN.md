# Infrastructure Overview
This application uses Next.js for the frontend and a simple API built using Node.js.

## Data Models
- User: { id: number, name: string, email: string }

## API Design
- GET /api/users: Returns a list of users.
- GET /api/users/[id]: Returns user details based on user ID.

## Key Decisions
- Using Next.js for its built-in support for dynamic routing and server-side rendering.