# real-time-code-editor

CODERRR is a real-time collaborative code editor designed to enhance the coding experience by allowing multiple users to write and compile code together seamlessly. Built using the MERN stack (MongoDB, Express.js, React, Node.js) with WebSocket for real-time synchronization, this project also integrates the JDoodle API to enable instant code compilation in various languages.

Features
Real-Time Collaboration:

Multiple users can write and edit code simultaneously in a shared environment with instant updates via WebSocket.
JDoodle API Integration:

Compile code instantly in supported languages (e.g., Python, C++, Java) directly within the editor.
Secure Authentication & Authorization:

Users are authenticated securely before joining a room, ensuring that only authorized users can access collaborative sessions.
Room Management:

Create, join, or leave rooms to manage collaborative coding sessions effortlessly.
Local Storage Integration:

Users can import code from their local storage and also save their progress locally for future use.
Responsive User Interface:

A sleek, responsive interface built with React and Tailwind CSS that adapts to various screen sizes for a smooth user experience.
Syntax Highlighting:

Real-time syntax highlighting using CodeMirror for a rich coding environment.
Persistent Data Storage:

MongoDB is used to store user data and project history reliably, allowing users to revisit their previous work.
Tech Stack
Frontend: React.js, Tailwind CSS, CodeMirror
Backend: Node.js, Express.js, WebSocket
Database: MongoDB
Code Compilation API: JDoodle API
Other Libraries: Axios, Toastify, FileSaver.js
Getting Started
Follow the instructions below to set up and run CODERRR locally.

Prerequisites
Node.js
MongoDB
JDoodle API credentials (sign up for an account at JDoodle to obtain your API keys)
