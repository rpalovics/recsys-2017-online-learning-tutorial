<p align="center">
  <img src="./figs/online reco.png" alt="alpenglow"/>
</p>

# RecSys 2017 Hands-on Online Ranking Tutorial

Traditional recommender algorithms may periodically rebuild their models, but they cannot adjust to quick changes in trends caused by timely information.
In contrast, online learning models can adopt to temporal effects, hence they may overcome the effect of concept drift in non-stationary online environments.

In our tutorial, we present open source systems capable of updating their models on the fly after each event: Apache Spark, Apache Flink and [Alpenglow](https://github.com/rpalovics/Alpenglow), a C++ based Python recommender framework.
Participants of the tutorial will be able to experiment with all the three systems by using Zeppelin Notebooks.
Our final objective is to compare and then blend batch and online methods to build models providing high quality top-k recommendation in non-stationary environments. 

## Theoretical background

A brief summary of the tutorial's theoretical background is now [available](https://github.com/rpalovics/recsys-2017-online-learning-tutorial/raw/master/docs/summary.pdf).
Participants should check out the summary before attending to the tutorial, as during the event there will be less emphasis on the theoretical background.

A preview of the introductory slides are now [available](https://github.com/rpalovics/recsys-2017-online-learning-tutorial/raw/master/docs/intro.pdf).