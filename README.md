# Meeting Scheduler Web Application

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
- [Usage](#usage)
- [Demo](#demo)
- [License](#license)

## Introduction

Welcome to the Meeting Scheduler web application! This web-based platform facilitates the scheduling of meetings and appointments between customers and companies. Whether you're a customer looking to book a service or a company managing appointments, this tool simplifies the process, minimizes scheduling conflicts, and enhances overall productivity.

Key features and benefits of the Meeting Scheduler include:

- Streamlined scheduling process.
- Real-time availability checking for companies.
- Email notifications for both customers and companies.
- Easy management and rescheduling of appointments.
- Calendar integration for efficient scheduling.

## Features

Some of the core features of the Meeting Scheduler include:

- User-friendly and responsive web interface.
- Separate login portals for customers and companies.
- **Customers** can:
  - View company profiles and available services.
  - Check real-time availability.
  - Schedule appointments.
  - Receive email confirmations.
  - Manage their appointments.
- **Companies** can:
  - Manage their business profile.
  - Set working hours and services.
  - View and confirm appointments.
  - Receive email notifications.
  - Sync with external calendars.

## Technologies Used

This project was developed using the following technologies:

- **Next.js**: A popular React framework for building fast and scalable web applications.
- **Husky**: Used for pre-commit and pre-push Git hooks to maintain code quality.
- **Tailwind CSS**: A utility-first CSS framework for building modern and responsive web designs.
- **Supabase**: An open-source alternative to Firebase for backend services.
- **TypeScript**: A statically typed superset of JavaScript for improved code quality and developer experience.

## Getting Started

### Prerequisites

Before you begin, make sure you have the following prerequisites:

- **Node.js**: Ensure you have Node.js installed on your development machine. You can download it from [nodejs.org](https://nodejs.org/).

### Installation

Follow these steps to set up and run the Meeting Scheduler locally:

1. Clone the repository:

   ```bash
   git clone https://github.com/jorgeolarte/latengo.git
   cd meeting-scheduler
   ```

2. Install the project dependencies:

   ```bash
   npm install
   ```

3. Configure environment variables: Create a `.env.local` file in the project root and set up the required environment variables (e.g., database credentials, API keys).

4. Start the development server:

   ```bash
   npm run dev
   ```

The application should now be running locally at `http://localhost:3000`.

## Usage

To use the Meeting Scheduler web application, follow these general steps:

1. Sign up or log in as a customer or company.
2. Explore available services and company profiles.
3. Check real-time availability of companies.
4. Schedule appointments at your convenience.
5. Receive email confirmations and manage your appointments as needed.

## Demo

You can access a live demo of the Meeting Scheduler at [https://www.example.com/meeting-scheduler-demo](https://www.example.com/meeting-scheduler-demo).

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
