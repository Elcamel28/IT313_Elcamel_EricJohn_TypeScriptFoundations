
# IT313 TypeScript Foundations

## Problem
The Enrollment Eligibility Checker calculates student averages and determines whether students are passing or on probation.

## TypeScript Concepts Used
- Basic types: specify strings, numbers, and return values.
- Interfaces: define student and report data.
- Enum: represents Passing and Probation statuses.
- Optional property: remarks is only included for students on probation.
- Union type: batchId can be a string or number.
- Type narrowing: typeof checks the batchId type.
- Generics: groupBy groups reports by status.
- Modules: import and export reusable functions.
- Async/await and try/catch: simulate retrieving student records and handle errors.
- map and reduce: create reports and calculate the class average.
- Template literals: format report output.

## How to Run

Install dependencies:

npm install

Check for type errors:

npx tsc --noEmit

Run the program:

npx ts-node main.ts
