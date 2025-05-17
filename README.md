🗓 Anime Boston Scheduler Planner
Scrapes the Anime Boston 2024 schedule using pandas/beautifulsoup and optimizes event choices using linear programming.

Features:
- Extracts full event grid with time, room, category, and color
- Filters low-utility events and early low-value ones

Solves the schedule as an assignment problem via LP

----
✅ What's done:
- ✅ Completed the web scraping in a notebook that captures the data, processes it (including subevents like Maid Cafe going into 45-min block options), and tidies it.
- ✅ Write a `WebScrape.py` script for translating data engineering into a CSV (optionally: store timestamp when the script queries data).
- ✅ After the CSV is fully ready, manually utility score the information.
- ✅ With the data prepped, write the LP mathematical model in the notebook.

🔜 What's next:
- ☐ After the LP model is defined, write the code.
- ☐ Standardize code in `MathOptModel.py` and observe results in a displayed itinerary.
- ☐ Make refinements to the LP model based on feedback from party members.
- ☐ Circle actual schedules (+with backup events)
- ☐ Finalize actual schedules with party (+with backup events)
