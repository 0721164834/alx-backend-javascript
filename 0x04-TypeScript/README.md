# TypeScript

This project contains tasks for learning to use TypeScript.

## Tasks To Complete

+ [x] 0. **Creating an interface for a student**<br/>[task_0/js/main.ts](task_0/js/main.ts) contains a script that meets the following requirements:
  + Write an interface named `Student` that accepts the following elements: `firstName(string)`, `lastName(string)`, `age(number)`, and `location(string)`.
  + Create two students, and create an array named `studentsList` containing the two variables.
  + Using Vanilla Javascript, render a table and for each elements in the array, append a new row to the table.
  + Each row should contain the first name of the student and the location.
  + When running, Webpack should return `No type errors found`.
  + Every variable should use TypeScript when possible.

+ [x] 1. **Let's build a Teacher interface**<br/>[task_1/js/main.ts](task_1/js/main.ts) contains a script that meets the following requirements:
  + `firstName(string)` and `lastName(string)`. These two attributes should only be modifiable when a Teacher is first initialized.
  + `fullTimeEmployee(boolean)` this attribute should always be defined.
  + `yearsOfExperience(number)` this attribute is optional.
  + `location(string)` this attribute should always be defined.
  + Add the possibility to add any attribute to the Object like `contract(boolean)` without specifying the name of the attribute.

+ [x] 2. **Extending the Teacher class**<br/>[task_1/js/main.ts](task_1/js/main.ts) contains the following updates:
  + Write an interface named `Directors` that extends `Teacher`. It requires an attribute named `numberOfReports(number)`.

+ [x] 3. **Printing teachers**<br/>[task_1/js/main.ts](task_1/js/main.ts) contains the following updates:
  + Write a function `printTeacher`:
    + It accepts two arguments `firstName` and `lastName`.
    + It returns the first letter of the `firstName` and the full `lastName`.
    + Example: `printTeacher("John", "Doe") -> J. Doe`.
  + Write an interface for the function named `printTeacherFunction`.
