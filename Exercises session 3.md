## Lift state quizQuestions

- Move the fetched quiz state up to App.tsx

### As a user, I want to see the first question of the quiz with possible answers

- Create QuizPage and QuestionHandler components under features/quiz-page/.
- QuizPage takes in all questions as prop and QuestionHandler displays first question
- QuizPage should be displayed if we have fetched answers (Update render in App.tsx and check length of Question state)
- QuestionHandler also displays possible answers for question (use `<button>` element and `map()` function to render several buttons)

## Keeping score

- As a user, I want to answer a question.
- As a user, I can only answer a question once.
- As a user, I want to see if my answer was correct.
- As a user, I want to see my total score.

## As a user, I want to answer a question

- Add a state variable for all submitted answers for user
- When clicking a answer button, save that answer in state variable

## As a user, I can only answer a question once.

- If user has answered the current question, disable buttons

# Install clsx

`npm install --save clsx`

<aside class="notes" data-timing="2 min" ></aside>

## As a user, I want to see if my answer was correct.

- When user selects an answer, set class selectedAnswer on that option.
- When user selects an correct answer, set class correctAnswer on that option.
- When user selects an incorrect answer, set class wrongAnswer on that option.

## As a user, I want to see my total score.

- At the top of the page, display how many questions was correctly answered
- Also display which question the user is on

## As a user, I want go to the next question.

- Add a button, that when clicked, updates the selected question

## As a user, after completing a quiz, I want to see a summary

- Display total score of quiz
- Add a button to create a new quiz

## Deploy with github pages

https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site#choosing-a-publishing-source

`npm run deploy`
