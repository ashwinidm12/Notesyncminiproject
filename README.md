# Notesyncminiproject

## Overview

**Notesyncminiproject** is a MERN stack educational platform built to help engineering students access academic resources from one place.

The platform provides:
- Semester-wise notes
- Previous year question papers (PYQs)
- Aptitude preparation materials
- A community discussion forum for doubts and answers

## Features

### Notes
- Semester and subject-wise notes
- Easy browsing for study materials
- File uploads for notes and resources

### PYQs
- Previous year questions organized by semester and subject
- Fast access for exam preparation
- Downloadable question papers

### Aptitude
- Aptitude practice questions
- Placement preparation support
- Topic-wise aptitude practice

### Discussion Forum
- Ask questions and get answers from the community
- Post doubts and discuss solutions
- Support for threaded Q&A

### User Authentication
- Login system for users
- Role-based access for features
- Secure account handling

## Tech Stack

- **Frontend**: React.js
- **Backend**: Node.js, Express.js
- **Database**: MongoDB
- **Authentication**: JWT
- **File Uploads**: Multer

## Project Structure

```
Notesyncminiproject/
├── server/                 # Backend (Node.js/Express)
├── mce-prep-frontend/      # Frontend (React)
├── note-sync/              # Additional React app
├── pyq-uploads/            # Uploaded PYQ files
├── uploads/                # General uploads
└── README.md
```

## Installation

### Prerequisites
- Node.js
- npm
- MongoDB
- Docker (optional)

### Backend Setup
```bash
cd server
npm install
npm start
```

The backend runs on `http://localhost:5000`.

### Frontend Setup
```bash
cd mce-prep-frontend
npm install
npm start
```

The frontend runs on `http://localhost:3000`.

### Database Setup
- Local MongoDB: `mongodb://localhost:27017/notesync`
- Docker MongoDB: `docker run -d --name notesync-mongodb -p 27017:27017 mongo:latest`

## Usage

1. Start the backend server.
2. Start the frontend application.
3. Open `http://localhost:3000` in your browser.

## Author

**Ashwini D M**
MERN Stack Developer

## GitHub

https://github.com/ashwinidm12/Notesyncminiproject


