# React with TS + ESlint

## How to add ESLint to the project
1. Install development-only packages:
    ```bash
    npm i --save-dev eslint @typescript-eslint/parser @typescript-eslint/eslint-plugin
    ```

2. Create initial eslint configuration file
    ```bash
    eslint --init
    ```

3. (Optional) Add linting command to `package.json`
    ```json
    "scripts": {
        "lint": "eslint -c .eslintrc.js --ext .js,.jsx,.ts,.tsx ./src",
    }
    ```

## F5 Experience
### `npm start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

The page will reload if you make edits.\
You will also see any lint errors in the console.

### `npm test`

Launches the test runner in the interactive watch mode.\
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `npm run lint`

Lint the `src` folder with the predefined `.estlintrc.js` file.

### `npm run build`

Builds the app for production to the `build` folder.\
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.\
Your app is ready to be deployed!

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.
