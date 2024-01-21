# Quizzler - Quiz Application Using Open Trivia Database

## Overview

Quizzler is a Python quiz application built using the Open Trivia Database API. The application presents a series of true/false questions to the user and tracks their score. The questions are fetched from the Open Trivia Database, covering a variety of topics.

## Output


https://github.com/sarvesh-2109/Quizzler/assets/113255836/89ca15b9-092a-4ebb-845f-6a1c6863e015



## Project Structure

The project consists of several files:

- **main.py**: Initializes the quiz by creating a question bank from the Open Trivia Database and sets up the QuizBrain and QuizInterface.
- **data.py**: Fetches question data from the Open Trivia Database using the requests library and stores it for later use.
- **question_model.py**: Defines the Question class to represent quiz questions.
- **quiz_brain.py**: Implements the QuizBrain class to manage the quiz logic, track the score, and check answers.
- **ui.py**: Creates the graphical user interface using Tkinter, including labels, buttons, and a canvas for question presentation.

## Getting Started

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/quizzler.git
   ```

2. Install the required libraries:

   ```bash
   pip install -r requirements.txt
   ```

3. Run the application:

   ```bash
   python main.py
   ```

## Dependencies

- **requests**: Used to fetch data from the Open Trivia Database.
- **Tkinter**: GUI library for creating the quiz interface.

## Usage

- The application starts by fetching questions from the Open Trivia Database.
- The user is presented with true/false questions and can select their answer by clicking the corresponding buttons.
- The score is displayed, and the background changes to green for correct answers and red for incorrect ones.
- After a brief delay, the next question is presented.
- The quiz continues until all questions are answered.

## Acknowledgments

- The project uses the Open Trivia Database API for providing quiz questions.
- Inspired by learning materials on API usage, Tkinter, and Python programming.

Feel free to contribute, provide feedback, or use this project to enhance your Python and API integration skills! 🚀
