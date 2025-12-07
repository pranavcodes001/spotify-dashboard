< > Spotify Top 50 – Power BI Dashboard

This project explores Spotify’s global Top-50 dataset using Power BI.
The dashboard highlights trends in song popularity, artist consistency, track characteristics, and explicit content across the daily charts.
It also includes custom DAX measures for deeper analytical context.

> Overview
The dashboard focuses on:
Popularity distribution across songs and artists
Duration analysis (min / max / averages)
Explicit vs non-explicit track patterns
Track and album characteristics
Artist and song recurrence
Daily movement trends using a Date table
Release-year based insights and song age
Optional moving-average trends for popularity
The goal is to demonstrate analytical capability using real-world music streaming data.

> Key DAX Logic (Summary)
The model includes calculated measures for:
General Metrics
Total songs in the dataset
Distinct songs and distinct artists
Avg, max, and min popularity
Average track duration (converted from ms → minutes)
Explicit Content Analysis
Explicit vs non-explicit track counts
Percentage of explicit tracks
Popularity comparison between explicit and clean tracks
Position & Ranking
Average chart position
Count of songs that hit position #1
Count of artists reaching #1
Entries within the Top 10
Album & Track Info
Average number of tracks per album
Album type distribution (single vs album)
Artist/Song Behavior
How many times each song appears in the charts
How consistently an artist appears
Avg popularity per artist
Distinct songs per artist
Time-Series / Trend
Using a proper Date table:
Change in song count vs previous day
Change in popularity vs previous day
7-day moving average for popularity
Release Year Insights
Average, newest, and oldest release year
Avg age of songs (in years)

> What You’ll See in the Dashboard

Popularity trend visuals
Artist frequency charts
Explicit vs clean song comparisons
Track duration distributions
Album type split
Ranking insights (Top 10, #1 positions)
Time-based shifts in daily charts
Release-year heatmaps and song-age visuals
The report is organized into clear pages for overview, artist analysis, track-level metrics, and time-series movement.

> Files
Spotify_Top50_Dashboard.pbix
Download the PBIX and open it in Power BI Desktop.

> Tools & Techniques
Power BI Desktop
Data modeling (relationships + Date table)
DAX measures for statistical and trend analysis
Iterators (AVERAGEX, MAXX, MINX)
Time intelligence functions (DATEADD)
CLEAN handling of boolean/text fields using FORMAT + LOWER

> Purpose
This project demonstrates:
Ability to design structured analytical dashboards
Writing optimized DAX for deeper insights
Applying trend analysis, ranking logic, and time intelligence
Turning a raw dataset into clear visual storytelling

> Author

Pranav Thakur
For feedback or collaboration, feel free to connect.
