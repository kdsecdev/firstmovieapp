# Getting Started with Create React App

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

## Available Scripts

In the project directory, you can run:

### `npm start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in your browser.

The page will reload when you make changes.\
You may also see any lint errors in the console.

### `npm test`

Launches the test runner in the interactive watch mode.\
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `npm run build`

Builds the app for production to the `build` folder.\
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.\
Your app is ready to be deployed!

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.

### `npm run eject`

**Note: this is a one-way operation. Once you `eject`, you can't go back!**

If you aren't satisfied with the build tool and configuration choices, you can `eject` at any time. This command will remove the single build dependency from your project.

Instead, it will copy all the configuration files and the transitive dependencies (webpack, Babel, ESLint, etc) right into your project so you have full control over them. All of the commands except `eject` will still work, but they will point to the copied scripts so you can tweak them. At this point you're on your own.

You don't have to ever use `eject`. The curated feature set is suitable for small and middle deployments, and you shouldn't feel obligated to use this feature. However we understand that this tool wouldn't be useful if you couldn't customize it when you are ready for it.

## Learn More

You can learn more in the [Create React App documentation](https://facebook.github.io/create-react-app/docs/getting-started).

To learn React, check out the [React documentation](https://reactjs.org/).

### Code Splitting

This section has moved here: [https://facebook.github.io/create-react-app/docs/code-splitting](https://facebook.github.io/create-react-app/docs/code-splitting)

### Analyzing the Bundle Size

This section has moved here: [https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size](https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size)

### Making a Progressive Web App

This section has moved here: [https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app](https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app)

### Advanced Configuration

This section has moved here: [https://facebook.github.io/create-react-app/docs/advanced-configuration](https://facebook.github.io/create-react-app/docs/advanced-configuration)

### Deployment

This section has moved here: [https://facebook.github.io/create-react-app/docs/deployment](https://facebook.github.io/create-react-app/docs/deployment)

### `npm run build` fails to minify

This section has moved here: [https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify](https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify)

## About the Code

This project is a simple movie application built using React. Below is a brief explanation of the main components and their functionalities:

### `src/App.js`

This is the main component of the application. It sets up the basic structure and routing for the app.

### `src/components/MovieList.js`

This component fetches and displays a list of movies. It uses the `MovieCard` component to render each movie.

### `src/components/MovieCard.js`

This component is responsible for rendering the details of a single movie, such as the title, description, and poster image.

### `src/components/MovieDetail.js`

This component displays detailed information about a selected movie. It is shown when a user clicks on a movie from the `MovieList`.

### `src/services/api.js`

This file contains functions for making API calls to fetch movie data. It abstracts the details of the API requests from the components.

### `src/styles`

This directory contains the CSS files for styling the components. Each component has its own CSS file to keep styles modular and maintainable.

### `src/utils`

This directory contains utility functions that are used across the application, such as formatting dates or handling errors.

### State Management

The application uses React's built-in state management to handle the state of the components. State is lifted up to the `App` component where necessary to manage the flow of data between components.

### Routing

React Router is used for handling navigation between different pages of the application. The routes are defined in the `App.js` file.

### Testing

The application includes tests for the components using Jest and React Testing Library. Tests are located in the `src/__tests__` directory.

### Deployment

The application can be deployed to any static site hosting service. The `npm run build` command creates a production-ready build of the app in the `build` folder.
