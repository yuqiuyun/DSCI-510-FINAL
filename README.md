# DSCI-510-FINAL
I intend to create an application that can analyze a YouTube music playlist, and eventually fetch MBTI personality types for that specific playlist.

The code I submitted is intend to fetch lyrics for songs using Genius API.
It might not run properly without the API permission.
The code still needs to be polished so there still might be problems.



My intended project plan; it is subject to change based on how well I will manage the YouTube API

Project Summary: Analyze personality types based on one’s liked videos on YouTube.

Project Goal: Use YouTube API to access liked music videos and incorporate Genius.com API to get lyrics for the liked songs on YouTube. Then I will scrape the MBTI website, especially keywords associated with each personality type to create a program that potentially analyzes people’s MBTI type based on the lyrics. 

Dataset 1: YouTube Data API 
Link for Reference: https://developers.google.com/youtube/v3/docs/videos/list 

Description: This API would allow me to incorporate functions executed on YouTube into my own program.

Usage: I intend to take usage of this free API to access information about a video playlist. Specifically I will be using the liked videos to access my liked videos.
 
Dataset 2: Genius.com API
Link for Reference: https://docs.genius.com/#songs-h2 

Description: Genius.com provides a large database of song lyrics. Its API allow us to fetch data/metadata regarding song/artists. 

Usage: I will intend to automate Genius lyrics with the “liked videos” list obtained from YouTube. I am planning to use this API with the help of Beautiful Soup to get song lyrics and write them to text files (will be stored locally). The text will later be parsed and compared to MBTI keywords. Potential step to fetch data would be: get artist names + song titles  get a list of URLs  fetch lyrics from URLs  loop through all URLs and write them into one file.

Dataset 3: MBTI 16 personalities website
Link for Reference: https://www.mbtionline.com/en-US/MBTI-Types/ESFJ 

Description: MBTI is a personality test/outline that categorize personalities into 16 different types. Each type has distinct features, and their official website lists out keywords that best describes each type. 

Usage: I intend to scrape the keywords associated with each personality type, and compare them to words presented in lyrics text files. I intend observe the match and create a program that would output the most matched personality type with the song lyrics (count how many times certain keywords show up in lyrics, and find the one with max# of matches). 



