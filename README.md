**Program Name**: College Student Tuition Management

**Description**:

This C++ program is designed to manage student tuition records for a college. It allows the user to add student details, including their name, residency status (In-State or Out-of-State), tuition fees, and optional health plan enrollment. The program can also generate a report that displays the total tuition paid by both In-State and Out-of-State students.

**Usage**:

1. Compile the program and run the executable.
2. Follow the on-screen menu to add student details or generate a report.

**Menu Options**:

- **Add Student Details**: This option allows you to add a new student's information, including name, residency status, tuition fees, and optional health plan enrollment.

- **Generate Report**: This option generates a report in a text file named "tuition_report.txt" that displays the total tuition paid for In-State and Out-of-State students.

- **Exit**: Use this option to exit the program.

**Data Storage**:

Student records and the report are stored in a text file named "tuition_report.txt." The program appends new records and report data to this file.

**Sample Output**:

Upon running the program, you'll see a menu like this:

```
## (College Student Tuition) ##
1 Add Student Details
2 Generate Report
-1 Exit

Enter your choice:
```

- When you choose "Add Student Details," you can input a student's name, residency status, tuition fees, and whether they want to enroll in a health plan.

- When you choose "Generate Report," the program calculates and appends the total tuition paid by In-State and Out-of-State students to the "tuition_report.txt" file.

- Choosing "Exit" will exit the program.

**Output Format**:

Here's an example of the contents of "tuition_report.txt" after using the program:

```
John Doe | In-State | Health Plan : E | 500
Jane Smith | Out-Of-State | Health Plan : S | 700
Total Tuition Paid for all In-State Students : 500
Total Tuition Paid for all Out-of-State Students : 700
```

The report includes student details and the total tuition paid for each category.

**Notes**:

- The program handles both In-State and Out-of-State tuition fees, along with optional health plan costs.
- It appends records to the file, so you can use the program multiple times to add more students.
- The program provides clear prompts and error messages.
- Please note that the "gets" function is generally unsafe for user input, and it is recommended to use "getline" instead to read user input safely.
