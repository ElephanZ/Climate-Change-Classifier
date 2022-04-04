# Climate-Change-Classifier
_Project of Social Media Management_

_Grade of this project: 30 / 30_

_Antonio Scardace_ @ 
_Dept of Math and Computer Science, University of Catania_

## Introduction

This project consists, given a series of tweets about Climate Change, in figuring out whether the user (the author) is skeptic or supports the belief of man-made climate change. Once implemented, trained, and tested, this algorithm will be useful in some real contests.

To solve this problem, I have made an algorithm (a classifier) which has been trained on a **43943 tweets** dataset collected between 2015-04-27 and 2018-02-21 by ***Canada Foundation for Innovation JELF Grant to Chris Bauch, University of Waterloo***. <br/>
Each row of the dataset contains: the text of the tweet labelled as '*message*', the tweet id labelled as '*tweetid*', and the sentiment of the tweet labelled as '*sentiment*'.

Each sentiment is labelled as one of the following classes:
- ``-1`` (**Anti**) &#8594; the tweet author doesn't believe in man-made climate change;
- ``0`` (**Neutral**) &#8594; the tweet author neither supports nor refutes the belief of man-made climate change;
- ``1`` (**Pro**) &#8594; the tweet author supports the belief of man-made climate change;
- ``2`` (**News**) &#8594; the tweet links to factual news about climate change;

<img src="https://antonioscardace.altervista.org/smm/dataset_distr.png" alt="dataset tweets distribution" style="width: 550px; margin-top: 10px; border: 1px solid #555"/>

## Real World Application

In the real world, there are probably a lot of applications for this project, but I have been interested by one in particular: <br/>
Given the tweets of some Twitter Verified Accounts (VIP such as politicians or actors) we have to be able to understand how much these people care about climate change in their Twitter page. <br/>
I have made tests on some US Verified Twitter profiles owned by well known activists (such as **Greta Thunberg** or **Leonardo Di Caprio**). <br/>
In time, with an appropriate dataset, may be maked analytics on how many VIPs are interested (and how) on climate change for each main job category (such as politics, cinema, football).

## License

Distributed under the MIT License. See ``` LICENSE ``` for more information.
