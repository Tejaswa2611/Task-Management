# Task Management Application

This project is a Task Management Application built using React and Redux Toolkit for effective state management. It provides a minimalistic and easy-to-use interface for managing tasks. Users can add tasks with priorities, mark them as completed, and sort them based on completion and priority.

## Setup Instructions

To run this project locally, follow these steps:

1. Clone the repository to your local machine:

```bash
git clone <repository_url>
```

2. Navigate to the project directory:

```bash
cd task_management_2
```

3. Install dependencies using npm:

```bash
npm install
```

4. Start the development server:

```bash
npm start
```

5. Open your browser and navigate to [http://localhost:3000](http://localhost:3000) to view the application.

## Project Structure

The project structure is organized as follows:

- `src/`: Contains the source code of the application.
  - `components/`: Contains React components used in the application.
  - `styles/`: Contains CSS modules for styling the components.
  - `app/`: Contains Redux store configuration.
    - `store.js`: Configures the Redux store.
  - `features/`: Contains Redux Toolkit slices for managing application state.
    - `todoSlice.js`: Redux slice for managing todo-related state.
  - `App.js`: Main component rendering the application.
  - `index.js`: Entry point of the application.
- `public/`: Contains static assets and the HTML file.

## Design Choices

- **React and Redux Toolkit**: Utilized React for building the user interface and Redux Toolkit for state management, ensuring a smooth and efficient application.
- **Framer Motion**: Integrated Framer Motion for creating interactive animations, enhancing the user experience and making the UI visually appealing.
- **Minimalistic Design**: Adopted a minimalistic design approach to provide users with a clean and intuitive interface, focusing on usability and simplicity.
- **UUID**: Used UUID for generating unique identifiers for tasks, ensuring data integrity and preventing conflicts.

## Additional Features

- **Sorting**: Implemented sorting functionality based on completion status and priority, allowing users to organize their tasks efficiently.

## Screenshots/GIFs
Adding a Todo list with selected priority and status
![cant load image](<Screenshot 2024-04-30 210617.png>)

Updation of a Todo list to update prioriy,status and title
![cant load image](<Screenshot 2024-04-30 210914.png>)

Visual	indication	of	completed	tasks	(strike-through)
![cant load image](<Screenshot 2024-04-30 210734.png>)

Sorting on the basis of completion of task
![cant load image](<Screenshot 2024-04-30 210751.png>)

Responsive and minimalistic design
![cant load image](<Screenshot 2024-04-30 210639.png>)

## GitHub Repository

https://github.com/Tejaswa2611/Task-Management
