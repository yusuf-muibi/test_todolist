# Dynamic To-Do List Application by Owolabi Oluwasemilogo and Yusuf Muibi

## Overview

This is a dynamic to-do list application built using the MERN stack (MongoDB, Express.js, React, and Node.js). The application allows users to manage their tasks in three sections: Pending, In Progress, and Completed. Users can add tasks, move tasks between sections, and optionally use drag-and-drop functionality to organize their tasks.

## Features

- **Add New Task**: Users can add a task to the Pending section with a title and optional description.
- **Move Tasks Between Sections**: Tasks can be moved from Pending to In Progress and from In Progress to Completed. Each task has a button for moving it to the next section.
- **Drag and Drop**: Users can drag and drop tasks between sections for easy organization.
- **Timestamp**: Tasks in the Completed section display a timestamp in the format "DD/MM/YY, HH:mm".

## Setup and Installation

### Prerequisites

- Node.js and npm installed on your machine.
- MongoDB installed and running on your machine or a cloud MongoDB service.

### Backend Setup

1. Clone the repository:

```bash
git clone <Repository>
cd Dynamic-ToDo-List-App
```

2. Navigate to the backend directory and install dependencies:

```bash
cd backend
npm install
```

4. Start the backend server:

```bash
npm start
```

5. The backend server should now be running on `http://localhost:5000`.

### Frontend Setup

1. Navigate to the frontend directory and install dependencies:

```bash
cd frontend
npm install
```

2. Start the frontend development server:

```bash
npm run dev
```

3. The frontend development server should now be running on `http://localhost:5173`.

## Usage

### Adding a Task
Enter the task title and description in the input fields provided in the "Add Task" section.
Click the "Add Task" button to add the task to the Pending section.

### Moving Tasks Between Sections
In the Pending section, click the "Start" button on a task to move it to the In Progress section.
In the In Progress section, click the "Complete" button on a task to move it to the Completed section.
Tasks in the Completed section will display the timestamp when they were completed.

### Drag and Drop
Drag tasks from one section to another by clicking and holding on a task card, then dragging it to the desired section.

## Screenshot

![Screenshot of the Application](frontend/src/assets/screenshot.png)
