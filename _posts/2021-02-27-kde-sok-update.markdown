---
layout: post
title: "SOK Update 1"
date: 2021-02-22 18:56:33 +0530
category: sok-blog
---

# Season Of KDE 1

Hello!!! Last month I started working on "Automating Social Media data collection" as my Season of KDE project, I wanted to share my progress so far. The following work has been done:

A data format has been establised and [this](https://github.com/rohanreddych/rohanreddych.github.io/tree/master/notes/sok-data) is the format of data that is collected every week.

- Twitter data

1. Public metrics like retweets, likes, replies and private metrics like engagement and clicks. 
2. Get all mentions of any twitter account. Since most of the data on twitter is public, I am designing my application in such a way that it can be used for retreiving data from multiple accounts. 
3. Searching for keywords across tweets, so that we can analyse what people are talking about kde products.

- Instagram and Facebook

1. To get data from Instagram and Facebook need analyst or admin access. So we cannot swap account name to get data about other accounts. 

- Linkedin

1. Linkedin also requires analyst role or above to get the data. 

- Mastodon

1. Public data

- Reddit

1. Get stats for different subreddits. 
2. Search for words across different subreddits.
3. Stats for all posts by contributors.
4. Other than subreddit traffic (which is available for moderators) most data is public so we can get most of the data.

- Linux package stats

1. Getting popularity of different kde apps and packages using popcons data provided by different distros. 

- Youtube

1. Channel data (subscribers, stc)
2. Content data (views, comments, likes, ...)


- Basic analytics

1. Sentiment analysis. For the comments so we can visualise positive/negative feedback to a post. 


#### TODO

Currently working on "Text classification using machine learning and natural language processing" for better understanding of which type of posts are doing well on social media. 

