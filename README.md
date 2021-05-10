# DSCI510 FINAL - Artist MBTI Personality Analyzer
The zip file inclues:
1. artist_personality.py
2. MBTI_scrape.py
3. graph_analysis.py
4. MBTI.csv
5. requirements.txt
6. Project Description.pdf
7. README.md

How to run:
1. Install everything in requirements.txt
- pip install [paralleldots](https://github.com/ParallelDots/ParallelDots-Python-API), [lyricsgenius](https://pypi.org/project/lyricsgenius/) and [spotipy](https://spotipy.readthedocs.io/en/2.18.0/)

2. If would like to generate a new MBTI.csv databse, run MBTI_scrape.py
-  MBTI_scrape.py only contains codes that scrape data and codes that build a database

3. Run artist_personality.py
- **(IMPORTANT)** **Please input a music artist of your choice when running this. Put the artist name in quotes.**  **For example**: python artist_personality.py “Drake”
- It takes in and reads the MBTI.csv
- Print statements added to indicate progress
- Output will be the result of the personality analysis, along with a series of keywords associated with that personality type

4. If would like to see how WordCloud generates graphs, run graph_analysis.py
- This step DOES NOT affect the result of the main artist_personality.py file. It is a separate step solely for the project description requirement of this assignment.
- Need to pip install [wordcloud](https://amueller.github.io/word_cloud/) and [matplotlib](https://matplotlib.org/stable/users/index.html) for this. It is not included in the requirements.txt since this is an optional step of this project.
