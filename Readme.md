# AstroKnight-ImBatman

AstroKnight-ImBatman is an interactive web application designed to provide an immersive and educational game experience for space exploration. The project combines stunning VR & 3D visualizations, AI-powered interactions, and real data from NASA to create a comprehensive platform for learning about our solar system.

## Table of Contents

1. [Project Overview](#project-overview)
2. [Features](#features)
3. [Technologies Used](#technologies-used)
4. [Project Structure](#project-structure)
5. [How It Works](#how-it-works)
6. [Installation and Setup](#installation-and-setup)
7. [Running the Application](#running-the-application)
8. [Usage](#usage)
9. [Contributing](#contributing)
10. [License](#license)

## Project Overview

AstroKnight-ImBatman is a web-based application that aims to deepen users' understanding of the planets in our solar system. The project leverages advanced technologies to provide an engaging learning experience, fostering curiosity and broadening perspectives on the universe.

## Features

- Interactive 3D solar system animation
- Detailed 3D models of planets with the ability to explore them "on foot"
- AI-powered chatbot for answering space-related questions
- Integration with NASA's public data for scientific accuracy
- Responsive design for various devices
- Smooth animations and transitions
- User feedback system

## Technologies Used

- Frontend:
  - HTML5
  - CSS3 (with Tailwind CSS framework)
  - JavaScript (ES6+ syntax)
  - Three.js for 3D rendering
  - WebGL for 3D graphics

- Backend:
  - Node.js
  - Express.js as the web application framework

- Database:
  - SQLite (for storing user feedback)

- AI:
  - Google's Generative AI API for the chatbot

## Project Structure
AstroKnight-ImBatman/ ├── assets/ │ ├── images/ │ └── videos/ ├── js/ │ ├── main.js │ ├── mainP.js │ └── other JS files... ├── server.js ├── app.py ├── package.json ├── package-lock.json ├── index.html ├── solar-system.html ├── ai-chatbot.html ├── about.html ├── feedback.html └── README.md


## How It Works

1. The application is served by a Node.js server using Express.js.
2. The frontend is built using HTML, CSS, and JavaScript, with Three.js handling 3D rendering.
3. 3D models of planets are loaded using GLTFLoader and rendered in the browser.
4. The AI chatbot is powered by Google's Generative AI API, integrated through the backend.
5. User feedback is stored in a SQLite database, managed by a Python backend (currently not in use).
6. The application fetches data from NASA's API to ensure scientific accuracy.

## Installation and Setup

1. Clone the repository:
git clone https://github.com/NafisRayan/AstroKnight-ImBatman.git


2. Navigate to the project directory:
cd AstroKnight-ImBatman


3. Download the GLTF 3D model files:
   - Visit the following Google Drive link to download the 3D model files: [Link](https://drive.google.com/drive/folders/15DFIuNTGMX3VnvFDYm2FS1jRCveDKTFy?usp=sharing)
   - Extract the downloaded files and place them in the `assets/models/` directory

4. Install Node.js dependencies:
npm install


5. Install Python dependencies (if using the Python backend):
pip install -r requirements.txt


## Running the Application

1. Start the Node.js server:
node server.js


2. Open a web browser and navigate to `http://localhost:3000`

3. If using the Python backend for feedback management:
python app.py


## Usage

- Explore the solar system through the interactive 3D animation
- Visit individual planet pages for detailed information and 3D models
- Use the AI chatbot to ask space-related questions
- Provide feedback through the feedback form
- Navigate through the responsive interface on various devices