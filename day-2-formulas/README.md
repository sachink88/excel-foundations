# Day 2: Excel Basic Formulas

## Objective
Learn basic Excel formulas (SUM, AVERAGE, COUNT, MAX, MIN) to analyze call center sentiment data, preparing for data engineering ETL aggregation tasks.

## Dataset
- **Call-Center-Sentiment-Sample-Data.xlsx**: Call center sentiment data (user-provided sample). Columns: ID, Customer Name, Sentiment, CSAT Score, Call Timestamp, Reason, City, State, Channel, Response Time, Call Duration (Minutes), Call Center.  
  - Rows: 64 (subset to 10-15 rows for practice).  
  - Why? Simple numerical data (CSAT Score, Call Duration) for practicing formulas, relevant to telecom call center operations.

## Tasks Completed
- Calculated total call duration using SUM.
- Computed average CSAT score by call center using AVERAGE.
- Counted calls by channel (Chatbot, Call-Center, etc.) using COUNT.
- Identified highest/lowest CSAT scores with MAX/MIN.
- Saved results in `call-center-practice-day2.xlsx`.

## Resources
- GitHub Repo: [rohanmistry231/Practice-Datasets-for-Excel](https://github.com/rohanmistry231/Practice-Datasets-for-Excel) (README with Excel tips).
- YouTube: [ExcelIsFun Formulas Playlist](https://www.youtube.com/watch?v=6k-GLrO66vQ&list=PLrRPvpgDmw0ngx3x6xogD0zRYhVJf3SgH) (watch first 10 min for SUM/AVERAGE).
- YouTube: [Leila Gharani Excel Formulas](https://www.youtube.com/watch?v=Xk6V2M0oQps) (first 10 min for basic formulas).
- Microsoft Learn: [Excel Formulas Basics](https://support.microsoft.com/en-us/office/overview-of-formulas-in-excel-ecfdc708-9162-49e8-b993-c311f47ca173).

## Next Steps
- Day 3: Conditional Formatting (e.g., highlight negative sentiment calls).
- Track progress: Commit daily via GitHub (`git add .`, `git commit -m "Day 2 complete"`, `git push`).

## Tips for Data Engineering Transition
Use formulas to prototype data aggregation (e.g., summarizing CSAT scores), a key ETL step. Practice with simple data to build pipeline skills.