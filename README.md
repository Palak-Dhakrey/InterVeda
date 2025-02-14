# Full Stack AI Mock Interview App

**Welcome to InterVeda - The AI Mock Interview App!**  
This project is designed to help developers enhance their skills through AI-driven mock interviews, providing real-time feedback to simulate a realistic interview experience.

## Table of Contents
- [Overview](#overview)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Getting Started](#getting-started)
  - [Installation](#installaton)
  - [Usage](#usage)
- [Database Management](#database-management)
- [User Authentication](#user-authentication)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## Overview
InterVeda allows users to practice technical and behavioral interview questions in an interactive environment. The app generates custom questions based on user preferences and delivers instant feedback on answers to help users improve their interview skills.

## Features
- **AI-Driven Questions**: Get custom-tailored interview questions based on your profile and feedback.
- **User Authentication**: Secure login and signup using Clerk.
- **Real-Time Feedback**: Answer interview questions and receive immediate feedback with the help of Gemini AI.
- **Interactive UI**: A responsive, user-friendly interface built with React.
- **Data Persistence**: User data and interview history managed through Drizzle ORM.
- **Dark Mode Support**: Toggle between light and dark themes with settings stored in localStorage.
- **Prime Membership**: Users can unlock unlimited interviews through Razorpay payment integration.

## Technologies Used
- **[Next.js](https://nextjs.org/)**: Framework for server-rendered React applications.
- **[React](https://reactjs.org/)**: JavaScript library for building user interfaces.
- **[Drizzle ORM](https://drizzle.team/)**: ORM for managing database interactions with PostgreSQL (Neon).
- **[Gemini AI](https://gemini.ai/)**: AI API for generating interview questions and analyzing answers.
- **[Clerk](https://clerk.dev/)**: Authentication and user management.


## Getting Started

### Installation
To get started with the project, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/Palak-Dhakrey/InterVeda.git
Navigate to the project directory:

bash
Copy
cd InterVeda
Install the dependencies:

bash
Copy
npm install
Usage
Start the development server:

bash
Copy
npm run dev
Open your browser and visit http://localhost:3000 to see the app in action!

Database Management
To open the local database for the project, run:

bash
Copy
npm run db:studio
User Authentication
User authentication and management are handled using Clerk.

Contributing
We welcome contributions! Please follow these steps to contribute:

Fork the repository: Click the "Fork" button at the top right corner of this repository.

Clone your fork:

bash
Copy
git clone https://github.com/yourusername/InterVeda.git
Create a new branch:

bash
Copy
git checkout -b your-feature-branch
Make your changes: Add features or fix bugs.

Commit your changes:

bash
Copy
git commit -m "Describe your changes"
Push your branch:

bash
Copy
git push origin your-feature-branch
Create a pull request: Go to the original repository and open a pull request.

For more details, please refer to the CONTRIBUTING.md.

License
This project is licensed under the MIT License. See the LICENSE file for details.


