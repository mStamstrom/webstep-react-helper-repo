# Exercises session 1

## Create a QuizForm page

- Create a new component QuizFormPage
- Add a title to the render function
- Add a HTML form element to the render function
- Add Submit button inside the form

## Add a Input component

- create a component named `Input`
- the `Input` component should return a `<input />` element
- `<input />` should be of `type` number
- add the `Input` component in QuizFormPage components render function
- when typing in `<input />`, the input value should be emitted and saved in a state variable in the QuizFormPage component

## Add dropdown for difficulty level

- Create a `Dropdown` component
- Use `Select` and `Option` HTML elements to define dropdown
- Component should take in a list of string values as prop
- When option is selected, that value should be saved in state variable in QuizForm

## When pressing submit button, print all values in state to console.

- use event to call function in App component
- Print values in console from App components

Note: Submit event need to call preventDefault to not refresh page

## Call api to fetch trivia game based on values in state in App component.

- Copy quizRequest from helper repo
- Call api and save response to state (use async/await)

## Call api to fetch trivia game based on values in state in App component.

- Add difficulty level to request
