HAZGUARD Prototype
​Relational Process Hazard Analysis Suite
​This is a production-ready prototype designed to replace static spreadsheets with a dynamic, relational PHA environment. It follows the industrial documentation standards of Gharda Chemicals and the navigation logic of high-end safety software.
​🚀 Key Features
​Standard Header: A high-density engineering header featuring relational equipment matrices and site metadata.
​Relational Node & Unit Registry: Define your plant sections (Nodes) and specific equipment (Units) once. They are "fetched" into the worksheet header automatically.
​Automated Deviation Builder: A 5-column selector system (Guideword, Parameter, Flow, From, To) that synthesizes professional safety strings to eliminate typos and standardise language.
​Master Logic Editor: Full authority to edit the "Logic Bank" (dictionaries) and the 5x5 Risk Criteria (Severity/Probability labels).
​Dynamic Recommendation Tracker: Automatically extracts actions from the worksheet into a centralized ledger with full traceability paths (Node > Deviation > Cause).
​Zero-Jitter Engine: A selective-rendering architecture that allows smooth text editing without losing cursor focus or screen flickering.
​🛠️ How to Use
​Initialization: Start a "New Project" from the Welcome screen to define the Facilitator and Study Title.
​Setup:
​Go to Study Setup > Nodes Registry to define your process sections.
​Go to Study Setup > Unit Manager to link specific equipment (Tags, MOC) to those nodes.
​(Optional) Customize the Risk Criteria labels.
​Analysis:
​In the PHA Worksheet, select a Node from the header.
​Use the Automated Builder dropdowns to create your Deviation.
​Input your technical analysis (Causes, Consequences, Safeguards).
​Follow-up:
​View the Action Tracker to see all proposing recommendations fetched from the worksheet.
​Export: Use the Download A3 button to generate a regulatory-ready PDF report.
​📋 Technical Notes
​Architecture: Single-file Vanilla JS / Tailwind CSS (no external dependencies required).
​Storage: Persistent data management using localStorage (Study Vault).
​Print Logic: CSS-calibrated for A3 Landscape engineering formats.
​Prototype developed by Anurag Yamnurwar.
