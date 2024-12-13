# Brain-Teaser: Interactive Quiz Application in Python

**Brain-Teaser** is an interactive Python-based quiz application that allows users to test their knowledge with custom quiz questions. The application loads questions from an external text file, presents them to the user, and provides instant feedback based on the answer selection.

## Features

- **Dynamic Question Loading**: The quiz questions, options, and correct answers are loaded from a text file. This makes the quiz easily customizable and scalable.
- **Real-Time Feedback**: After each question, the user receives immediate feedback on whether their answer is correct or incorrect.
- **User-Friendly**: Simple command-line interface for easy interaction.
- **Modular Code**: The program is structured using functions for better readability, reusability, and scalability.
- **Flexible Question Format**: The application supports a structured question format (`Question|Option1|Option2|Option3|Option4|CorrectOptionIndex`), making it easy to edit or add new questions.

## Prerequisites

Before running the project, ensure you have Python installed on your system.

- Python 3.x or higher

## Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/Aritri2001/brain-teaser.git
    ```

2. Navigate to the project directory:
    ```bash
    cd brain-teaser
    ```

3. (Optional) Create a virtual environment and install any required dependencies:
    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
    ```

4. There are no external dependencies for this project, so you can run it as is.

## Usage

1. Open the `questions.txt` file to add or edit questions. The format should be:
    ```
    What is the capital of France?|Paris|London|Berlin|Rome|1
    What is 2 + 2?|3|4|5|6|2
    ```

2. Run the Python script:
    ```bash
    python brain_teaser.py
    ```

3. Follow the prompts in the terminal to take the quiz and receive feedback.




## USER INPUT DOCUMENT:
![image](https://github.com/user-attachments/assets/d8725ccb-2d82-4c8f-ad8a-7bb5cab003f9)

## DATABASE OUTPUT:
![image](https://github.com/user-attachments/assets/8fede800-5694-453d-bf11-7c86d002e8be)
