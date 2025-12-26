## Clyra Fullstack Project

A fashion e-commerce web application allowing users to buy and rent clothes.

### Project Structure

- `frontend/`: React SPA (customer-facing UI)
- `backend/`: Node.js/Express REST API

> The older `client/` and `server/` folders have been recreated as `frontend/` and `backend/`.  
> Use the new folders for future development.

### Prerequisites

- Node.js (v16+ recommended)
- npm

### Frontend (`frontend/`)

```bash
cd frontend
npm install
npm start         # or: npm run dev (alias)
```

By default this runs the React app on [http://localhost:3000](http://localhost:3000).

### Backend (`backend/`)

```bash
cd backend
npm install
npm start         # or: npm run dev
```

The API server listens on [http://localhost:5000](http://localhost:5000).

### Development Notes

- Frontend and backend run independently – connect via HTTP requests (e.g. `fetch`/`axios` to `/api/...` or `http://localhost:5000/...`).
- To extend the API, edit `backend/index.js`.
- To add or change UI, edit files inside `frontend/src/`.

### Future Ideas

- Integrate a real database (MongoDB, PostgreSQL, etc.).
- Add user authentication and authorization.
- Improve error handling, logging, and automated testing.

### License

MIT
