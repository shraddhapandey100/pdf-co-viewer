# PDF Co-Viewer

A real-time, synchronized PDF co-viewer application built with React and Node.js, allowing users to view and follow along with PDF slides remotely. Admin users control the navigation, and all viewers follow along in real-time.

## Features

- **Real-Time Sync**: Keeps all viewers on the same PDF page as the admin.
- **Admin Controls**: Admin users can change slides, affecting all connected viewers.
- **Easy Setup**: Built with Node.js and Socket.IO for backend, React and PDF.js for frontend.

## Tech Stack

- **Frontend**: React, PDF.js, Socket.IO-client
- **Backend**: Node.js, Socket.IO
- **Deployment**: Docker, (optional: AWS, Heroku, or DigitalOcean)

## Getting Started

### Prerequisites

- Node.js and npm installed

### Running Locally

1. **Clone the Repository**

   ```bash
   git clone https://github.com/username/pdf-co-viewer.git
   cd pdf-co-viewer
