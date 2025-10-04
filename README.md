# BMIET-VibeCoding-TeamTwins
Python CLI Expense Tracker for BMIET Vibe Coding — Team Twins.

PERSONAL EXPENSE TRACKER — TEAM TWINS (UT7O16X7)

A small command-line Personal Expense Tracker written in Python 3 (standard library only).
You can add, view, update, delete expense records and save them to a CSV file. 
It also generates export files:
- expense_report.txt (human-readable report)
- expense_summary.csv (per-category totals)
- expense_backup.json (JSON backup)

Robust input validation ensures the program never crashes on normal mistakes.

------------------------------------------------------------
HOW TO RUN
------------------------------------------------------------
1. Extract the ZIP file anywhere on your computer.
2. Open a terminal or command prompt in the extracted folder (where app.py is located).
3. Run:
   Windows: python app.py
   macOS / Linux: python3 app.py

------------------------------------------------------------
MENU OPTIONS
------------------------------------------------------------
Type 1 → Add Expense
Type 2 → View Expenses
Type 3 → Expense Summary
Type 4 → Update Expense
Type 5 → Delete Expense
Type 6 → Export Report
Type 7 → Help / Files
Type 8 → Exit

Tips:
- Type q to cancel an action at many prompts.
- Invalid input is handled gracefully — no crashes.
- After exporting, check files: expense_report.txt, expense_summary.csv, expense_backup.json.

------------------------------------------------------------
FILES OVERVIEW
------------------------------------------------------------
app.py               Main CLI program (run this)
expenses.csv         Primary data file (auto-created) — header: date,amount,category,note
expense_report.txt   Human-readable exported report
expense_summary.csv  Per-category totals (generated)
expense_backup.json  JSON backup (generated)
README.md            This file

Data details:
- Date stored as YYYY-MM-DD HH:MM:SS
- Amount stored with two decimals (e.g. 199.50)
- Category is a short string (Food, Travel, etc.)
- Note is optional short text

------------------------------------------------------------
ABOUT THE PROJECT
------------------------------------------------------------
Built by Team Twins — Spoorti A. Menasagi & Keerti A. Menasagi 
for BMIET Vibe Coding — Python Track (Beginner).

- Standard library only (no external packages)
- Handles invalid input gracefully
- Reads/writes CSV and generates export files
- Fully compatible with lab machines

AI Assistance: Some code structuring and refinement suggestions were obtained from ChatGPT. 
All final code, testing and adaptation by the team.

------------------------------------------------------------
QUICK DEMO FLOW (FOR JUDGES)
------------------------------------------------------------
1. Launch app — menu appears.
2. Add 2–3 expenses.
3. Show View + Summary.
4. Export Report — open the generated files.
5. Update / Delete an expense to show error-free handling.
