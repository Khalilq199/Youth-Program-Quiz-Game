# Youth Program Quiz Game 🎮

This **Knowledge Quiz Game** was created for a youth program, where kids could test their knowledge on various topics of the day. It received an impressive **95% satisfaction rate** from participants due to its interactive and educational nature. Built using Python, the game presents questions to users, tracks their answers, and provides immediate feedback along with their final score.

## 🚀 Project Overview

The quiz game dynamically displays a series of questions with multiple-choice answers. Users input their responses, and the program keeps track of their score, showing their results at the end. The goal of the game is to make learning fun and engaging for youth, encouraging them to improve their knowledge while enjoying the process.

### Key Features:
- **Multiple-Choice Questions**: Questions are presented from a pre-defined list, users select answers from four possible options (A, B, C, D).
- **Answer Validation**: Logical operators compare the user's input with the correct answer and immediately provide feedback.
- **Score Calculation**: The program calculates the final score as a percentage based on the number of correct answers.
- **Result Feedback**: Users are shown their final results and performance messages based on their score.

## 🛠️ Technical Overview

- **Question and Option Storage**: 
  - Questions and answer options are stored in tuples (`questions` and `options`), allowing easy access and iteration during the quiz.
- **Input Handling**: 
  - The user input is captured via `input()`, and their response is validated by converting it to uppercase using `.upper()` to ensure consistency.
- **Answer Validation**: 
  - The user's input is compared to the correct answer using an `if` statement. If the answer matches, their score is incremented.
- **Score Calculation**: 
  - At the end of the quiz, the score is converted to a percentage by dividing the correct answers by the total number of questions. 
  - The final score is displayed, and the user is given a performance assessment based on their result.
  
### Core Logic Breakdown:

- **Storing Data**: 
  - The quiz uses tuples (`questions`, `options`, `answers`) to store the list of questions, possible answer options, and correct answers.
  - The `guesses` list tracks the user's input.
- **Answer Checking**: 
  - After each question, the user's answer is compared to the correct answer using an `if` statement. If the answer is correct, the user is notified and the score is updated.
- **Final Results**: 
  - Once all questions are answered, the program displays the correct answers, the user's answers, and calculates the final score as a percentage.
  - The user receives personalized feedback depending on their score.

## 📬 Contact

For questions, collaboration, or contributions, feel free to reach out:

- **Khalil Ahmad Qamar**  
- [LinkedIn](https://linkedin.com/in/khalil-ahmad-qamar/)  
- [Email](mailto:your.email@example.com)
