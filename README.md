# Social Media Sentiment Analysis

## Overview:
A sentimental analysis conducted on the most sentimental person, one of my favourite guitarists Brian May from Queen [brianmayforreal Instagram](https://www.instagram.com/brianmayforreal/?hl=en)

## Data Source
1. Twitter: You can apply for API at [Twitter For Developer](https://developer.twitter.com/en/docs)
2. Instagram no longer provides public API. I used the automatic scraper developed by [APIFY](https://apify.com/) instead.
The dataset I used in this project are 8000 instagram posts dated from 2017-09-10 to 2019-10-06. 

## First Try:
>Because Twitter would automatically repost his Instagram posts，Twitter has public API, and IG doesn't

>First I decided to just analyze on his Twitter posts to avoid the complication of dealing with mannually scrapying from Instagram.
>However, after I got the data from Twitter's API [Twitter API data](DrBrianMay_tweets%20from%20twitter%20API.csv), I realized twitter don't always repost the complete text. Many long posts are replaced by a hyperlink redirecting readers to original posts, which caused error in my analysis results.

>So I had to go with the original posts on Instagram. [APIFY data](brianins.csv)

## Analysis
### Posts length 
> Posts Length in characters
> Posts Length in words
> Posts Length in sentences
> Posts Length in characters

### On which day did he post the most?

### Screaming posts with a max of 28 exclamation marks (wow
> <img src="images/screaming%20posts.png" width="60%">

> He's obviously so excited about an astrophysics conference last summer that he used 28 exclamation marks in the post. Not surprised.

### Most Common Words 
> <img src="images/Most%20Common%20Words.png" width="60%">

> "Thanks" is the most common word. Gratitude is the attitude!

### Emotion distribution
> <img src="images/positive_negative.png" width="50%"/> <img src="images/emotion%20Distribution.png" width="50%"/>

### Which Emotions are most liked by followers?
> <p float="left">
  <img src="images/emotion%20and%20likecount%20corr.png" width="50%"/> 
  <img src="images/emotion%20and%20likecount%20correlation.png" width="50%">
  </p>

> Followers like it most when he is joyful, hopeful and positive. 
> Social media, I'm so glad to see "there are still faint glimmers of civilization left in this barbaric slaughterhouse that was once known as humanity."

### Word cloud
> <img src="images/wordcloud.png" width="60%">

### Comparison Word Cloud
> <img src="images/comparison%20word%20cloud.png" width="60%">




#### Important disclaimer: 
This is an analysis done on one person's data, and all the data I used are publicly accessible. 

If there is an issue of privacy for anyone because of the result, please let me know. 

PS. No animals were harmed during the analysis. 




