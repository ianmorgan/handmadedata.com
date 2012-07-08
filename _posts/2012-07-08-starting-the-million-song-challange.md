---
layout: post
tags:   million_song_challange, pig
---
After an excellent presentation on [Pig](http://pig.apache.org/) that used the 
[Million Song Dataset Challange](http://www.kaggle.com/c/msdchallenge/) on Kaggle as an worked example, 
I'm inspired to explore this problem a little more. It seems like a good way to understand more about the 
algorithms and technologies of Data Science. 

The prize is just kudos and the data provided by [Columbia University](http://labrosa.ee.columbia.edu/millionsong/) 
for educational purposes. That means a few generous individuals have put some example solutions up on blogs
already.

I'm using the following to start with:
  
1.  A talk by [Andrew Clegg](https://github.com/andrewclegg/pig-data-mining-talk) on Pig at the London 
Hadoop User Group. This has a very basic algorithm running on Pig/Hadoop with some notes on how it may be 
improved. A downside is that it takes already takes 10 minutes to run just the training data (about 10% 
of the full dataset). As Andrew mentions, this is probably not the most efficient solution for this problem, 
in which the dataset will just about fit into main memory. Python would run a lot quicker.

2.  A blog by [Martin O'Leary](http://mewo2.com/kaggle/2012/04/27/the-million-song-dataset-challenge-part-i/) 
with a basic solution in Python.

3. The [Example Solution](https://kaggle2.blob.core.windows.net/competitions/kaggle/2799/media/MSDChallengeGettingstarted.pdf) 
provided by Kaggle. This in Python. 

It looks like I'm going to need to brush up on my Python. I've managed to get Andrew Clegg's Pig example 
running, which now I understand the install process is vey simple except for one missing library. I'll try and find time 
to write up my notes on that tomorrow, but after that I'm going pick one of the two Python examples 
(I'm leaning to the one by Martin O'Leary).



 

   
