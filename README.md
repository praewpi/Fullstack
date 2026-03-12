# Full Stack Web Development Course Exercises

This repository contains exercises and projects completed as part of the **Full Stack Open** course offered by the University of Helsinki.

🔗 **Course Website:** [https://fullstackopen.com/](https://fullstackopen.com/)

## About the Course

The Full Stack Open course introduces modern JavaScript-based web development. It covers building **single page applications** with **ReactJS** that use **REST APIs** built with **Node.js**, as well as state management, testing, databases, and more.

**Topics covered (Parts 0–6):**
- React, Redux, Node.js, MongoDB, GraphQL, and TypeScript fundamentals
- Building and consuming REST APIs
- Frontend and backend integration
- Testing and best practices

---

## Repository Structure

### Part 0 – Fundamentals of Web Apps
> Introduction to web development basics: HTTP, DOM, AJAX, and how modern web applications work.

- `exercise0_4.md` – Diagram of creating a new note
- `exercise0_5.md` – Diagram of single page application
- `exercise0_6.md` – Diagram of SPA note creation
- `note_part0.txt` – Study notes on DOM, AJAX, and browser APIs

---

### Part 1 – Introduction to React
> Getting started with React: components, props, state, and event handling.

- **courseinfomation** – Displays course info using React components *(note: folder name has a typo in the original project)*
- **anecdotes** – Random anecdote viewer with voting functionality
- **unicafe** – A feedback collection app using React state

---

### Part 2 – Communicating with Server
> Deeper React, forms, data fetching, and working with REST APIs using `axios`.

- **courseinformation** – Extended course info component
- **phonebook** – A phonebook app with CRUD operations using a JSON server backend
- **countries** – Country search app consuming the REST Countries API

---

### Part 4 – Testing Express Servers, User Administration
> Node.js backend development, unit testing, integration testing, and user authentication with JWT.

- **bloglist** – A blog list backend built with Express, MongoDB (Mongoose), and tested with Jest & Supertest

---

### Part 5 – Testing React Apps
> Frontend testing, Cypress end-to-end testing, and token-based authentication on the frontend.

- **bloglist-frontend** – React frontend for the blog list app with login, blog creation, and voting features

---

### Part 6 – State Management with Redux
> Advanced state management using Redux and Redux Toolkit.

- **unicafe-redux** – Unicafe feedback app reimplemented with Redux
- **redux-anecdotes** – Anecdotes app using Redux for state management and async actions

---

## Tech Stack

| Technology | Usage |
|------------|-------|
| React | Frontend UI (Parts 1–6) |
| Redux | State management (Part 6) |
| Node.js + Express | Backend REST API (Part 4) |
| MongoDB + Mongoose | Database (Part 4) |
| Axios | HTTP requests (Parts 2–5) |
| Jest + Supertest | Backend testing (Part 4) |
| JSON Server | Mock REST API (Part 2) |

---

## Getting Started

Each part/project is self-contained. To run a project:

```bash
# Navigate to the project folder
cd part1/unicafe

# Install dependencies
npm install

# Start the development server
npm start
```

For backend projects (e.g., Part 4):
```bash
cd part4/bloglist

npm install

# Set up your .env file with MONGODB_URI and SECRET
npm run dev
```

---

## Course Progress

- [x] Part 0 – Fundamentals of Web Apps
- [x] Part 1 – Introduction to React
- [x] Part 2 – Communicating with Server
- [x] Part 4 – Testing Express Servers, User Administration
- [x] Part 5 – Testing React Apps
- [x] Part 6 – State Management with Redux
