#  https://github.com/Mo2888/quiz-app
#This JavaScript code is used to create a quiz application. It interacts with an external JSON file containing quiz questions and handles user interactions and scoring. Here's a breakdown of the key functionality:

Selecting Elements: The code begins by selecting various HTML elements (e.g., questions, answers, countdown) using the document.querySelector method.

Setting Options: It initializes variables like currentIndex to track the current question index and rightAnswers to keep track of correct answers. It also sets up a countdownInterval variable for the timer.

Fetching Questions: It makes an XMLHttpRequest to fetch quiz questions from an external JSON file called "Questions.json."

Creating Bullets: Dynamically creates bullets (representing quiz questions) based on the number of questions fetched.

Adding Question Data: Adds the question and answer choices to the HTML based on the current question index.

Starting Countdown: Initiates a countdown timer for each question, with a default time of 10 seconds.

Handling Submit: Listens for a click event on the "Submit" button. When clicked, it checks the selected answer, updates the score, and loads the next question.

Checking Answers: Compares the selected answer with the correct answer to determine correctness.

Handling Bullets: Updates the active bullet (question) based on the current question index.

Showing Results: Displays the quiz results when all questions have been answered. It removes the quiz-related elements and shows the user's score.

Countdown Function: Manages the countdown timer. It updates the timer display and triggers a click on the "Submit" button when time runs out.

