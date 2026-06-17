<img width="1415" height="736" alt="Screenshot 2026-06-17 at 2 04 12 PM" src="https://github.com/user-attachments/assets/672de9a8-6a4f-419b-88e1-d13e9d47f4c3" />
<img width="1125" height="736" alt="Screenshot 2026-06-17 at 2 03 51 PM" src="https://github.com/user-attachments/assets/62c5d9a9-e012-4fc6-95c0-dffe43873c48" />
<img width="1125" height="736" alt="Screenshot 2026-06-17 at 2 03 37 PM" src="https://github.com/user-attachments/assets/a55b1d53-cb29-41a2-b7fc-2776cd59822b" />
One flag worth noting: your CSV had no per-vehicle age field, 
so the age-bucket table and the cost-vs-age line chart use a modeled wear/efficiency-drift curve anchored to your actual logged 
cost/km — that's called out in the dashboard's footer/caption rather than presented as raw CSV data. 
Everything else (KPI cards, bar/doughnut charts, E85 paradox math, score) is computed directly from your 10 rows.
