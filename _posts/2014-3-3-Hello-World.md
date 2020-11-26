---
layout: post
title: Russian Vocab Project
---

The number of words and phrases in a given language is overwhelming; it is impressive that a non-native speaker can become fluent in a foreign language at all.

Conventional wisdom tells us that a learner only reaches such a level of mastery through years of immersion -- living, speaking and breathing the language every day -- that allow them to internalise not only the sheer multitude of words, but also the mass of idioms, collocations and subtle meanings that collectively give them an “intuitive” knowledge of that language (the word “intuitive” implying that this knowledge is difficult to objectively or logically ascertain).

Taking a look at this enormous learning task -- the absorption of thousands of words and phrases in a foreign language -- I thought that there must be a way for students to learn more quickly, more comprehensively, and with more enjoyment in the daily learning exercise. There must be a way to systematise this convoluted process, break the task down into its constituent parts, and build a tool that can perform much better as a learning aid. Since any small improvements in the efficiency of the learning process would scale up thousands of times, I knew that investing time to optimise the system would pay dividends in days and weeks of saved studying time.

So I set about learning Python, and I wrote a program intended to serve as this optimal tool, automating as much of the learning process as possible, and saving students valuable time!

Learn in descending order of frequency:
- The first and simplest strategy to optimise study time is to focus on high-frequency words.
Commonly, language learners are taught to write down and learn the words and phrases that they personally encounter when they read or listen to content in their target language.
The issue with this approach is two-fold:
First, manually copying down words soaks up studying time which could be better spent actually learning new material.
Secondly, learning words in random order doesn’t take advantage of the huge law of diminishing returns when it comes to the frequency of words -- to the extent that learning a few high-frequency words can be just as useful as learning hundreds of low-frequency ones, sheerly because the former are far more likely to appear in speech and writing.

Start with a frequency list
The simple solution to this is to learn in descending frequency order according to a frequency list of the whole language. These lists are calculated based on a huge corpus (body of texts) in the language. In my case, I used the one from the Russian National Corpus. Similar lists can be found online for any major language.
Start with a corpus
However, a frequency list alone doesn’t give us enough data to make more detailed insights about word and phrase frequency. So instead, for my project I also needed a huge parallel corpus (a database of translated sentence pairs) that can be queried to find more granular data on individual word meanings and collocations (whose necessity will become clear further down this article).
