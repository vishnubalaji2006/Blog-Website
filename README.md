# Blog Website

A web-based blog application developed using Node.js, Express.js, MongoDB and EJS. The application allows users to create, view, edit and manage blog articles.

## Features

- Create blog articles
- View all published articles
- Edit existing articles
- Delete articles
- Store blog data in MongoDB
- Render dynamic pages using EJS
- Convert Markdown content into HTML

## Technology Stack

- **Backend:** Node.js, Express.js
- **Database:** MongoDB
- **ODM:** Mongoose
- **Frontend / Templating:** EJS, HTML, CSS, JavaScript

## Project Architecture

- `server.js` – Main application entry point and server configuration.
- `models/` – MongoDB data models.
- `routes/` – Application routes and request handling.
- `views/` – EJS templates used to render web pages.

## Installation and Setup

### Prerequisites

- Node.js and npm
- MongoDB Community Server

### 1. Clone the repository

```bash
git clone https://github.com/vishnubalaji2006/Blog-Website.git
cd Blog-Website
```

### 2. Install dependencies

```bash
npm install
```

### 3. Start MongoDB

Ensure your local MongoDB server is running on port `27017`.

### 4. Run the application

```bash
npm run blogwebsite
```

### 5. Open in browser

Visit:

http://localhost:3000

## Database Configuration

The application connects to the local MongoDB database:

`mongodb://localhost/bharatInternDatabase`

Database name: `bharatInternDatabase`

Collection: `articles`

## Author

Developed as a web development project using Node.js, Express.js and MongoDB.

GitHub: https://github.com/vishnubalaji2006
