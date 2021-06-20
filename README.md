## About the Project:

Problem : Anomaly Detection and Anomaly Scoring

-[Data](https://github.com/uakarsh/anomaly_detection/blob/main/anomaly_file.csv)


- Anomaly Detection Colab Notebook : [Notebook](https://github.com/uakarsh/anomaly_detection/blob/main/Anomaly_Detection.ipynb)
- Anomaly Scoring Colab Notebook : [Notebook](https://github.com/uakarsh/anomaly_detection/blob/main/Anomaly%20Scoring.ipynb)


## Preprocessing:

- The proprocessing part, is loading the data, exploring the data, and then performing some statistical analysis with them, and then train the model, apply cross-validation technqiue,creating new features and obtain the results.

## Models used:

- The model used are:
1. LSTMs
2. Random Forest
3. KNN
4. XGBoost
5. Logistic Regression

## Statistical Techniques used:

1. Inter Quartile Range
2. Z-Scores


## Approach for ML Models:
1. Used Random Search CV
2. Trained on some permutations of the column
3. Created new features, and trained again

## Approach for Statistical Techniques:

- In this method, I used Z-Score to find the outliers. And then found out that each of the anomalies can be figured out with the help of this technique, so I went forward with this technique.
-  Now, my approach was suppose if I take the max value until the given timestamp T, and do some shifting scaling type of process, of all the data, and then compare it with the maximum deviation until now maybe that could be a potential candidate.


## Results

![alt text](https://github.com/uakarsh/anomaly_detection/blob/main/Screenshot%202021-06-20%20232250.jpg)


## Areas of Improvement:

I think that more experimentation can be done, with the help of feature extractors like LSTM, which can be replaced with the Normalization technique, and possibly more combinations can be made to improve the results.

### 📺 Some of my projects:

<!-- YOUTUBE:START -->
- [Medical Visual Question Answering (Current Repository)](https://github.com/uakarsh/med-vqa)
- [Customer Segmentation (Unsupervised Learning)](https://github.com/uakarsh/customer-segmentation)
- [Brain MRI Segmentation (Classification and Segmentation)](https://github.com/uakarsh/brain-segmentation)
- [Image Classification (Cancer detection)](https://github.com/uakarsh/CNN-for-Beginners)
- [Movie Recomendation using Cosine Similarity](https://github.com/uakarsh/Movie-Recommendation-Engine)
<!-- YOUTUBE:END -->


<details>
  <summary>:zap: GitHub Stats</summary>

 [![Anurag's github stats](https://github-readme-stats.vercel.app/api?username=uakarsh)](https://github.com/anuraghazra/github-readme-stats)


</details>

[website]: https://uakarsh.github.io/AkarshU
[twitter]: https://twitter.com/akarsh1_u
[youtube]: https://www.youtube.com/channel/UCvHy0oE1PUkGFjK_pWCajmQ
[instagram]: https://www.instagram.com/toforaeka/?hl=en
[linkedin]: https://www.linkedin.com/in/akarsh-upadhyay-50ba7518b/
[kaggle]: https://www.kaggle.com/akarshu121
