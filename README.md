# Getting Started with Create React App

Using ReactJS create a Pokemon App with the followings:
SPECIFICATIONS
Create a multiple page application with ReactJS.
First page will display all the pokemon, with lazy loading. Another page will show the detail of a specific pokemon.
Your application will also provide a search bar to filter pokemon.
This application will use an external API, you can find the documentation a this link
In order to perform the request to the API, you can use Axios.
Your application needs to handle errors. (No internet/bad request.)

REQUIREMENTS
No more than 1 components per file. Additionals components will be in src/components/
CSS will be in a file associated to the component: css for ExampleComponent.js will be in ExampleComponent.css.
Your Readme will have to describe the project. Your .gitignore must remove node_modules/
On the css/colors/design, you can be creative.

## Description
This is a React application that fetches and displays data from the Pokémon API to showcase Pokémon information. 
The app includes a list of Pokémon, their details, and a search functionality to filter through the Pokémon based on their names.

Features:
Pokémon List Page: Displays a list of Pokémon with their names, images, and a link to view more details.
Pokémon Detail Page: Displays detailed information about each Pokémon including their height, weight, base experience, abilities, and types.
Search Functionality: Allows users to search for Pokémon by name.
Responsive Layout: The app layout adjusts according to the screen size (6 Pokémon cards per row on larger screens, 2 per row on smaller screens).
Styled Using Bootstrap: The app is styled using Bootstrap with custom color schemes for different Pokémon types.

## Installation
Prerequisites
-Node.js and npm
-Install Dependencies
-Install the necessary dependencies using npm:
-npm install

## Usage
-Clone the Repository
-cd pokemon-react-app
-npm install
-npm start

Link to the cloud hosting: "https://aliyupokemonapp.netlify.app/"

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
