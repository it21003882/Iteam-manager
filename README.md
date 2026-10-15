# Item Manager

A MERN item manager lab project with separate frontend and backend applications.

## Project structure

- `frontend/` – React and Vite user interface
- `backend/` – Express API with MongoDB and Mongoose

## Run locally

1. In `backend/`, install dependencies with `npm install` and copy `.env.example` to `.env`.
2. Set `MONGO_URI` in `backend/.env` to your MongoDB connection string.
3. Start the API with `npm run dev` (default: `http://localhost:5000`).
4. In `frontend/`, install dependencies with `npm install` and copy `.env.example` to `.env`.
5. Set `VITE_API_URL=http://localhost:5000/api` in `frontend/.env` and run `npm run dev`.

The item form supports create and edit operations. Each item includes a discount percentage from 0 to 100, displayed on the Home page.
