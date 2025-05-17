🗓 Anime Boston Scheduler Planner
Scrapes the Anime Boston 2024 schedule using pandas/beautifulsoup and optimizes event choices using linear programming.

Features:
- Extracts full event grid with time, room, category, and color
- Filters low-utility events and early low-value ones

Solves the schedule as an assignment problem via LP

----
✅ What's done:
- ✅ Completed the web scraping in a notebook that captures the data, processes it (including subevents like Maid Cafe going into 45-min block options), and tidies it.
- ✅ Write a `webscrape.py` script for translating data engineering into a CSV (optionally: store timestamp when the script queries data).
- ✅ After the CSV is fully ready, manually utility score the information.

🔜 What's next:
- ☐ With the data prepped, write the LP model.
- ☐ After the LP model is defined, write the code.
- ☐ Run and observe results in an itinerary.
- ☐ Make refinements to the LP model.
