# YouTube-Video-and-Information-Crawler

1. First, one can find how to scrape YouTube videos using YouTube Data API v3 with also a "next-page" capability since there is a limit
to scrape videos for one request. 
2. Please note that in order to user YouTube Data API, first an API key need to be generated from the Google Cloud Console for free, check here: https://developers.google.com/youtube/v3/docs
3. Yet, do not forget that there is a quota limit per API key, check here: https://developers.google.com/youtube/v3/determine_quota_cost
or one can also check from the Google Cloud Console.
4. Please note that one can choose which information is necessary and then can change "part" parameter of the YouTube Data API, check here: https://developers.google.com/youtube/v3/docs/search/list, this page can also be used to conduct some experiments with the API key.
Just keep in mind that, more information means more quote needed.

***

Second this project can also be used to crawl a given YouTube video's description and subtitles (manually or automatically generated)
using a videoID.
