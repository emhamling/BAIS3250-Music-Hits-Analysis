# Data Folder

This folder contains the datasets used in our analysis of musical features and their relationship to Billboard chart performance.

### Included Files:

- **billboard_hot100_from_jan2025.csv**  
  → Raw Billboard Hot 100 data scraped from January 2025 onward.

- **Merged_billboard_hot_100_spotify.csv**  
  → Initial merge of Billboard Hot 100 data with Spotify audio features from the Kaggle dataset.

- **Cleaned_Merged_Billboard_Spotify.csv**  
  → Cleaned version of the merged dataset with standardized column names and de-duplicated entries.

- **Cleaned_Billboard_Spotify_Final.csv**
  → Final cleaned and formatted dataset used for exploratory analysis and modeling. Includes average values and combined identifiers.

### Notes:
- Song titles and artist names were standardized (lowercased, stripped punctuation) before merging.
- Duplicate entries and multiple observations per song were averaged.
- Combined columns (e.g., **artist_combined**) were created to improve merge accuracy across platforms.


