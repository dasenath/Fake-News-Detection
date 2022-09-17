# Fake-News-Detection
The dataset to be analysed pertains to news articles (GitHub, 2017). It contains news headlines, article bodies and the nature of the agreement between the headline and the article bodies (stance). The task given was to classify is the headlines and the article bodies areunrelated, agree, disagree and discuss. The word clouds presented in Figure 1 aided in identifying the extent of word similarity for the four classes.
We took inspiration for calculating the cosine similarity from Riedel et al. (2017) and implemented the pipeline presented in Figure 2 handle the task. We experimented with various feature extraction and machine learning techniques as listed in Table 1. An overall accuracy of 93.3% was obtained when the models M3 and M5 were used for the binary and three-class classifcation tasks respectively (highlighted in Table 1). The F1-scores of the pipeline are presented in Table 2.

Figure 1: Word cloud

![image](https://user-images.githubusercontent.com/105256866/190878116-c5f7f61b-56b6-4a6a-b3a5-055ce523f1ce.png)

Figure 2: Classification pipeline

![image](https://user-images.githubusercontent.com/105256866/190878134-7c1842a3-bbd6-4b38-8d8c-bb4bff2b462e.png)

Table 1: Classification models

![image](https://user-images.githubusercontent.com/105256866/190877982-b6547e30-c0e3-48eb-9682-2b5b90b3a948.png)

Table 2: Pipeline results

![image](https://user-images.githubusercontent.com/105256866/190878036-a1b87e6c-f949-4e25-910b-ea9158a40fab.png)


References
GitHub. 2017. GitHub - FakeNewsChallenge/fnc-1. [online] Available at: <https://github.com/FakeNewsChallenge/fnc-1> [Accessed 29 March 2022].
Riedel, B., Augenstein, I., Spithourakis, G.P. and Riedel, S., 2017. A simple but tough-to-beat baseline for the Fake News Challenge stance detection task. arXiv preprint arXiv:1707.03264.

