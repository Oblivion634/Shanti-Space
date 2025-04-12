# Shanti-Space- Mental Well-Being Management Platform
ShantiSpace is a full-stack platform designed to promote mental well-being, combining both front-end and back-end technologies to provide a comprehensive mental health management experience. It includes guided meditation, therapy resources, AI-based screening, music playlists, community support, and more.

# Features
Front-End:
Guided Meditation: Breathing exercises, meditation sounds, and timer for mindfulness.
AI Screening Quiz: Personalized mental health screening through an AI-generated quiz (login required).
Therapy Information & Locator: Find and learn about various therapy types and locate local therapists (Google Maps API integration coming soon).
Music Categories: Focus, sleep, instrumental, meditation, and stress-relieving music with embedded Spotify and YouTube playlists.
Community Page: Anonymously post thoughts, like and delete posts (stored in MongoDB).
Articles Page: Read and like helpful articles related to mental well-being.

# Back-End:
User Authentication: Firebase integration for secure login and user management.
Database: MongoDB for storing community posts, user data, and other relevant information.
API Integration: Google Maps (upcoming), Gemini API-powered chatbot, and AI screening.
Payment Integration (coming soon): For booking therapist sessions.

# Tech Stack
Frontend: React, React Router, Axios, Leaflet, GSAP, Swiper
Backend: Node.js, Express, MongoDB, Firebase.
Libraries & APIs: Google Generative AI, Mediapipe, Howler, React-Speech-Recognition

# Installation
Clone the repository:

git clone https://github.com/yourusername/shantispaced.git

Install dependencies:
npm install

Set up environment variables by creating a .env file in the root directory with the necessary keys for Firebase, Google APIs, etc.

Run the development server:
npm start

# Upcoming Features
Google Maps API integration for therapist location.
Mood Tracker to track and analyze emotional well-being over time.
Payment gateway for therapist booking.

# Contributing
Feel free to fork the repository, submit pull requests, or open issues for bug reports or feature suggestions.
