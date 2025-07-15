# EasyNotes API

A simple RESTful CRUD API for note-taking built with Node.js, Express, and MongoDB.

## Installation

```bash
npm install
```

## Configuration

Create a `.env` file:
```env
PORT=3000
MONGO_URI=mongodb+srv://<db_user>:<db_password>@user.vx3pm.mongodb.net/notes
```

## Usage

Start the server:
```bash
npm start
```

API available at: `http://localhost:3000`

## API Endpoints

| Method | Endpoint | Description |
|--------|----------|-------------|
| GET | `/notes` | Get all notes |
| POST | `/notes` | Create a note |
| GET | `/notes/:id` | Get note by ID |
| PUT | `/notes/:id` | Update note |
| DELETE | `/notes/:id` | Delete note |

## Requirements

- Node.js
- MongoDB