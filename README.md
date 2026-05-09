# NotesApp

A full-stack Notes Application that allows users to create, edit, manage, and delete notes through a clean and responsive interface.

---

## Features

* Create and manage notes
* Edit existing notes
* Delete notes
* Responsive user interface
* REST API integration
* Persistent data storage

---

## Tech Stack

### Frontend

* React.js
* HTML
* CSS
* JavaScript

### Backend

* Node.js
* Express.js

### Database

* MongoDB

---

## Project Structure

```bash
notesapp/
│
├── client/         # Frontend application
├── server/         # Backend server
├── models/         # Database models
├── routes/         # API routes
├── controllers/   # Business logic
├── package.json
└── README.md
```

---

## Installation

### Clone the repository

```bash
git clone https://github.com/Sainath-Reddy7/notesapp.git
cd notesapp
```

### Install dependencies

#### Frontend

```bash
cd client
npm install
```

#### Backend

```bash
cd ../server
npm install
```

---

## Environment Variables

Create a `.env` file inside the `server` directory and add the following:

```env
MONGO_URI=your_mongodb_connection_string
PORT=5000
```

---

## Running the Application

### Start Backend Server

```bash
cd server
npm start
```

### Start Frontend

```bash
cd client
npm run dev
```

---

## API Endpoints

| Method | Endpoint   | Description       |
| ------ | ---------- | ----------------- |
| GET    | /notes     | Fetch all notes   |
| POST   | /notes     | Create a new note |
| PUT    | /notes/:id | Update a note     |
| DELETE | /notes/:id | Delete a note     |

---

## Future Improvements

* User authentication
* Search functionality
* Note categories and tags
* Dark mode support
* Cloud synchronization

---

## Contributing

Contributions are welcome.

1. Fork the repository
2. Create a feature branch
3. Commit your changes
4. Push to your branch
5. Open a Pull Request

---

## License

This project is licensed under the MIT License.

---

## Author

**Sainath Reddy**

GitHub: [https://github.com/Sainath-Reddy7](https://github.com/Sainath-Reddy7)
