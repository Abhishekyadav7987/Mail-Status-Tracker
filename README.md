# Mail Status tracker

**Suppose**, you have applied for a job through an email. You have sent the email two days ago but you haven't gotten any response. And you don't know if the employer read your email or not. Well no need to worry now because I have a solution for that, **introducing Mail Status Tracker**.

**Mail Status Tracker** is an  project designed to help users track the status of their sent emails. With Mail Status Tracker, you can determine whether your email has been read by the recipient, providing peace of mind and valuable insights into your email communications.

## Introduction

Have you ever sent an important email and wondered if the recipient has read it? With Mail Status Tracker, you no longer have to guess. Mail Status Tracker is a simple and privacy-focused platform that allows you to track the status of your sent emails without requiring full email read/write access. Our solution respects your privacy while providing the information you need.

## Features

- **User Authentication**: Secure user authentication using Nhost, allowing users to sign up, sign in, and manage their profiles.
- **Email Tracking**: Embed a tracking pixel in your emails to monitor when they are opened. The tracking pixel sends a request to the server, updating the email’s status to "seen".
- **Dashboard**: Access a user-friendly dashboard to view the status of your sent emails, including whether they have been read and the time they were read.
- **Serverless Functions**: Utilize Nhost serverless functions to handle backend logic for updating email statuses.

## Tech Stack

Mail Status Tracker leverages a straightforward tech stack to deliver its functionality:

- **React**: For building the frontend user interface.
- **Nhost**: For user authentication, database management, hosting, and serverless functions.
- **GraphQL**: For efficient data querying and manipulation.
- **Express**: For handling server-side logic.
- **PostgreSQL**: Managed by Nhost for database operations.

## Installation

To get started with Mail Status Tracker, follow these steps:

1. **Clone the repository**:
   git clone https://github.com/Abhishekyadav7987/Mail-Status-Tracker
   cd Mail Status Tracker

2. **Install dependencies**:
      npm install
3.**Set up environment variables**:
   Create a .env file in the root directory and add your Nhost project details
    NHOST_BACKEND_URL=your_nhost_backend_url
    NHOST_ADMIN_SECRET=your_nhost_admin_secret
4.**Run the application**:
   npm start
## Usage:
Sign up or log in to your Mail Status Tracker account.
Send an email using the Mail Status Tracker platform, which will embed a tracking pixel in the email.
Monitor the status of your sent emails on the dashboard. You will see whether the email has been read and the time it was read.
