#Yahoo Screen Video-Mouse Activity Dataset (ICMR 2016)

This repository contains the Yahoo Screen video-mouse activity dataset used in our ICMR 2016 paper **"Mouse Activity as an Indicator of Interestingness in Video"** 

## Introduction
This dataset includes 496 videos from Yahoo Screen and their user mouse activity logs. The dataset was used for evaluating our technique presented in ICMR 2016.

## The Data
`yahoo_screen_videos_icmr2016.tsv`is a tab-separated values (TSV) format file, containing information about the 496 videos: video_id, video_title, and video_url. 

Note that some lines have only video_id, with no title and url information. This is because those videos have unfortunately been removed from Yahoo websites. Please contact us for questions regarding those videos.

The directory `mouse_aggregated` contains 496 text files, each file is named as `<video_id>.txt` and contains the aggregated mouse features we derived from raw user mouse activity logs (Equation 1 in our ICMR 2016 paper), one line per second. 


## Reference
Gloria Zen, Paloma de Juan, Yale Song, Alejandro Jaimes. **"Mouse Activity as an Indicator of Interestingness in Video."** In Proceedings of the 2016 ACM on International Conference on Multimedia Retrieval (ICMR 2016), New York, New York, USA, June 6-9, 2016 
