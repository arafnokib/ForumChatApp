# Forum-Chat Web Application

A full-stack web-based forum and chat application built using **Node.js**, **EJS templates**, and **CSS**. This project demonstrates dynamic server-side rendering, routing, and integration of a backend with a structured frontend interface. Users can view, post, and interact in chat or forum threads through a clean web interface.

---

## Features

* Dynamic server-side rendering using **EJS templates**
* User-friendly chat/forum interface
* Structured frontend with **HTML, CSS, and JavaScript**
* Node.js backend handling routing and data flow
* Static assets management (CSS, images, JS) via the `public/` folder
* Modular project structure for frontend and backend separation

---

## Tech Stack

* **Backend:** Node.js, Express (or compatible server)
* **Frontend:** EJS templating, HTML, CSS, client-side JavaScript
* **Package Management:** npm / Yarn (`package.json`, `yarn.lock`)
* **Server:** Handles routing, dynamic content rendering, and static assets

---

## Installation

1. Clone the repository:

```bash
git clone https://github.com/arafnokib/ForumChatApp.git
```

2. Navigate to the project folder:

```bash
cd ForumChatApp
```

3. Install dependencies:

```bash
npm install
# or
yarn install
```

4. Start the server:

```bash
node server.js
```

5. Open your browser and go to:

```
http://localhost:3000
```

---

## Project Structure

```
ForumChatApp/
│
├─ server.js          # Node.js backend server
├─ package.json       # Node dependencies
├─ yarn.lock          # Yarn lockfile
├─ public/            # Static assets (CSS, JS, images)
└─ views/             # EJS templates for frontend pages
```

---

## Usage

* Navigate to the home page to view forum threads or chat messages.
* Post new messages through the chat interface.
* Interact with existing threads to simulate forum discussions.

---

## Key Skills Demonstrated

* Node.js backend development
* Server-side templating with **EJS**
* Frontend integration with dynamic content
* Routing and request handling
* Project structuring for maintainable full-stack applications

---

## Future Improvements

* Add **user authentication** for personalized accounts
* Integrate **real-time messaging** with WebSockets
* Store messages in a **database** instead of in-memory
* Improve UI/UX with responsive design
* Add message editing and deletion functionality

---

## License

MIT License (or specify another license if applicable)
