# Twitter-Crypto-Sentiment-Scarping-$NEAR
## Install
* pip install chromedriver-binary-auto
## Introduction
Scraping real-time sentiment data from Twitter on target Crypto/NFT Token based on popularity. 
* Current parameters includes : 

Article_text | Replies | Retweets | Love
| :--- | ---: | :---: | :---:

* Data Selection Barriers:
   * min_replies >= 28
   * min_faves=99
   * min_retweets>=111

* query 
    * `query` is target Token what you wanna scrape like: `%24NEAR` stands for `$NEAR`; `%23CRYPTO` stands for `#CRYPTO`

* max_posts 
    * `max_posts` is basically, numbers of posts you want scrape. Scraping 8 posts takes 1 to 2 seconds.


![alt text](https://github.com/ZaizhiSheng/Twitter-Crypto-Scraper/blob/main/word_cloud.png?raw=true)

## Usage
* Open terminal 
  * run `python main.py`

* Data Scale
  * `max_posts =` set the number of data for scarping
