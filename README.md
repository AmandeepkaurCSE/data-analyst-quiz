## 📋 How It Works

### `quizQuestions`
Array of question objects:
- `question`: The quiz question text.
- `options`: Array of answer choices.
- `correctAnswer`: Index of the right option.

### Screens
1. **Start**: Displays heading and **Start Quiz** button.  
2. **Quiz**: Shows current question and options. After selection, **Submit** becomes active.  
3. **Result**: Reveals your final score.

### Flow
1. User clicks **“Start Quiz”** → moves to Quiz screen.  
2. User selects an option → **Submit** becomes active.  
3. Clicking **Submit** validates and highlights answers:  
   - Highlights correct answer in green, wrong in red.  
4. If questions remain → button shows **Next Question**, loads next.  
   If last question → button shows **Show Results**.  
5. **Result Screen** displays score (e.g. “7/10”); **“Play Again”** resets quiz.
