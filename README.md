# Sinhala Lyrics Corpus
A corpus for Sinhala songs lyrics prepared for CS4642 Data Mining & Information Retrieval module. This corpus contains lyrics for 1094 songs. Corpus is created only for educational purposes.

### Attributes
1. `url`: url of the lyric. Can be use as a unique key field
2. `songName`: name of the song
3. `artist`: list containing artists
4. `genre`: list containing genres
5. `lyricWriter`: list containing lyric writers
6. `musicDirector`: list containing music directors
7. `key`: key of the song
8. `beat`: beat of the song
9. `views`: no of views for the song in original site
10. `shares`: no of shares for the song in original site
11. `lyric`: lyric (each line seperated by a `\n` character)

> Some of the above fields may empty in the json file due to different html formats in the website.

### Note
Data is scraped from the https://sinhalasongbook.com/ site for educational purposes.
