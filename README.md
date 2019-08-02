# Tay-Tay-Text-Theatre

<img src="https://cdn2.hercampus.com/old-new-taylor-swift-5.jpg"/>

Inspired by <a href='https://youtu.be/_tjFwcmHy5M'>this</a> Ted Talk by Colin Morris titled **Pop Music is Stuck on Repeat** I was interested in whether Taylor Swifts' songs have become more repetitive over time. In the Ted talk Morris talks through <a href='https://pudding.cool/2017/05/song-repetition/'>this</a> essay where he outlines his strategy to quantify repetitiveness in songs using the Lempel-Ziv-Wilch (LZW) compression algorithm.

I've sourced all the the Taylor Swift lyrics from <a href='https://www.kaggle.com/PromptCloudHQ/taylor-swift-song-lyrics-from-all-the-albums'>this</a> Kaggle dataset and bootstrapped some of the exploratory data analysis using the <a href='https://www.kaggle.com/rahulvks/explore-the-taylor-swift-lyrics-nlp'>this</a> Kaggle kernel.

Taylor Swift has undergone some drasitic changes since her first album in 2006 and in <a href='https://github.com/louwjlabuschagne/tay-tay-text-theatre/blob/master/tay-tay-text-theatre.ipynb'>this notebook</a> we investigate three questions:
+ Has Taylor's songs become shorter over time?
+ Has Taylor's songs become happier over time?
+ Has Taylor's songs become more repetitive over time?

A medium blog summarising my findings can be found <a href='https://medium.com/@louwjlabuschagne/a-swift-look-at-taylors-music-over-the-years-da2958510461'>here</a>.


## Getting Started
You can clone the repo by running

```
git clone https://github.com/louwjlabuschagne/tay-tay-text-theatre.git
```

You might not have `textblob`, `worldcloud` or `nltk` install, you can install these packages by running

```
pip install textblob
pip install wordcloud
pip install nltk
```
