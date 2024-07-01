# JKR Follower Accumulation vs Google Trends Interest in "JK Rowling"
This is a demonstration of the "cursor trick" that was usable with the Twitter V1 API prior to the meltdown of Twitter's APIs. 
It shows how JK Rowling's follower accumulation accelerates with Google Trends spikes in interest for the search term "JK Rowling"

The data file `jkr_timestamps_vs_follower_gain.pkl` contains the timestamps and the total number of followers Rowling accumulated since June 15, 2018. 
Additionally, the Python script `qt_jorts_effect.py` demonstrates how this "cursor trick" works. It exploits a trick first noted [here](https://popzazzle.blogspot.com/2019/11/how-to-find-out-when-someone-followed-you-on-twitter.html) wherein the cursor Twitter uses to let API users page through long following lists is also a Unix timestamp that marks the timestamp at which the last follow in the payload occurred. 
