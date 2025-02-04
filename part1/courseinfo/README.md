# Half Stack Application Development

This is a React application created as part of the Full Stack Open course. The goal of this exercise is to practice creating and refactoring React components and passing data using props.

## Features

- **Header**: Displays the course name.
- **Content**: Renders the different parts of the course along with the number of exercises for each part.
- **Total**: Calculates and displays the total number of exercises in the course.

## File Structure

- `App.jsx`: The main component that holds the data and passes it to child components.
- `Header.jsx`: Displays the name of the course.
- `Content.jsx`: Contains three `Part` components, which render individual parts of the course and their respective exercises.
- `Part.jsx`: Displays a part's name and the number of exercises.
- `Total.jsx`: Displays the total number of exercises across all parts.
