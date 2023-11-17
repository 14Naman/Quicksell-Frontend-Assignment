# Quicksell-Frontend-Assignment
React-based interactive Kanban board application with dynamic grouping and sorting options, utilizing the Quicksell API for data, providing a visually appealing and responsive user interface.
An interactive Kanban board application built using React JS and SCSS. The board dynamically adjusts based on user grouping preferences. It interacts with the provided API from [Quicksell](https://api.quicksell.co/v1/internal/frontend-assignment).

## Features

- **Conditional Rendering**: Components are rendered based on the state and user preferences.
- **Grouping**:
  - **By Status**: Tickets are grouped based on their current status.
  - **By User**: Tickets are arranged according to the assigned user.
  - **By Priority**: Tickets are grouped based on their priority level.
- ****:
  - **Priority**: Tickets are arranged in descending order of priority.
  - **Title**: Tickets are sorted in ascending order based on their title.
- **User's View State Persistence**: The application saves the user's view state, even after a page reload.
- **Dynamic Data**: Fetches and displays data from the Quicksell API.
- **Custom Spinner**: An engaging spinner for better user experience during data fetching or other waiting times.
- **Available User Indicator**: Displays which users are currently available.

## Live Demo

Experience the application [here](https://naman-quicksell-assignment.vercel.app/).

## Repository

Find the source code on [GitHub](https://github.com/14Naman/Quicksell-Frontend-Assignment).

## Tech Stack

- **JavaScript**
- **React JS**
- **SCSS (CSS Preprocessor)**
