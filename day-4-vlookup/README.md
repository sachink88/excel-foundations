\# Day 4: Excel VLOOKUP and INDEX-MATCH



\## Objective

Learn VLOOKUP and INDEX-MATCH to retrieve project management data, simulating data joins for data engineering ETL processes.



\## Dataset

\- \*\*Project-Management-Sample-Data.xlsx\*\*: Project management sample data (user-provided). Columns: Project Name (text), Task Name (text), Assigned To (text), Start Date (date), Days Required (number), End Date (date), Progress (text).  

&nbsp; - Rows: 40 (subset to 10-15 rows for practice).  

&nbsp; - Why? Simple text/numerical data for lookup practice, relatable to project management experience.



\## Tasks Completed

\- Used VLOOKUP to find End Dates by Task Name (e.g., `=VLOOKUP("Market Research", B2:G41, 6, FALSE)`).

\- Applied INDEX-MATCH to retrieve Assigned To by Project Name (e.g., `=INDEX(C2:C41, MATCH("Marketing", A2:A41, 0))`).

\- Created a summary table linking Task Names to deadlines and progress.

\- Saved results in `project-practice-day4.xlsx`.



\## Resources

\- GitHub Repo: \[rohanmistry231/Practice-Datasets-for-Excel](https://github.com/rohanmistry231/Practice-Datasets-for-Excel) (README with lookup examples).

\- YouTube: \[ExcelIsFun VLOOKUP Playlist](https://www.youtube.com/watch?v=6k-GLrO66vQ\&list=PLrRPvpgDmw0lQ\_UC8z4w0s0g0g0g0g0g0) (watch first 15 min for VLOOKUP).

\- YouTube: \[Leila Gharani INDEX-MATCH](https://www.youtube.com/watch?v=Xk6V2M0oQps) (first 15 min for INDEX-MATCH).

\- Dataset Source: User-provided project management sample.



\## Next Steps

\- Day 5: Data Cleaning (e.g., standardize dates, remove duplicates).

\- Track progress: Commit daily via GitHub (`git add .`, `git commit -m "Day 4 complete"`, `git push`).



\## Tips for Data Engineering Transition

VLOOKUP/INDEX-MATCH mimic SQL JOINs in ETL workflows. Practice linking project data to prepare for data integration tasks.

