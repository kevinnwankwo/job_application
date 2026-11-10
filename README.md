Job Application System

A interactive CLI-based Python tool designed to automate the screening, validation, and department assignment of job applicants based on specific company age and gender criteria policies.

Key Features

Age Eligibility Screening: Automatically enforces company policies by rejecting applicants under 18 or over 50 years of age.
Smart Department Routing: Allocates successful candidates to specific corporate departments according to age and gender metrics.
Interactive Batch Processing: Loops continuously to let users process multiple applications back-to-back until they choose to stop.
Error Prevention: Robust validation filters block malformed text values entered for age metrics and invalid gender flags.

Department Placement Logic Matrix

Gender	Age Group	Assigned Department	Status

Any	Under 18	None	Disqualified

Any	Over 50	None	Disqualified

Male	18 to 24	Customer Care	Successful

Male	25 to 44	Engineering	Successful

Male	45 to 50	Security	Successful

Female	18 to 30	Customer Care	Successful

Female	31 to 50	Admin	Successful

Getting Started

Prerequisites

Python 3.x installed on your operating system.

Execution

Save the program script in a file named `job_placement.py`.

Open your terminal or command line prompt.

Run the application with the following command:

```bash
   python job_placement.py
   ```
