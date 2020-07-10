---
layout: post
title: How i made an Ai Doctor !
subtitle: A Discord bot that can detect diseases with images !
tags: [Machine Learning, Discord,Discord bot]
readtime: true
image: /assets/img/AIDOC.jpg
comments: true
---


### How it started.
So around a year back i had finished over 27 courses on machine learning back to back and was playing with some kaggle datasets, this is when i found a [Pneumonia Dataset](https://www.kaggle.com/paultimothymooney/chest-xray-pneumonia) so i downloaded the dataset over to colab notebook and made a simple model within 30 minutes to predict on chest X-rays for whether the patient is positive for pneumonia or not, this was meant for just fun so i just made a [repo](https://github.com/himanshu2406/CNN-ai-pneumonia-detection) with the notebook (Which was unuseable by someone else and not ready to be deployed at all) and forgot about it


### Reason for a useable model.
A few weeks passed and i came accross a local hackathon where the topic was **healthcare** , i was bored and wanted to bunk out of college for a day so i went to the hackathon representing my college and remodelled my pneumonia project and made it take images as input through a website and return preditction , came in a close third but it was worth it.

### Birth of the Discord bot.
Recently, i came accross Discord py , a library to make discord bots and got myself familiar with it to make some interesting bots. I realised that discord bots can do much more than play pokemon ! I was thinking of integrating some machine learning algorithm with the bot when i came across my ancient repository for the pneumonia predictor , so i ported this code for Discord py and voila the [AI-Doc](https://github.com/himanshu2406/Ai-Doctor) was born

### What's next:
1. I have decided to make this bot open source and made it so that anyone can [add it to their own server](https://discord.gg/ZUGVPSS) without worrying about hosting or installing libraries.
2. As i keep on finding more datasets , i'll keep on updating the bot to predict more stuff from pneumonia to maybe even corona ?
