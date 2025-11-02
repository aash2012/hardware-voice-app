# Architecture & Stack

Mobile: React Native (Expo + EAS)
Backend: Node.js + Express
DB: MongoDB Atlas (or local)
Auth: JWT (access + refresh tokens, rotation)
STT: Whisper or Google Speech-to-Text (backend proxy)
NLP: regex + fuse.js fuzzy match microservice
Hosting: Render / Railway for backend, MongoDB Atlas
