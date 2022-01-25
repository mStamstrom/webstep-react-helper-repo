## Add dropdown for difficulty level

- Create a new `Dropdown` component
- Use `Select` and `Option` HTML elements to create the dropdown
- Component should take in a list of string values as prop
- When option is selected, that value should be saved in state variable in QuizForm

## When pressing submit button, print all values in state to console.

- When submit button is clicked, emit an `event` to App component and print values from input and dropdown

Note: Submit event need to call preventDefault to not refresh page

## Call api to fetch a trivia game based on saved values.

- Copy quizRequest from helper repo
- Call api and save response to state (use async/await)

## As a user I want to choose category for my quiz

1. When mounting quiz form, fetch categories
2. When categories has been fetched, display categories in new dropdown
3. When selecting category, save selected category in a state variable
4. If category has been selected, send category with request to create quiz

## As a user I want to choose category for my quiz

1. When mounting quiz form component, fetch categories and save in state

## As a user I want to choose category for my quiz

2. When categories has been fetched, display categories in new dropdown

## As a user I want to choose category for my quiz

3. When selecting category, save selected category in a state variable

## As a user I want to choose category for my quiz

## Add a loading spinner

- Copy loading spinner from helper repo
- Add a new state to App component, isLoading
- State should default to true and be set to false once API has responded
- Display spinner when isLoading is true
