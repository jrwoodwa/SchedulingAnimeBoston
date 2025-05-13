🗓 Anime Boston Scheduler Planner
Scrapes the Anime Boston 2024 schedule and optimizes event choices using linear programming.

Features:
- Extracts full event grid w/ time, room, category, color
- Filters low-utility events and early low-value ones

Solves schedule as an assignment problem via LP

----
✅ What's done:
- ✅ Completed the web scraping in a notebook that captures the data, processes it (including subevents like Maid Cafe going into 45-min block options), and tidies it. 

🔜 What's next:
- ☐ Need to write a `webscrape.py` script for translating data engineering into a CSV.
- ☐ After the CSV is fully ready, manually utility score the information.
- ☐ With the data prepped, write the LP model.
- ☐ After the LP model is defined, then write the code.
- ☐ Run and observe results in an itinerary.
- ☐ Make refinements to the LP model.
