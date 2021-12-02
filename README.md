# dataincubator_capstone

Method
Procedure

Two hundred North American (100 Americans and 100 Canadians) and 200 East Asian (100 Japanese and 100 South Koreans) users were randomly selected from the Twitter wall. To verify the authenticity of each cultural group member, we used Twitter’s advanced search function (https:\\twitter.com/search-advanced) to filter the language each user used and the place the users were located. For example, we selected Korean samples that used Korean and were tweeted in Korea only. From this search, we collected 100 user names for each region (Korea, Japan, U.S., and Canada). In total, there were 418,690 North American tweets and 424,561 East Asian tweets.
To collect tweets from these users, we used the application programming interface (API) Twitter offers. All the tweets are saved on the Twitter server, and API is the channel to communicate with that server. To have access to the Twitter server, we created an ID for this research and received an authentication from Twitter. We used a Python library called ‘tweepy’ for authentication and data collection, and coded additional scripts for the emoticon search using Python. 
After collecting tweets from our subjects, we searched for unicode based emoji, provided on phone, as well as text-based emoticons. Unicode emojis are pictographs (pictorial symbols) that are typically presented in a colorful form and used online in text, such as 😀. Text-based emoticons were emoticons made with the combination of letters, as in :). We did not have specific hypothesis about cultural differences stemming from using different modes of emoticons (i.e., unicode vs. text-based). We then counted the number of emoji/emoticons from each tweet and then categorized each emoticon by valence: positive (smiling and laughing faces), surprise, neutral (faces in thought, unemotional faces), and negative (faces expressing anger, sadness, disgust, contempt, and fear). This dataset provided information only on user's’ tweeted language, location of users, and emoticons used by these users. Other information, such as participants’ gender, could not be obtained due to the limited access. The only available information from user information was the language used from tweets and location of users.

Results 
Overview
The analyses were designed to address cultural differences and similarities in emoticon use across two regions (U.S., Canada; Japan, Korea). The first question of interest is whether any differences emerge in the frequency of emoticon use in Twitter. 

[Total Emoticons] We first performed a chi-square analysis to examine the relation between culture and presence of emoticons in tweets. There was a significant association between the culture and whether or not emoticons were present in tweets [χ2(1, N=843251)=2268,  p < .001]. East Asians were more likely to have emoticons in their tweets (43.1 %) than North Americans (38%). We also performed a Welch t test for cultural difference, because the equal variance assumptions did not hold. The results showed a main effect of participant culture for the total number of emoticons (t (1, 802793.164) = -35.054, p <.001, 95% CI [-.080, -.072]. East Asians used more emoticons (M = .569, S.E.= .002) than European Americans did (M = .492, S.E.= .002). This hypothesis still held when we performed a linear mixed model with our subjects’ user identification as a correlated random factor [ F (1, 413.55) = 5.53, p = .019, 95% CI [-.15, -.01]].  

[Text-based Emoticons] East Asians used more text-based emoticons than North Americans did [ F (1, 413.98) = 26.62, p <.001, 95% CI [-.249, -.111]]. This was the case for positive, negative, and neutral emoticons. The full range of text-based emoticons used can be seen in Table 2. This cultural difference was more pronounced in the use of positive emoticons [ F (1, 413.17) = 26.77, p < .001, 95% CI [-.103, -.046]] than in the use of neutral emoticons [ F (1, 419.53) = 8.76, p = .003, 95% CI [-.006, -.001]], or negative emoticons [ F (1, 415.30) = 10.24, p = .001, 95% CI [-.016, -.039]]. There was no difference between culture in using emoticons for surprise [ F (1, 478.817) = .010, p = .919].

[Unicode-based Emoji] North Americans used more unicode-based emoji than East Asians did [ F(1, 420.49) = 44 , p <.001, 95% CI [.115, .211]. North Americans used more positive, neutral, and negative emoji. 

Discussion
Results from Study 1 support our hypothesis that East Asians use more emoticons than North Americans do, showing that  context of use matters when considering expression of emotion. The online environment may ease constraint on expressing emotion that has been observed in face-to-face East Asian communicative contexts. Similar to being alone in the laboratory without the experimenter as in the Ekman & Friesen research, East Asians might be free of pressure to control their expression of emotion when they tweet.

