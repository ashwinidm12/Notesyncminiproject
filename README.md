# Notesyncminiproject

## Overview

**Notesyncminiproject** is a MERN stack based educational web platform designed to help engineering students access academic resources in one place. This is a group project developed by engineering students.

The platform allows students to access **semester-wise notes, previous year question papers (PYQs), aptitude preparation materials, and a community discussion forum similar to Quora.**

The system aims to simplify learning by organizing resources and enabling peer interaction.

## Features

### 1. Notes Section
- Semester-wise academic notes
- Subject-based organization
- Easy access for students preparing for exams
- Structured resource browsing

### 2. Previous Year Question Papers (PYQs)
- Organized by semester and subject
- Helps students prepare using past exam patterns
- Quick navigation to required papers

### 3. Aptitude Preparation
- Aptitude questions for placement preparation
- Practice materials to improve logical and quantitative skills
- Useful for campus placement preparation

### 4. Ask & Answer (Quora-like Forum)
- Students can post questions
- Other users can answer questions
- Community knowledge sharing
- Discussion-based learning

### 5. User Authentication
- User login system
- Identification using USN or user credentials
- Role based access for content interaction

### 6. Modern Web Interface
- Clean UI built with React
- Navigation across different academic services
- Interactive frontend experience

## Contributors
- Ashwini D M (ashwinidm12)
- [Add other group members' names here]

## Tech Stack

### Frontend
- React.js
- HTML
- CSS
- JavaScript

### Backend
- Node.js
- Express.js

### Database
- MongoDB

### Version Control
- Git
- GitHub

## Project Structure
```
Notesyncminiproject/
├── server/                 # Backend (Node.js/Express)
│   ├── controllers/
│   ├── routes/
│   ├── models/
│   ├── middleware/
│   └── server.js
├── mce-prep-frontend/      # Frontend (React)
│   ├── src/
│   │   ├── components/
│   │   ├── pages/
│   │   ├── services/
│   │   └── App.js
│   └── package.json
├── note-sync/             # Additional React app
├── pyq-uploads/           # Uploaded PYQ files
├── uploads/               # General uploads
└── README.md
```

## System Architecture
```
                ┌─────────────────────┐
                │      Frontend       │
                │     React.js UI     │
                │ (mce-prep-frontend) │
                └──────────┬──────────┘
                           │ API Calls
                           │
                ┌──────────▼──────────┐
                │       Backend       │
                │   Node.js + Express │
                │   REST API Server   │
                └──────────┬──────────┘
                           │
                           │ Database Queries
                           │
                ┌──────────▼──────────┐
                │       MongoDB       │
                │   Stores Users,     │
                │ Questions, Notes,   │
                │ and Resources       │
                └─────────────────────┘
```

## Installation and Setup

### Prerequisites
- Node.js
- MongoDB
- Docker (optional, for MongoDB)

### 1. Clone Repository
```bash
git clone https://github.com/ashwinidm12/Notesyncminiproject.git
```

### 2. Backend Setup
```bash
cd server
npm install
npm start
```
Backend runs on: `http://localhost:5000`

### 3. Frontend Setup
```bash
cd mce-prep-frontend
npm install
npm start
```
Frontend runs on: `http://localhost:3000`

### Database
- MongoDB runs on localhost:27017
- Or use Docker: `docker run -d --name notesync-mongodb -p 27017:27017 mongo:latest`

## Usage

### For Students:
1. Browse notes for different semesters
2. Access previous year question papers
3. Practice aptitude questions
4. Post questions and answers in the discussion forum
5. Collaborate and learn from peers

### For Admins:
1. File upload for notes and study materials
2. Upload answers for student questions
3. Post aptitude questions
4. Upload year-wise question papers

## Future Improvements
- AI-based doubt answering system
- Personalized learning recommendations
- Quiz and test modules
- Notifications for answers and discussions

## License
This project is for educational purposes.
