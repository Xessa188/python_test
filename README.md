# Requirements Design & EC/BV

[🔗 Click here to view the Google Sheet](https://docs.google.com/spreadsheets/d/1BOeksGA5oWXE7ZgPqmtmCbhdXT_TwzXNc1QoOLsIlxY/edit?gid=2127844572#gid=2127844572)

## What is this project?
This project shows how I take software feature requirements and break them down into practical QA test cases. I wanted to map out exactly how to test a system to ensure it doesn't break when users input unexpected data.

## What I worked on:
* **Breaking down requirements:** Took complex rules—like string formatting, character limits, and conditional buttons—and turned them into individual test steps.
* **Finding edge cases:** Used Equivalence Partitioning (EP) and Boundary Value Analysis (BVA) to figure out exactly where the system might fail (like testing what happens right at a 12-character limit).
* **Test Design:** Organized everything into a clean QA sheet featuring Equivalence Classes, Boundary Values, and full Test Cases.

## Scenarios covered in the sheet:
1. **Input Fields:** Testing how the system handles spaces, max character counts, and numeric boundaries.
2. **Button Logic:** Checking if buttons correctly stay disabled until the user meets specific criteria.
3. **Calculations:** Verifying that total travel times and pricing rules calculate the right numbers every time.
