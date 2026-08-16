# GoStack — React Native Concepts Challenge

A study project developed during the **Rocketseat GoStack** program to practice React Native fundamentals and mobile integration with a REST API.

> **Study project:** this repository follows the GoStack learning path and is preserved as part of my technical learning history.

## What the project does

The mobile application consumes the repositories API created in the Node.js challenge and displays repository information on a native interface.

Main behaviors include:

- Load repositories from the backend
- Display repository title and technologies
- Display the current number of likes
- Send a like to a repository through the API
- Refresh the local state with the updated like count

## Tech stack

- React Native 0.62
- React 16
- JavaScript
- Axios
- React Hooks
- React Native Testing Library
- Jest
- ESLint

## Concepts practiced

- Functional React Native components
- `useState` and `useEffect`
- REST API consumption with Axios
- `FlatList` rendering
- Mobile styling with `StyleSheet`
- User interaction with `TouchableOpacity`
- Updating state after asynchronous requests
- Mobile component testing

## Running the project

Install dependencies:

```bash
yarn
```

Start Metro:

```bash
yarn start
```

Run on Android:

```bash
yarn android
```

Or on iOS:

```bash
yarn ios
```

Run the tests:

```bash
yarn test
```

The application expects the related Node.js repositories API to be available according to the original course configuration.

## Project context

Created in 2020 as part of Rocketseat's GoStack React Native fundamentals challenge. The implementation is intentionally preserved close to the original exercise to document the mobile development concepts practiced at that stage of my learning path.

---

**William Figueiredo**  
Software Engineering → AI Engineering
