# Build a Prior Authorization Workflow Simulator  
>*Learn healthcare workflows through interactive gameplay*  
>*Business Workflow Simulation with Claude*

Claude can build complete interactive simulations that teach complex business workflows through visual storytelling and gamification. This project demonstrates how AI can transform complicated healthcare processes into engaging educational experiences.

**1.Workflow Simulation:** Model real-world healthcare processes interactively.  
**2.Gamification:** Improve learning through drag-and-drop interactions and progress tracking.  
**3.Healthcare Operations:** Understand how Prior Authorization works between patients, providers, and insurers.  
**4.Interactive Development:** Generate fully functional browser applications using Claude.  

**Tasks**  
1
Read the provided resources.
2
Watch the solution video.
3
Open Claude.
4
Set Claude effort level to Low.
5
Start a new conversation.
6
Paste the provided Prior Authorization Workflow Simulator prompt.
7
Generate the complete HTML application.
8
Save the generated HTML file.
9
Open the application in your browser.
10
Start a new patient scenario.
11
Drag the patient through the workflow stages.
12
Assemble the Prior Authorization request by adding all required documents.
13
Submit the request to the payer.
14
Complete approval, pend, denial, or appeal scenarios.
15
Track progress using the journey tracker and elapsed days.
16
Review the educational explanations and workflow summary.
17
Restart the simulator with a different patient scenario.
18
Take screenshots of the completed workflow and dashboard.
19
If Claude does not complete the output or usage limits are reached, wait for the reset period and continue later.
20
Create a Day26 folder in your GitHub repository.
21
Create a day26.md file.
22
Upload screenshots, generated HTML file, and learnings.
23
Commit and push the changes.
24
Submit the GitHub commit URL.  

**Input Prompt**:  
Prior Authorization Workflow Simulator (gamified, drag-and-drop)

Build a single-file, self-contained HTML application (HTML + CSS + vanilla JavaScript, no external dependencies, no build step) that visually simulates the US healthcare Prior Authorization (PA) workflow as an interactive, gamified, drag-and-drop experience.

The simulator should include:

• Three workflow lanes: Patient, Provider, and Payer.
• Interactive drag-and-drop movement of cases between stages.
• Multiple patient scenarios (elective surgery, MRI, specialty medication, inpatient admission).
• Medical necessity evaluation.
• Prior Authorization document collection.
• Submission to payer.
• Review outcomes including Approval, Pend, Denial, Appeal, and Peer-to-Peer Review.
• Educational explanations after every step.
• Progress tracker across the top.
• Days elapsed counter.
• Efficiency score.
• Celebration animation on approval.
• Workflow summary on completion.
• Responsive modern UI using shades of blue with black text.
• Working Restart / New Patient button.
• Fully functional buttons and interactions.

Technical Requirements:
- Single HTML file.
- HTML, CSS and Vanilla JavaScript only.
- No frameworks.
- No CDNs.
- No localStorage.
- All workflow state managed in JavaScript memory.
- Well-commented code.
- Scenario data stored in an editable array near the top.
- Output only the complete HTML file without truncation.
