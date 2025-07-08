# 🎓 Student Grading Program

This is a simple Python program that accepts a student's score as input and returns the corresponding grade based on predefined grading criteria.

---

## 📌 Features

- Accepts user input for a student's score (0–100)
- Validates the input to ensure it's a numeric value
- Classifies the score into grades (A–F)
- Handles invalid or out-of-range inputs gracefully

---

## 📊 Grading Criteria

| Score Range | Grade |
|-------------|-------|
| 70 - 100    | A     |
| 60 - 69     | B     |
| 50 - 59     | C     |
| 45 - 49     | D     |
| 40 - 44     | E     |
|  0 - 39     | F     |

---

## 🧠 How It Works

1. The program prompts the user to enter a numeric score.
2. It checks:
   - If the input is a valid number.
   - If the score is between 0 and 100.
3. It compares the score against grading thresholds.
4. It prints the corresponding grade (A–F).
5. If the input is not a number or outside the allowed range, it shows an appropriate error message.

---

## 💻 Example Output

Enter student's score (0 - 100): 76
Grade: A

Enter student's score (0 - 100): 42
Grade: E

Enter student's score (0 - 100): -5
Invalid score: must be between 0 and 100

Enter student's score (0 - 100): abc
Invalid input: please enter a numeric value.

---

## ✅ Requirements

- Python 3.x

---

## 📂 How to Run

1. Save the code in a file called `grading.py`
2. Open a terminal or command prompt
3. Run the program:

```bash
python grading.py

```

✍️ Author

Victor Efobi
