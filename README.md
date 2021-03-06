# Climate-Change-Classifier
_Project of Social Media Management (Machine Learning applied on Social Media)_

_Grade of this project: 30 / 30_

_Antonio Scardace_ @ 
_Dept of Math and Computer Science, University of Catania_

## Introduction

This project consists, given a series of tweets about Climate Change, in figuring out whether the user (the author) is skeptic or supports the belief of man-made climate change.

To solve this problem, I have made an algorithm (a classifier) which has been trained on a **43943 tweets** dataset collected between 2015-04-27 and 2018-02-21 by ***Canada Foundation for Innovation JELF Grant to Chris Bauch, University of Waterloo***.

Each row of the dataset contains: the text of the tweet labelled as '*message*', the tweet id labelled as '*tweetid*', and the sentiment of the tweet labelled as '*sentiment*'.

Each sentiment is labelled as one of the following classes:
- ``-1`` (**Anti**) &#8594; the tweet author doesn't believe in man-made climate change;
- ``0`` (**Neutral**) &#8594; the tweet author neither supports nor refutes the belief of man-made climate change;
- ``1`` (**Pro**) &#8594; the tweet author supports the belief of man-made climate change;
- ``2`` (**News**) &#8594; the tweet links to factual news about climate change;

<img src="https://antonioscardace.altervista.org/smm/dataset_distr.png" alt="dataset tweets distribution" style="width: 550px; margin-top: 10px; border: 1px solid #555"/>

## Real World Application

I've made tests on two US profiles owned by well-known activists - **Greta Thunberg** and **Leonardo Di Caprio**. <br/>
In time, with an appropriate dataset, may be made analytics on how many VIPs are interested (and how) in climate change for each main job category (such as politics, cinema, and football).

## Getting Started

So that the repository is successfully cloned and project run smoothly, a few steps need to be followed.

### Requisites

* At least 10 cores of CPU.
* I recommend to downloading, installing, and using [Conda](https://docs.conda.io/projects/conda/en/latest/user-guide/install/index.html#) that has  [Jupyter Notebook](https://jupyter.org/install) included.
* The use of [Visual Studio Code](https://code.visualstudio.com/download) is recommended.

## License

Distributed under the MIT License. See ``` LICENSE ``` for more information.
