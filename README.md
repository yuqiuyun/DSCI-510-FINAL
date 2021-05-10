# DSCI510 FINAL - Artist MBTI Personality Analyzer
The zip file inclues:
1. artist_personality.py
2. MBTI_scrape.py
3. MBTI.csv
4. requirements.txt
5. Project Description.pdf
6. README.md

How to run:
1. Install everything in requirements.txt
- (pip install [paralleldots](https://github.com/ParallelDots/ParallelDots-Python-API), [lyricsgenius](https://pypi.org/project/lyricsgenius/) and [spotipy](https://spotipy.readthedocs.io/en/2.18.0/))

2. If would like to generate a new MBTI.csv databse, run MBTI_scrape.py
-  MBTI_scrape.py only contains codes that scrape data and codes that build a database

3. Run artist_personality.py
- (IMPORTANT) Please input a music artist of your choice when running this. Put the artist name in "".  For example: python artist_personality.py “Drake”
- It takes in and reads the MBTI.csv
- Print statements added to indicate progress
- Output will be the result of the personality analysis, along with a series of keywords associated with that personality type

