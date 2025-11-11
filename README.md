# Clyra Fullstack Project

A fashion e-commerce web application allowing users to buy and rent clothes.

## Project Structure

- `/client`: React frontend for Clyra
- `/server`: Node.js/Express backend API

## Setup Instructions

### Prerequisites
- Node.js (v16+ recommended)
- npm

### Client (Frontend)
```
cd client
npm install
npm start
```
Runs the React SPA on [http://localhost:3000](http://localhost:3000)

### Server (Backend)
```
cd server
npm install
npm start # (or) node index.js
```
API will be served on [http://localhost:5000](http://localhost:5000)

## Development
- Frontend and backend run independently – connect using HTTP requests (fetch/axios to `/api/...`).
- To begin API expansion, edit `server/index.js`.
- To add UI pages or components, edit files inside `client/src/`.

## Future Ideas
- Integrate a real database (MongoDB, PostgreSQL etc.)
- User authentication and authorization
- Better error handling, logging, and testing.

## License
MIT
