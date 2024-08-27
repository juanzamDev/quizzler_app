# Quizzler

Quizzler is a Python-based quiz application that fetches trivia questions from the Open Trivia Database and presents them to the user in a graphical interface.

## Project Structure

The project consists of several Python files, each responsible for a specific part of the application:

- `data.py`: Fetches quiz questions from the Open Trivia Database API.
- `question_model.py`: Defines the Question class to represent individual quiz questions.
- `quiz_brain.py`: Manages the quiz logic, including tracking score and progressing through questions.
- `ui.py`: Implements the graphical user interface using Tkinter.
- `main.py`: Ties all components together and runs the application.

## Features

- Fetches 10 boolean (True/False) questions from the Open Trivia Database.
- Presents questions one at a time in a graphical interface.
- Allows users to answer by clicking "True" or "False" buttons.
- Provides immediate feedback on the correctness of answers.
- Tracks and displays the user's score throughout the quiz.
- Handles HTML-encoded characters in questions.

## Requirements

To run this project, you'll need:

- Python 3.x
- `requests` library for API calls
- Tkinter (usually comes pre-installed with Python)

## Installation

1. Clone this repository or download the source files.
2. Install the required `requests` library:

   ```
   pip install requests
   ```

3. Ensure you have the necessary image files (`true.png` and `false.png`) in an `images` folder in the project directory.

## Usage

To start the quiz application, run the `main.py` file:

```
python main.py
```

The application window will open, and you can begin answering questions by clicking the "True" or "False" buttons.

## Customization

You can customize the quiz by modifying the `parameters` dictionary in `data.py`. For example, you can change the number of questions or the type of questions fetched from the API.

## Contributing

Contributions to improve Quizzler are welcome. Please feel free to submit a Pull Request.

## License

This project is open source and available under the [MIT License](LICENSE).

