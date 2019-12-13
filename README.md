# Hong Kong (HK) Media Disinformation on Twitter - README
###### By Jefferson Huynh

###### The following directory contains a general overview of banned Twitter accounts associated with spreading HK-related disinformation in the Twitter realm. The overview is comprised of 3 sets, all released by Twitter. 



### I. Twitter Account  Description

###### Note: The CSV datasets (including set 1-3) contain a total of 5,241 unique user accounts. There are a total of 3,024 account_language set to English, 2,013 account_language set to Chinese (ZN), 90 account_language set to Chinese (TW), 46 account_language set to Russian, 20 account_language set to Spanish, 11 account_language set to Indonesian, 10 account_language set to Turkish, 9 account_language set to British English, 9 account_language set to Japanese, 6 account_language set to French, and 2 account_language set to Portuguese. In addition, there were a total of  13,847,718 tweets sent  by the 5,241 users. The year of tweet sent and account creation varied, ranging from 2007 to 2019. Some of the tweets contained pornographic links (which, unsurprisingly, garnered the most engagements) and others contained redirects to websites, and messages shared by the users. 

##### Change: However, when filtering out the data for HK protest-related messages, one particular user, "Dream News", shared a total of 14 tweets directed to the protests, which occurred for a span of one week. 



### II. Each file contains these columns:
* userid: the user's indentification number

* user_display_name: the user's heading name

* user_screen_name: the user's username

* user_profile_description: the user's description

* user_profile_url: the user's account link

* User_reported_location:: the user's reported location

* follower_count: the amount of accounts following the user

* following_count: the amount of accounts followed by the user

* account_creation_date: the user's account creation date

* account_language: the user's designated language

* tweet_language: the language of the tweet

* tweet_text: the text of the tweet

* tweet_time: the time of tweet sent by the user

* tweet_client_name: the type of Twitter program used by the user when sending out the tweet

* in_reply_to_userid: the user replying to another user with the '@' symbol

* in_reply_to_tweetid: the user replying to another user's tweet

* quoted_tweet_tweetid: the user quoting another user's tweet

* is_retweet: whether or not the user retweeted

* retweet_userid: the user retweeing another account

* retweet_tweetid: the user user retweeting another account's tweet

* latitude: current location of the tweet sent out

* longitude: current location of the tweet sent out

* quote_count: the amount of quotes garnered in a single tweet

* reply_count: the amount of replies garnered in a single tweet

* like_count: the amount of likes garnered in a single tweet

* retweet_count: the amount of retweets garnered in a single tweet

* hastags_count: the amount of hashtags included in a single tweet

* ulrs: the amount of links included in a single tweet

* user_mentions: the user's mentions

* poll_choices: the user's selection of polls

