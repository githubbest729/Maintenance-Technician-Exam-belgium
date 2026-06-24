================================================================================
README - Maintenance Technician Pre-Employment Assessment (Belgium)
================================================================================
 
File: maintenance_technician_exam_belgium.html
Created for: Industrial Maintenance Hiring / Pre-Employment Screening
Target role: Maintenance Technician - Factory / Production Environment (Belgium)
Language: English
 
 
--------------------------------------------------------------------------------
OVERVIEW
--------------------------------------------------------------------------------
 
This is a single self-contained HTML file that runs a randomised pre-employment
technical assessment exam for Maintenance Technician candidates. It requires no
internet connection, no external libraries, and no installation. It works by
opening the file directly in any modern web browser.
 
The exam is designed for candidates with approximately 3 to 10 years of
industrial maintenance experience working in a factory or production plant
environment.
 
 
--------------------------------------------------------------------------------
HOW TO USE
--------------------------------------------------------------------------------
 
1. Copy the file maintenance_technician_exam_belgium.html to any location.
2. Open the file in a web browser (Chrome, Edge, Firefox, or Safari).
3. The exam loads automatically with a random set of 20 questions.
4. The candidate reads each question and selects one answer per question.
5. When all 20 questions are answered, click Submit Exam.
6. The result, score, and answer review are displayed immediately.
7. The candidate can click Retry Exam to take the exam again with a new
   random set of 20 questions drawn from the full 40-question bank.
 
 
--------------------------------------------------------------------------------
QUESTION BANK
--------------------------------------------------------------------------------
 
Total questions in the bank: 40
 
The 40 questions are split across three categories:
 
  - Multiple Choice: 24 questions
  - True or False:    8 questions
  - Scenario-Based:   8 questions
 
Each time the exam loads or is retried, the system randomly draws:
 
  - 12 Multiple Choice
  -  4 True or False
  -  4 Scenario-Based
  -------------------------
    20 questions per attempt
 
This means candidates will rarely see the exact same combination of questions
twice, making the exam suitable for repeat attempts without memorisation.
 
 
--------------------------------------------------------------------------------
TOPICS COVERED
--------------------------------------------------------------------------------
 
The question bank covers the following industrial maintenance topics:
 
  - Preventive vs corrective maintenance principles
  - Electric motor troubleshooting (overload, phase imbalance, insulation)
  - Gearbox inspection, oil analysis, and seal replacement
  - Pump troubleshooting (no flow, mechanical seal failure, cavitation)
  - Conveyor and transport band fault diagnosis
  - Bearing overheating and lubrication (grease type, quantity, frequency)
  - V-belt drives, coupling alignment, and mechanical adjustments
  - Reading electrical diagrams and mechanical schematics
  - Sensors: inductive proximity, photoelectric, analogue (4-20 mA)
  - Actuators: solenoid valves and pneumatic cylinder faults
  - Contactors, overload relays, fuses, and motor starters
  - Frequency drives / VFD fault codes (overcurrent, overtemperature)
  - PLC troubleshooting: Siemens S7, Allen-Bradley MicroLogix
  - PLC I/O checks, output vs field fault diagnosis
  - Hydraulic system basics (cylinder drift, valve leakage)
  - Vibration analysis basics (1X imbalance signature)
  - Thermal imaging for electrical panel inspection
  - CMMS documentation and maintenance history
  - MTBF and reliability concepts
  - Safe isolation, LOTO procedures, and restart safety
  - Production downtime reduction and reliability mindset
 
 
--------------------------------------------------------------------------------
SCORING
--------------------------------------------------------------------------------
 
  Total points:         100
  Points per question:    5
  Pass mark:             75 points (75%)
  Number of questions:   20 per attempt
 
  Pass:  Score of 75 or above
  Fail:  Score below 75
 
 
--------------------------------------------------------------------------------
RESULTS AND ANSWER REVIEW
--------------------------------------------------------------------------------
 
After clicking Submit Exam, the page displays:
 
  - PASS or FAIL verdict
  - Total score in points (example: 80 / 100)
  - Percentage score
  - Number of correct answers out of 20
  - Number of incorrect answers out of 20
 
Each question on the page is then highlighted:
 
  - Green border and green highlight = correct answer
  - Red border and red highlight    = incorrect selection
  - A short explanation is shown below each question explaining
    why the correct answer is right
 
 
--------------------------------------------------------------------------------
BUTTONS
--------------------------------------------------------------------------------
 
  Submit Exam         Calculates and displays the score and answer review.
                      All questions must be answered first.
 
  Reset Exam          Clears all selected answers and removes the result.
                      Keeps the same set of 20 questions on screen.
 
  Retry Exam          Draws a fresh random set of 20 questions from the
                      40-question bank and starts the exam from scratch.
 
 
--------------------------------------------------------------------------------
TECHNICAL DETAILS
--------------------------------------------------------------------------------
 
  File type:          Single HTML file
  Dependencies:       None (no CDN, no external libraries, no internet required)
  Offline use:        Yes - works fully offline
  Browser support:    Chrome, Edge, Firefox, Safari (any modern version)
  CSS / JS:           Fully embedded inside the HTML file
  Question selection: JavaScript randomisation on page load and on retry
  Data storage:       No data is stored, saved, or transmitted anywhere
 
 
--------------------------------------------------------------------------------
CUSTOMISATION NOTES
--------------------------------------------------------------------------------
 
If you need to modify the exam, open the HTML file in any text editor.
 
  - To add questions: add new objects to BANK_MC, BANK_TF, or BANK_SC
    inside the JavaScript section following the same structure as existing items.
 
  - To change how many questions are drawn per section: edit the .slice(0, N)
    values in the drawQuestions() function.
 
  - To change the pass mark: edit the value 75 in the line:
    const passed = pct >= 75;
 
  - To change points per question: edit the value 5 in the line:
    const totalPoints = correct * 5;
 
  - To change the exam title or instructions: edit the HTML in the
    exam-header and instructions sections near the top of the file.
 
 
--------------------------------------------------------------------------------
INTENDED USE
--------------------------------------------------------------------------------
 
This exam is intended for use as a pre-employment technical screening tool
for Maintenance Technician candidates in a Belgian industrial environment.
It is not specific to any single company or machine brand.
 
The exam is suitable for:
 
  - HR departments conducting initial candidate screening
  - Technical leads running structured trade tests before interview
  - Candidates self-assessing their readiness for a maintenance technician role
 
The exam is not a substitute for hands-on practical assessment or formal
safety certification verification.
 
 
--------------------------------------------------------------------------------
END OF README
--------------------------------------------------------------------------------
