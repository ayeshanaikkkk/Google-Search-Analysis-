# Google-Search-Analysis-
A Python-based Google Trends analyzer using pytrends and matplotlib to track, analyze, and visualize the global search popularity of "Cloud Computing." Extracts peak search timelines, generates geographic interest bar charts, and fetches related keyword suggestions directly from Google Search data.

* **`date`**: The start date of the tracked week.
* **`Cloud Computing`**: The Google Trends Interest Index (scaled 0–100).
* **`isPartial`**: Confirms whether the data for that week is finalized (`False`) or still incomplete (`True`).
<img width="444" height="301" alt="image" src="https://github.com/user-attachments/assets/b911ea0f-47c0-4d0d-92b0-91689a594c94" />

Early 2024 Daily Peaks Snapshot
* **Daily Resolution:** Unlike the 12-month overview which aggregates data by week, this shorter timeframe output isolates individual dates to find exact single-day spikes.
* **Peak Volume:** Displays `2024-01-29` as the highest search interest day within the specified window with a maximum value of `100`.
<img width="390" height="290" alt="image" src="https://github.com/user-attachments/assets/1ebfd0f0-c84e-414b-b7b2-7c0bc2853302" />

Top 10 Regions by Search Interest
* **`geoName`**: The country or territory.
* **`Cloud Computing`**: The regional search interest index (scaled 0–100), showing where the topic is proportionally most popular.
<img width="316" height="277" alt="image" src="https://github.com/user-attachments/assets/9b26d52a-93bc-4bd7-906a-fb1040bcf8c1" />

Visualizing Global Search Interest
* **Visualization Style:** Utilizes the clean, modern `fivethirtyeight` plotting theme.
* **X-Axis Clipping:** Highlights a known formatting edge-case where vertical country labels are clipped at the bottom by default (e.g., "pia", "ena", "pal").
<img width="1026" height="537" alt="image" src="https://github.com/user-attachments/assets/9b67be72-78d0-4f68-9918-ad48ade1895f" />
