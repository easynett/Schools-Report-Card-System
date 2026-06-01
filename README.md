# Semi-Automated Report Card Generation System

## INTRODUCTION

I came up with an idea, and now it's live — a fully functional Semi-Automated Report Card Generation System for secondary schools, capable of handling reports from 1st Term to 3rd Term, entirely created using **Microsoft Excel**.

---

## SCREENSHOTS

### End of Session Leaderboard
![Leaderboard](images/leaderboard.png)

### Broadsheet Interface
![broadsheet](images/broadsheet.png)

### Individual Student Report Card (1st, 2nd & 3rd term)
![Report Card](images/report-card.png)

### Comments & Ranking Sheet
![Comments Sheet](images/comments-sheet.png)

---

## EXECUTIVE SUMMARY

Manual report cards are no longer being used in modern Nigerian schools. However, some schools may not be able to afford fully automated online solutions and their recurring termly costs.

In response to this, I created a semi-automated Report Card Generation System for secondary schools, capable of handling reports from First Term to Third Term with cumulative results.

This solution helps schools transition from the old manual method to a modern approach, as every process requires only a PC and significantly reduces costs since the solution operates primarily offline.

However, to reflect a modern working environment, ICT compliance, and adaptability, Google Sheets is partly used to collect subject teachers' scores, which are later copied into the offline solution where report cards for all students are automatically generated.

---

## SOFTWARE USED

- Microsoft Excel

---

## EXCEL FUNCTIONS AND TOOLS USED

a. Data Validation: List & Value Range  
b. Conditional Formatting  
c. Sort & Filter  
d. Relative, Absolute, Mixed & 3D References  
e. Cell, Worksheet & Workbook Protection  
f. Freeze Panes  
g. Basic Excel Functions: SUM, AVERAGE, COUNT, COUNTA, IF, RANK  
h. Advanced Excel Functions: VLOOKUP, XLOOKUP, INDEX-MATCH, IFERROR

---

## WORKBOOK LAYOUT

The workbook consists of approximately 30 worksheets.

- Sheet1 is renamed **1st Term**
- Sheet2 is renamed **2nd Term**
- Sheet3 is renamed **3rd Term**
- Sheet4 is renamed **Comments**
- The remaining sheets (Sheet5 to Sheet30) hold the actual report cards for individual students.

### Worksheet Functions

- **1st Term Sheet** serves as the broadsheet for all students' scores for the First Term.
- **2nd Term Sheet** serves as the broadsheet for all students' scores for the Second Term.
- **3rd Term Sheet** serves as the broadsheet for all students' scores for the Third Term.
- **Comments Sheet** serves as the data source for fetching student positions (rank), attendance scores, and individual subject averages, which are then displayed on the individual student report cards.

---

## WORKBOOK PROTECTION AGAINST USER ERROR

The workbook is protected with a password to prevent accidental renaming, deletion, or hiding of worksheets by users.

Each worksheet is password-protected to ensure the design and layout remain intact and to prevent unauthorized modifications.

Cells are protected to prevent users from entering data outside the permitted areas.

Data Validation is used to ensure that only approved values are selected from dropdown lists or entered into designated cells.

---

## LOOKING UP STUDENT SCORES

The student name, sorted alphabetically on the **1st Term** worksheet, serves as the lookup value used to connect each student with their corresponding subject scores (CA & Exam) recorded in the broadsheet.

A future update will make use of **Student IDs** to handle cases where two or more students have identical names.

---

## HOW THE SYSTEM WORKS

Subject teachers enter individual student scores (CA & Exam) online through a Google Sheets link provided. The Google Sheet is structured exactly the same as the broadsheet.

Class teachers monitor their class worksheet online to ensure all subject teachers have entered their scores. Once completed, they copy the entire score sheet and paste it into the Report Card System.

**BOOM!** All students' report cards are instantly ready for printing.

The Comments Sheet calculates each student's average score and automatically assigns rankings based on those averages.

Class Teacher comments and Principal comments are selected from dropdown lists on the individual report card pages.

---

## FUTURE UPDATE

As a Data Analyst, uncovering insights and telling data-driven stories is part of our role. A future update will include a **Leaderboard Dashboard**.

### KPI

- Total Number of Students
- Session Overall Best Student
- Session Best Student in Mathematics
- Session Best Student in English Language
- Session Best Student in ICT
- Session Most Improved Student
- Session Best Class

### Pivot Charts

- Top Ten Students (Overall)
- Top Ten Students in Mathematics
- Top Ten Students in English Language
- Top Ten Students in ICT
- Best Student by Gender
- Comparison of Subject Performance

### Slicers

- Best Student per Subject
- Best Student by Gender
- Best Student per Term
- Best Student by Class (JSS1A, JSS1B, JSS1C)
- Best Class per Term

---

## APPRECIATION

My profound gratitude goes to IOTB Tech Fellowship and Tektariq for making this journey possible.

Special appreciation goes to:

- Our Faculty Lead, Kishky
- Lead People Admin
- All Data Force Mentors
- My Accountability Group Mentor, Sir Teabay

Thank you all for what you do.

**The best is yet to come!**

---

## LICENSE / PASSWORD

You are free to use, modify, distribute, and improve this project without prior written notification, provided this project is not used for commercial purpose.

Workbook PW: easynett

Worksheet PW: 222

---

## AUTHOR

**Ishaq Ismail**

Data Analyst | Excel Developer | Business Intelligence Enthusiast

Passionate about building practical data-driven solutions that solve real-world problems. This project demonstrates how Microsoft Excel can be leveraged to create efficient, cost-effective systems for educational institutions.

Feel free to connect, collaborate, or provide feedback on this project.

---

www.linkedin.com/in/easynett | www.github.com/easynett | info2easynett@gmail.com