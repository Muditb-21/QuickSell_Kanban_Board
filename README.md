# Kanban Board 

This application is built using React JS and interacts with the provided API from [https://api.quicksell.co/v1/internal/frontend-assignment](https://api.quicksell.co/v1/internal/frontend-assignment). 
It allows users to manage and view tickets in a Kanban board format with various grouping and sorting options.

### Commands to run locally
1.  npm install 
2.  npm start

You can install axios using:
-   npm install axios 



### Grouping Options

The Kanban board application offers three distinct ways to group the data:

1. **By Status**: Tickets are grouped based on their current status.
2. **By User**: Tickets are arranged according to the assigned user.
3. **By Priority**: Tickets are grouped based on their priority level.

### Sorting Options

Users can sort the displayed tickets in two ways:

1. **Priority**: Arrange tickets in descending order of priority.
2. **Title**: Sort tickets in ascending order based on their title.

### Priority Levels

The priority levels for the tickets are as follows:

- Urgent (Priority level 4)
- High (Priority level 3)
- Medium (Priority level 2)
- Low (Priority level 1)
- No priority (Priority level 0)

### User State Persistence

The application is built to save the user's view state even after a page reload. This ensures that users can continue their work seamlessly.

## Technologies Used

- React JS
- JavaScript
- HTML
- CSS

## Dependencies

- React
- Axios (for API interactions)
