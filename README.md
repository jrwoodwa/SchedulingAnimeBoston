🗓 Anime Boston Scheduler Planner
Scrapes the Anime Boston 2024 schedule and optimizes event choices using linear programming.

Features:
- Extracts full event grid w/ time, room, category, color
- Filters low-utility events and early low-value ones

Solves schedule as an assignment problem via LP

----
What's needed...
- Need to write a `webscrape.py` script that captures the data processes it (including with subevents like Maid Cafe going into 45-min block options), and tidies it into a csv.
- After the csv is fully ready, manually utility score the information.
- With the data prepped, write the LP model.
- After the LP model is defined, then write the code.
- Run and observe results in an itinery.
- Make refinements to the LP model.
