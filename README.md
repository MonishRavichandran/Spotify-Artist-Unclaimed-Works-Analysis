🎧 Spotify Artist Unclaimed Works Analysis — Taylor Swift
📖 Project Overview

This project was developed as part of my Data Analyst Internship at Tritone.
It analyzes the unclaimed musical work right shares by cross-referencing them with Taylor Swift’s catalog from Spotify, helping identify tracks with potential unclaimed ISRCs (International Standard Recording Codes).

The project demonstrates practical skills in data collection, cleaning, analysis, and automation using Python and the Spotify API.

🚀 Objectives

Extract Taylor Swift’s full album and track catalog from the Spotify API.

Retrieve metadata such as album name, track title, release date, and ISRC codes.

Compare the extracted data with unclaimed musical work right share records.

Identify overlapping ISRCs and export results to an Excel report.

🧠 Key Learnings

Handling API rate limits and pagination efficiently.

Working with large datasets using pandas.

Integrating data from multiple sources (Spotify API + TSV dataset).

Automating Excel report generation with multiple sheets.

🛠️ Technologies Used

Python 3.10+

Spotify API via spotipy

Pandas for data manipulation

ExcelWriter for exporting analysis results

📂 Project Structure
│
├── unclaimedmusicalworkrightshares.tsv    # Input dataset
├── intern_project.ipynb                   # Main Python jupyter notebook script
├── artist_unclaimed_analysis.xlsx         # Output report
├── README.md                              # Project documentation

