#Yahoo Screen Video-Mouse Activity Dataset (ICMR 2016)

This repository contains the video-mouse activity dataset used in our ICMR 2016 paper **"Mouse Activity as an Indicator of Interestingness in Video"** 

## Introduction
This dataset includes 497 videos from Yahoo Screen and their user mouse activity logs. The dataset was used for evaluating our technique presented in ICMR 2016.

## The Data
`yahoo_screen_videos_icmr2016_all.tsv` is a tab-separated values (TSV) format file, containing information about the 497 videos. Each line contains each video's video_id, video_title, video_duration, and video_url.

`yahoo_screen_videos_icmr2016_exp.tsv` is a subset of the entire dataset. It contains information about the 45 videos used in our experiments. 

Note that some lines do not have video_url (indicated as `__unavailable__`). This is because those videos have unfortunately been removed from Yahoo websites. Please contact us for questions regarding those videos.

The directory `mouse_aggregated` contains 497 text files. Each file is named as `<video_id>.txt` and contains the aggregated mouse features we derived from raw user mouse activity logs (Equation 1 in our ICMR 2016 paper). There is one line per second.

The directory `interestingness_score` contains 45 text files. Each file is named as `<video_id>.txt` and contains the interestingness scores we obtained using crowdsourcing. There is one line per second. See the paper for more details about our crowdsourcing experiment.

## Reference
Gloria Zen, Paloma de Juan, Yale Song, Alejandro Jaimes. **"Mouse Activity as an Indicator of Interestingness in Video."** In Proceedings of the 2016 ACM on International Conference on Multimedia Retrieval (ICMR 2016), New York, New York, USA, June 6-9, 2016 
