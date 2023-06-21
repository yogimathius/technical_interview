### Code Review: Generate Student Report
You have been given a piece of code that is intended to generate a report based on a list of students and their grades. The code has been written by another developer, but it contains several bad practices and could be improved. Your task is to review the code and provide recommendations on how to improve it.

Here is the code:

```
const students = [
  { name: "Alice", grade: 85 },
  { name: "Bob", grade: 90 },
  { name: "Charlie", grade: 78 },
  { name: "David", grade: 92 },
  { name: "Eve", grade: 88 }
];

function generateReport(s) {
  let report = "";
  for (let i = 0; i < s.length; i++) {
    let x = s[i];
    report = report + "Student Name: " + x.name + "\n";
    report = report + "Grade: " + x.grade + "\n";
    report = report + "-------------------------------------\n";
  }
  console.log(report);
}
```

Your task is to review the code and provide recommendations for improvement. Focus on the bad practices present in the code and suggest better approaches or best practices that can be followed. Consider factors such as code readability, efficiency, error handling, and overall code structure.

