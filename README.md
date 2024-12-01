# Grade Calculator

A JavaScript project to calculate and evaluate students' grades based on their scores. This program also determines whether a student has passed or failed the course and provides a detailed report.

---

## Features

- **Calculate Class Average:** Computes the average score for a given list of student scores.
- **Grade Assignment:** Converts numerical scores into letter grades (`A++`, `A`, `B`, `C`, `D`, or `F`).
- **Pass/Fail Evaluation:** Determines if a student passes or fails based on their score.
- **User-friendly Message:** Provides a report with the class average, the student's grade, and their pass/fail status.

---


### Example Code

```javascript
console.log(studentMsg([56, 23, 89, 42, 75, 11, 68, 34, 91, 19], 100));
// Output: "Class average: 50.8. Your grade: A++. You passed the course."

console.log(studentMsg([92, 88, 12, 77, 57, 100, 67, 38, 97, 89], 37));
// Output: "Class average: 71.4. Your grade: F. You failed the course."
