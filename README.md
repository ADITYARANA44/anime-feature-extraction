# Anime Dataset Feature Extraction

Extracting structured features from a messy anime ranking dataset using Python and Pandas.

## Problem
In the raw dataset, the Title column mixes several details into one string: the title, type, episode count and airing dates. This project pulls those details out into clean columns so the data can be analysed.

## Dataset
`anime.csv` contains 50 top-ranked anime titles with their Rank, Title and Score. The file is included in this repository.

## What I did
- Wrote a custom Python function to extract the episode count from each title
- Used Pandas `apply()` to create a new Episodes column
- Cleaned the extracted values and converted them to integers
- Extracted the airing period into a Time_Stamp column
- Answered questions using filtering and `nlargest()`: the highest-scoring anime, the anime with the most episodes, and the top 5 by episode count

## Tools Used
Python, Pandas, NumPy, Jupyter Notebook

## Files
- `08_FeatureExtraction.ipynb`: the analysis notebook
- `anime.csv`: the dataset

## Key Findings
- Highest-scoring anime: Fullmetal Alchemist: Brotherhood (score 9.10)
- Longest-running anime in the dataset: Gintama (201 episodes)

## Author
Aditya Singh Rana
[LinkedIn](https://www.linkedin.com/in/aditya-singh-rana-95897a352) | [GitHub](https://github.com/ADITYARANA44)
