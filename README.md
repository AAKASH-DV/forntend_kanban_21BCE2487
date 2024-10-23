# [Kanban Board Application](https://main.d2nq9mz8ggbsl4.amplifyapp.com)

This is a Kanban board application built using **ReactJS**. It interacts with the provided API from [https://api.quicksell.co/v1/internal/frontend-assignment](https://api.quicksell.co/v1/internal/frontend-assignment). The application allows users to group and sort tickets dynamically based on their selection of status, user, or priority. The UI is responsive, and the user's view state is preserved even after page reload.

## Features

- **Group tickets** by Status, User, or Priority.
- **Sort tickets** by Priority or Title.
- **Responsive** and visually appealing design.
- **View state preservation** after page reload.
- Priority levels defined as:
  - Urgent (4)
  - High (3)
  - Medium (2)
  - Low (1)
  - No priority (0).

## Demo

A live demo of the Kanban board application can be accessed [here](https://main.d2nq9mz8ggbsl4.amplifyapp.com).

## Installation

To run the Kanban board application locally, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/aakash-kanban-board.git
2. Navigate to the project directory:
   ```bash
   cd kanban-board
3. Install the required dependencies:
   ```bash
   npm install
4. Start the development server:
   ```bash
   npm start
5. Open your browser and visit http://localhost:3000 to view the application.

## Usage
Click the "Display" button to fetch tickets from the API.
Group tickets using the options: By Status, By User, or By Priority.
Sort tickets by either Priority (descending) or Title (ascending).
The Kanban board will dynamically update based on your preferences.
Your view state is saved, so it remains after page reload.
