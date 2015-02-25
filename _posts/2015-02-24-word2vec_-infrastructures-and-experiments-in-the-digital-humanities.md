---
layout: post
title: "Word2Vec: infrastructures and experiments in the digital humanities"
published: false
created:  02/24/15 21:44:36
tags: [machine learning, digital humanities, infrastructure]
---

Armand Marie Leroi's 'Digitizing the Humanities' opinion piece in [_The New York Times_][(http://www.nytimes.com/2015/02/14/opinion/digitizing-the-humanities.html?_r=0) suggests that we be seeing the emergence of 'one republic of learning' based around the transformation of humanities into sciences. The 'promise' is based on an 'inexorable logic' of digitization, numbers and statistics. By analogy with biology where, Leroi suggests, 'where major tenets are couched in math and generally agreed,' a _pax scientia_ based an evolutionary theory of culture should allow a humanities renaissance. 

Leroi might be right about the growth of digital humanities, but there are some things that can't pass by unremarked. He refers to 'deep learning algorithms becoming very good at extracting meaning from data' and 'the rise of a mathematical theory of culture ... built by biologists, economists and physicists and being published in the unforgiving terms and journals that such scientists read'. These two developments are linked. The theory of culture being built by biologists, economists, physicists and, we might add, computer scientists in various guises (for instance, the recapitulation of Adolphe Quetelet's 'social physics' of the 1840s in Alex Sandy Pentland's social physics) does seem to be gathering pace. But it relies on communication infrastructures, media platforms, databases and especially analytic techniques are not, by and large, in the hands of scientsts in the way that the Large Hadron Collider or an Illumina HiSeq 2000 are. 

Are the algorithms or even the software the same as the experimental or field equipment used by scientists? Yes and no. As often, the software offers a lead here. Topic model software has played a major role in the last five years of the digital humanities. On the one hand, the software libraries for topic modelling are readily available. [`gensim`1(http://radimrehurek.com/gensim/index.html) has been widely used, although [`MALLET`](http://mallet.cs.umass.edu/) is probably favoured in the digital humanities. Or we might look at even more recent algorithms such as the Google-developed [`word2vec`](http://code.google.com/p/word2vec/), which, unlike most algorithms currently used in digital humanities, is actually a 'deep learning' algorithm. 
