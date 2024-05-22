# demo_intern
Online Quiz Application Using Java Programming 
Basic Description for the Online Quiz Application:-
The Online Quiz Application is a simple Java program that conducts a general knowledge quiz. The program is designed to ask the user six questions, record their answers, and calculate their final score based on the correct responses. Below is a detailed description of the classes used in the project.
-->Classes Used:
Question Class:-
->Purpose: To represent a single quiz question.
-->Attributes:
->questionText: A string containing the text of the question.
->options: An array of strings containing the answer options.
->correctOption: An integer representing the index of the correct answer option.
-->Methods:
->Constructor: Initializes the question text, options, and the correct option.
->Getter Methods: getQuestionText(), getOptions(), getCorrectOption() to retrieve the respective attributes.
-->Quiz Class:
->Purpose: To manage the quiz, including storing questions, starting the quiz, and calculating the score.
-->Attributes:
->quizTitle: A string representing the title of the quiz.
->questions: A list of Question objects representing the questions in the quiz.
->score: An integer to keep track of the user's score.
-->Methods:
->Constructor: Initializes the quiz title and sets up the questions list and score.
>addQuestion(Question question): Adds a Question object to the quiz.
>start(): Conducts the quiz by iterating over the questions, presenting them to the user, and checking their answers.
>getScore(): Returns the user's final score.
-->Note==As I Have Coded in Eclipse IDE as we can Run in Any compiler
--> Reference Outputs==
![Screenshot 2024-05-22 213751](https://github.com/naveen22999/demo_intern/assets/170524966/e90cd0be-618d-4417-aa2a-708f43d7b79a)
![Screenshot 2024-05-22 213907](https://github.com/naveen22999/demo_intern/assets/170524966/0ecc8744-c36a-4a51-a295-946194f1d9a0)
![Screenshot 2024-05-22 213923](https://github.com/naveen22999/demo_intern/assets/170524966/e3814b10-35e0-4624-b863-203ef7b673f4)
![Screenshot 2024-05-22 213934](https://github.com/naveen22999/demo_intern/assets/170524966/46bfd29d-20ea-41d6-a071-9e56ca2e40d8)



