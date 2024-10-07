# Test-Task

This project is a job management application that allows users to view and edit a list of jobs. Job data is dynamically generated using Faker.js, providing a realistic set of mock data for testing purposes. The application displays the jobs in a table format, where each row represents a job entry. 

Users can easily edit any job by clicking the "Edit" button in the table, which opens a form to modify the job's details. The application utilizes React for building the user interface, with Redux Toolkit for managing state and seamless updates to the job list. It provides a clean and interactive way to handle and update job data.


## Table of Contents

- [Installation](#installation-Required-libraries)
- [Prerequisites](#prerequisites)
- [Steps](#steps)
- [Getting Started](#getting-started)
- [Technologies Used](#technologies-used)
- [Features](#features)
- [Usage](#usage)

### Installation Required libraries
npm install @faker-js/faker @reduxjs/toolkit better-sqlite3 formik next react react-dom react-modal react-redux


### Prerequisites
Before running this project, make sure you have [Node.js](https://nodejs.org/) installed on your machine.

### Steps
1. Clone the repository:

   git clone https://github.com/amwhiz/job-listing.git

2. Navigate to the project directory:

   cd your-repo-name

3. Install dependencies:

   npm install
   
### Getting Started

```bash
npm run dev
# or
yarn dev
# or
pnpm dev
# or
bun dev
```

Open http://localhost:3000 with your browser to see the result.

You can start editing the page by modifying pages/index.tsx. The page auto-updates as you edit the file.

API routes can be accessed on http://localhost:3000/api/jobs.ts. This endpoint can be edited in pages/api/jobs.ts.

The pages/api directory is mapped to /api/*. Files in this directory are treated as API routes instead of React pages.

This project uses next/font to automatically optimize and load Inter, a custom Google Font.

## Technologies Used

This project uses the following key dependencies:

- **@faker-js/faker**: `^9.0.3` - For generating fake data.
- **@reduxjs/toolkit**: `^2.2.7` - For state management.
- **better-sqlite3**: `^11.3.0` - For interacting with SQLite databases.
- **formik**: `^2.4.6` - For form handling.
- **next.js**: `14.2.14` - The React framework for server-side rendering and static site generation.
- **react**: `^18` - The core React library.
- **react-dom**: `^18` - React DOM library for rendering components.
- **react-modal**: `^3.16.1` - For creating accessible modals in React.
- **react-redux**: `^9.1.2` - For integrating Redux with React components.

## Features
- **Fake Data Generation**: Uses Faker.js to generate mock data for testing and development.
- **State Management**: Redux Toolkit is integrated for efficient state management.
- **Database Integration**: Uses Better-SQLite3 for fast, secure SQLite database interaction.
- **Form Handling**: Formik simplifies form creation and validation.
- **Server-Side Rendering (SSR)**: Built with Next.js, enabling both SSR and static site generation.
- **API Routes**: Provides easy-to-use API routes with Next.js.
- **Modal Management**: React-Modal is used for creating accessible and customizable modal dialogs.

## Usage

To run the project in development mode:
```bash
npm run dev

