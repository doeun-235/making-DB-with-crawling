# Making DB of Playlist with Web Crawling in Python

I crawled datum of musics in the given playlist, from a music streaming site 'genie.com', and exported DB as xlsx file. I used this program when preparing a truck event of our team on the Seoul Queer Culture Festival 2019.

The main code is '190503 SQCF truck setlist crawling_v.1.ipynb' and other codes were written during practices to the goal. In the main code, I used BeautifulSoup and selenium for crawling. At 'genie.com', they have a rule for making webpage names to each songs, so I used a rule for finding pages. There was some outliers cause their name on the input list were incorrect. I modified the result manually this time, but the code can be improved using search word suggestion system of Google.
