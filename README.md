# youtube_sync
Real-Time Web Application with WebSockets
This project showcases a real-time web application utilizing WebSocket technology for seamless live data synchronization. It allows you to share a YouTube link with a friend and watch the video together in perfect sync, ensuring no lag between your friend's device and yours.

## Features

- Real-Time Updates: Live two-way communication using WebSocket.
- Two-Way Handshake: WebSocket establishes a persistent connection through an initial HTTP handshake, allowing real-time data transfer between the client and server.
- Frontend: A dynamic UI built with React and styled using modern CSS techniques.
- Backend: A Node.js and Express.js server ensuring fast and scalable real-time communication.
- Cross-Device Support: Sync data seamlessly across devices.

## Tech Stack
### Frontend:

HTML, CSS, JavaScript, ReactJS

### Backend:

Node.js, Express.js, WebSocket Protocol

## Prerequisites
Make sure you have the following installed:

- Node.js
- npm (Node Package Manager)
- A modern web browser

## Installation and Setup
1. Clone the repository:
```cmd
git clone https://github.com/Priyansurout/youtube_syn.git
```
```cmd
cd <repository-directory>
```
Note: change the <repository-directory> to where you cloned the repo.

2. Install dependencies for both the frontend and backend and run them:

For backend
```cmd
cd youtube_syn

npm install

npm start
```

For frontend
```cmd
cd ../youtube-sync-player

npm install

npm start
```
3. Open your browser and navigate to:

```cmd 
http://localhost:3000
```

## Usage

1. Start the backend server and frontend client as mentioned in the setup instructions.
2. Open the web application in your browser.
3. copy paste the video link then copy the room id
4. Join the room from the room id.
5. voila you have succesfully create a websocketing app which let's you share and watch the same youtube video with your friend.

## Output

https://github.com/user-attachments/assets/d59bfce8-fdb0-49fd-bff9-34f5116fdc82

## Contributing

Contributions are welcome! Fork the repository, create a new branch, and submit a pull request with your changes. For major changes, please open an issue to discuss before proceeding.
