GradeWise – Student Grade Calculator:
         A simple React app for calculating student marks, percentages, and grades, and for keeping a list of saved student results.

Features:
● Enter a student's name, roll number, and marks for five subjects
● Instant calculation of total, average, percentage, grade, and pass/fail status
● Input validation (required fields, marks must be between 0 and 100)
● Save results to a records table and delete them when no longer needed
● Three pages: Home, Calculator, and Records

Subjects:
Marks are entered out of 100 for each of the following:
1) Mathematics
2) Physics
3) Chemistry
4) Computer Science
5) English
The maximum total is 500.

Grading Scale: 

Percentage         Grade

90 and above       A+
80 – 89            A
70 – 79            B
60 – 69            C
50 – 59            D
Below 50           F

Pass rule: a student passes only if they score at least 35 in every subject. A student who fails any subject receives grade F and a "Fail" status, regardless of overall percentage.

Tech Stack:
● React (hooks: useState)
● Plain CSS (App.css, index.css)
● Vite-style entry point (main.jsx)

Project Structure:

src/
├── App.jsx      # Home, Calculator, and Records pages + app state
├── App.css      # App styles
├── index.css    # Global styles
└── main.jsx     # React entry point

Getting Started:
Prerequisites:
● Node.js 18 or later
● npm

Installation:
# Clone the repository
git clone <your-repo-url>
cd <your-project-folder>

# Install dependencies
npm install

# Start the development server
npm run dev
Then open the local URL shown in the terminal (usually http://localhost:5173).

Build for Production:
npm run build

How to Use:
1) Open the Calculator page.
2) Enter the student's name and roll number.
3) Enter marks (0–100) for all five subjects.
4) Click Calculate Result to see the total, average, percentage, grade, and status.
5) Click Save Student Record to add the result to the Records page.
Use Delete on the Records page to remove a record.
