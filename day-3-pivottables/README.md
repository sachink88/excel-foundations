\# Day 3: Excel PivotTables and Visualization



\## Objective

Learn PivotTables, slicers, and charts to analyze Tokyo Olympics medal data, simulating dashboard creation for data engineering reporting.



\## Dataset

\- \*\*Tokyo-Olympics-Medal-Data.xlsx\*\*: Tokyo 2020 medal table (user-provided sample). Columns: Team (text), Gold (number), Silver (number), Bronze (number), Total Medals (number), Ranking (number).  

&nbsp; - Rows: ~90 (subset to 20 rows for practice).  

&nbsp; - Why? Simple tabular data for PivotTable aggregation and visualization.



\## Tasks Completed

\- Created PivotTable for total medals by ranking (Insert > PivotTable > Fields: Ranking to Rows, Total Medals to Values).

\- Added slicers for Gold/Silver/Bronze (PivotTable Analyze > Insert Slicer > Gold/Silver/Bronze fields).

\- Built bar chart for top 10 teams by total medals (PivotChart > Bar > Filter top 10).

\- Saved results in `olympics-practice-day3.xlsx`.



\## Resources

\- GitHub Repo: \[Excel PivotTables Guide](https://github.com/rohanmistry231/Practice-Datasets-for-Excel) (README with Pivot examples).

\- YouTube: \[ExcelIsFun PivotTables Playlist](https://www.youtube.com/watch?v=6k-GLrO66vQ\&list=PLrRPvpgDmw0ngx3x6xogD0zRYhVJf3SgH) (watch first 15 min for basics).

\- YouTube: \[Leila Gharani PivotTables](https://www.youtube.com/watch?v=Xk6V2M0oQps) (first 15 min for slicers/charts).

\- Dataset Source: Official Tokyo Olympics medal table (e.g., \[Microsoft Sample](https://download.microsoft.com/download/d/1/c/d1cbcef0-d00d-4854-adaf-ee7a9bd60a11/olympics.xlsx)).



\## Next Steps

\- Day 4: VLOOKUP/INDEX-MATCH for data lookup (e.g., team rankings).

\- Track progress: Commit daily via GitHub (`git add .`, `git commit -m "Day 3 complete"`, `git push`).



\## Tips for Data Engineering Transition

PivotTables mimic SQL GROUP BY/aggregation in ETL tools like Spark. Use for quick data exploration before pipeline coding.

