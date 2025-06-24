#📋 How It Works
quizQuestions: Array of question objects (question, options, correctAnswer index).

###Screens:###

Start: displays heading and “Start Quiz” button.

Quiz: shows current question and options. After selection, you can submit and move to next question.

Result: reveals your score out of total questions and allows resetting the quiz.

Flow:

User clicks “Start Quiz” → moves to Quiz screen.

User selects an option → Submit becomes active.

Clicking Submit validates and highlights answers.

If questions remain ➝ “Next Question”

If last ➝ “Show Results”

Result Screen displays score; “Play Again” resets.
