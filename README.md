# Analysis on Human Personality and League of Legends Factors (KAIST CS564 '20 Fall Class Project)

## Data Collection & Preprocessing With Python

- Data Collection/Preprocessing Code: `collect_rank_match.py`, `preprocess.py`, `prepare-analysis.py`
- Datasets: `responses.csv`, `all_tiers.csv`, `all_matches.csv`
- Collect League of legends player statistics collection via Riot API.
- Preprocess lane and role information to generate five lane information.

*Mainly written by Jiseong Yang and Taeckyung Lee*

## Clustering Champion Data

- Collect League of legends 152 different champions data in JSON Format via Riot API and transform it into a data frame.(Code: `lolchampions.py`)
- Clustering champions with Hierarchical Clustering: `Main_Analysis.R`.

*Mainly written by Giyoung Byun and Soohwan Lim*

## Survey Data Preprocessing & R analysis

- Preprocessing code: `prepare_analysis.py`
- Datasets: `Roll_Data.csv`
- Combine collected log data with survey results

- R analysis code: `Main_Analysis.R` 
- R analysis of MBTI and LoL, based on clustering results and preprocessed data

*Mainly written by Seojin Kim and Soohwan Lim*
