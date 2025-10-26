\# Day 5: Excel Data Cleaning



\## Objective

Learn data cleaning techniques (e.g., remove duplicates, standardize formats, handle missing values) using 2022 FIFA World Cup data, preparing it for data engineering ETL pipelines.



\## Dataset

\- \*\*2022-FIFA-World-Cup-Performance-Sample-Data.xlsx\*\*: Argentina's 2022 FIFA World Cup player performance data (user-provided). Columns: Player Name (text), Position (text), Jersey Number (number), Player DOB (date), Club (text), Appearances (number), Goals Scored (number), Assists Provided (number), Dribbles per 90 Min (number), Interceptions per 90 Min (number), Tackles per 90 Min (number), Total Duels Won per 90 Min (number).  

&nbsp; - Rows: 22 (subset to 10-15 rows for practice).  

&nbsp; - Why? Contains potential inconsistencies (e.g., missing stats) for cleaning practice, relevant to sports analytics.



\## Tasks Completed

\- Removed duplicate player entries (Data > Remove Duplicates).

\- Standardized date format for Player DOB (Home > Format > Date).

\- Filled missing values (e.g., set 0s for blank stats like Dribbles per 90 Min).

\- Saved cleaned data in `fifa-practice-day5.xlsx`.



\## Resources

\- GitHub Repo: \[rohanmistry231/Practice-Datasets-for-Excel](https://github.com/rohanmistry231/Practice-Datasets-for-Excel) (README with cleaning tips).

\- YouTube: \[ExcelIsFun Data Cleaning Playlist](https://www.youtube.com/watch?v=6k-GLrO66vQ\&list=PLrRPvpgDmw0lQ\_UC8z4w0s0g0g0g0g0g0) (watch first 15 min for basics).

\- YouTube: \[Leila Gharani Data Cleaning](https://www.youtube.com/watch?v=Xk6V2M0oQps) (first 15 min for duplicates/missing data).

\- Dataset Source: User-provided 2022 FIFA World Cup Argentina sample.



\## Next Steps

\- Day 6: Conditional Formatting (e.g., highlight top goal scorers).

\- Track progress: Commit daily via GitHub (`git add .`, `git commit -m "Day 5 complete"`, `git push`).



\## Tips for Data Engineering Transition

Data cleaning ensures data quality in ETL workflows. Practice fixing inconsistencies to prepare for real-world datasets.

