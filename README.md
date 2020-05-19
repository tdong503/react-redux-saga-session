## Quick start

1. Clone this repo using `git clone git@github.com:berrrrt/react-redux-saga-session.git`
2. Move to the appropriate directory: `cd react-redux-saga-session.gite`.<br />
3. Run `yarn` or `npm install` to install dependencies.<br />
4. Run `npm start` to see the example app at `http://localhost:3000`.
5. Run `yarn test` or `npm test` to run tests

## Practice

1. Fix the failed snapshot tests
2. Add an api call to below api, and display the result with a new page
   https://thoughtworks-mobile-2018.herokuapp.com/user/jsmith/tweets
   - Add a new container with preferred route name
   - Add component to display the json content
   - Add snapshot tests for the new route and component
   - Add saga and related tests to fetch data
   - Add action and reducers and related tests to save the fetch data
