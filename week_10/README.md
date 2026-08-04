# Week 10 Programming Quiz Battle
## video demo 


https://github.com/user-attachments/assets/54c13718-532d-4cf0-a796-202d77482d4b


## Scenario

Welcome to the **Java Academy Challenge!**

As a trainee programmer, this activity implements the **Programming Quiz Battle** — a Java Swing GUI that displays a programming question with two possible answers. Selecting the correct answer defeats the **Code Boss**.

## Files

| File | Purpose |
|---|---|
| `Questions.java` | Data class holding the question, two options, and the correct answer. |
| `QuizBattleGUI.java` | Swing GUI class that displays the question, handles button clicks, and shows the result. |

## Questions.java

- **Fields:** `question`, `option1`, `option2`, `answer` (all `private String`)
- **Constructor:** initializes the fields with the quiz question:
  - Question: `Which keyword creates an object?`
  - Option 1: `new`
  - Option 2: `class`
  - Correct answer: `new`
- **Methods:**
  - `getQuestion()` → returns the question text
  - `getOption1()` / `getOption2()` → return the button labels *(the "missing components" from the assignment)*
  - `isCorrect(String choice)` → compares the user's choice against the correct answer

## QuizBattleGUI.java

- Extends `JFrame` and implements `ActionListener`
- Holds a `Questions` object *(the "which class" referenced in the assignment comments)* to source the question and options
- **Constructor:**
  - Sets the window title to `Programming Quiz Battle`
  - Sets a suitable window size
  - Uses `setLayout(null)` for absolute positioning
  - Sets `JFrame.EXIT_ON_CLOSE` as the default close operation
  - Builds `lblQuestion`, `btn1`, `btn2`, and `lblResult`, positioned using the bounds specified in the assignment
  - Registers `this` as the `ActionListener` on both buttons
- **`actionPerformed(ActionEvent e)`:**
  - Retrieves the clicked button via `e.getSource()`
  - Checks the button's text against the correct answer using `question.isCorrect(...)`
  - Updates `lblResult` with `"Correct! You defeated the Code Boss!"` or `"Wrong! Try Again!"`
- **`main` method:** entry point that creates a new `QuizBattleGUI()` instance to launch the app

## How to Run

Compile and run from the folder that **contains** `week_10` (not from inside it), since both files declare `package week_10;`:

```bash
javac week_10/Questions.java week_10/QuizBattleGUI.java
java week_10.QuizBattleGUI
```

## Expected Output

A window titled **"Programming Quiz Battle"** appears showing:
- The question: *Which keyword creates an object?*
- Two buttons: `new` and `class`
- A result label initially reading *"Answer the question!"*, which updates to a correct/wrong message after clicking a button

## Git Workflow

```bash
git clone repository_url
cd repository_name
code .
# (write/complete the code)
git add .
git commit -m "Week 10: Quiz Battle GUI"
git push
```
