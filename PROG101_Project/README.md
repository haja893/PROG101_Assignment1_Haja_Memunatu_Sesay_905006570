# Community Water Supply Monitoring and Reporting System

**Course:** PROG101 — Principles of Programming Logic and Design  
**Assignment:** Designing Logical Solutions for Sierra Leone Community Challenges  
**Institution:** Limkokwing University, Sierra Leone  
**Student:** Haja Memunatu Sesay
**Student ID:** 905006570
**Class:** BBIT1101
**Lecturer:** Mr. James Kanga

## Project overview
This academic project proposes a **logical design**, not a working application, to record, prioritize and track complaints about damaged public taps, faulty pumps and interrupted community water supplies in Sierra Leone.

## Objectives
- Collect and validate complaint information.
- Assign High, Medium or Low priority from integer severity 3, 2 or 1.
- Generate a report ID such as `WSR0001`.
- Retrieve the status of a complaint by ID.
- Allow authorized staff to update status.
- Summarize Pending, In Progress and Resolved reports.

## Menu and modules
The menu provides Submit Complaint, Check Complaint Status, Update Complaint Status, Generate Complaint Summary, and Exit. Seven principal modules are `MainMenu`, `SubmitComplaint`, `ValidateInput`, `AssignPriority`, `CheckStatus`, `UpdateStatus`, and `GenerateSummary`. `AuthenticateUser` is a supporting function.

## Repository structure
```text
Algorithms/Algorithm_Design.txt
Pseudocode/Water_Supply_Pseudocode.txt
Flowcharts/PROG101_Water_Supply_Flowcharts.drawio
Flowcharts/01_main_menu.png ... 07_summary.png
Testing/Logical_Test_Scenarios.md
Report/  (final approved report to be added)
README.md
```

## How to review
1. Read the step-by-step algorithm in `Algorithms/`.
2. Read the language-independent pseudocode in `Pseudocode/`.
3. Open the `.drawio` file in [diagrams.net](https://app.diagrams.net/) to inspect and edit the seven diagrams. PNG exports are also included.
4. Review illustrative inputs and expected outputs in `Testing/`.

## Example
For a first valid complaint about a broken public tap in Wellington with severity 3, the expected result is report ID `WSR0001`, priority `High`, status `Pending`.

## Programming logic
The design demonstrates sequence, selection (`IF`, `ELSE IF`), repetition (`REPEAT UNTIL`, `FOR EACH`), Boolean validation, variables, data types, functions, and modular decomposition.

## SDG 6, openness and Digital Public Goods
The proposed design supports **SDG 6: Clean Water and Sanitation** by improving how water infrastructure problems could be reported and monitored. It does not itself supply water. Future open-source development could allow reuse and community contributions. This design is **not** a certified Digital Public Good. A future implementation would need an appropriate license, privacy safeguards and other relevant standards. Personal complaint information must not be published in this repository.

## Scope and limitations
This is a **design-only** assignment: there is no runnable program, deployed service or executed software test. Authentication and password verification are conceptual; complaints and counters are modeled in memory. A production implementation would require secure authentication, persistent records and durable unique IDs.

## Version control
Commit each meaningful change to the GitHub repository. Repository screenshots and commit-history screenshots should be captured from the actual GitHub account and inserted into the final report.

## Report status
The final report is being restructured and will be added to `Report/` after approval.


## Current submission status

The seven flowcharts and logical tests are prepared. The final assignment report and genuine GitHub repository/commit screenshots are **pending**. See `GitHub_Evidence/EVIDENCE_TEMPLATE.md`. This is a logical-design project, not an executable application.
