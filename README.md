# Amazon Prime Video Content Analysis

An interactive Power BI dashboard exploring the Amazon Prime Video catalogue.

![Dashboard](dashboard.png)

## Key questions
- How big is the catalogue, and how much of it is movies vs TV shows?
- Which genres and age ratings dominate?
- How has the number of titles released changed over time?

## Highlights
- 9,668 unique titles: 7,814 movies (80.8%) and 1,854 TV shows
- Drama is the top genre, followed by Comedy and Action
- Titles released per year have grown sharply since 2015

## Tools
Power BI (DAX measures, Power Query cleaning), Excel/CSV

## Data cleaning
- Removed 17 corrupted rows caused by line breaks in descriptions
- Merged split "Arts, Entertainment & Culture" genre values
- Counted distinct titles, since each title appears once per genre

## Files
- `Prime_Video_Dashboard.pbix`: the Power BI report
- `Title_Data`: the dataset
- `dashboard.png`: dashboard screenshot

## Author
Your Thiyag | [LinkedIn](www.linkedin.com/in/thiyagarajanms)
