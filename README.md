# MediaFlow-clean-for-a-full-stack-streaming-app.



MediaFlow is a modern web streaming platform built with React, Redux Toolkit, and Material UI, powered by the TMDB API.
It offers a sleek Netflix-style experience with custom carousels, infinite scrolling, and interactive video modals.

View Demo · Report Bug · Request Feature

📑 Table of Contents

Overview

Features

Screenshots

Getting Started

Tech Stack

Installation (Docker)

Todo

License

🎥 Overview

MediaFlow allows users to explore, stream, and discover movies and TV shows using real-time data from The Movie Database (TMDB) API.
The platform features dynamic routing, custom hooks, optimized rendering with React Suspense, and performance-focused design.

🧩 Features

🎟️ User Interface

Netflix-inspired responsive UI built with Material UI and Framer Motion

Grid-based genre browsing with lazy loading and code-splitting

Infinite scrolling powered by Intersection Observer API

🎬 Movie Functionality

View trending, top-rated, and upcoming titles

Dynamic detail modals with video previews using video.js

Custom carousel built with react-slick

⚙️ Core Architecture

State management via Redux Toolkit (RTK) and RTK Query

Context API and custom hooks for modular, reusable components

Forwarding Refs and Higher-Order Components (HOCs) for scalability

🧱 Performance

Lazy-loading routes with React Router v6.9’s lazy()

Server data loading via loader dispatch integration

Code-splitting and suspense optimization

🛠️ Prerequisites

Create an account on TMDB
.

Generate an API Key (v3).

Create a .env file in your project root and paste:

TMDB_V3_API_KEY=your_api_key_here

💻 Tech Stack

Frontend: React.js, Redux Toolkit, Material UI, Framer Motion

Routing: React Router v6.9

Video Engine: video.js

UI Enhancements: react-slick (carousel), Intersection Observer API

Deployment: Docker

🐳 Installation (Docker)
docker build --build-arg TMDB_V3_API_KEY=your_api_key_here -t cineverse .
docker run --name cineverse-app --rm -d -p 80:80 cineverse

🧠 Todo / Future Improvements

Enhance animation transitions for video card portals

Improve context performance and re-render optimization

Add accessibility features for better UX

Replace Vite with Turbopack (when fully supported)

Implement automated tests

Introduce new motion-based animations

📜 License

This project is licensed under the MIT License.

✉️ Contact

Developed by Nidhi Samarth
📧 nidhisamarth31@gmail.com

🔗 LinkedIn
 | GitHub
