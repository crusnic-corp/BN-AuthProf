# BN-AuthProf
Author Profiling on Bangla Social Media Texts. 
---
Although research on author profiling has quite progressed in  abundant resources languages, it is still infancy for limited resources languages such as Bengali. This repository contains our Bangla Author Profiling Dataset (*BN-AuthProf*). The primary objective is to introduce and benchmark the performance of machine learning approaches on Age and Gender Classification tasks from the social media status of people. BN-AuthProf dataset contains 30,131 Facebook posts from 300 users from both Bangladesh and West Bengal (Kolkata, India). Each post is tagged with age and gender. Experimentation carried out using various machine learning (SVM, MNB, DT, LR, KNN), deep neural networks (LSTM, CNN, BiLSTM, CNN+BiLSTM) based approaches. Experimental outcomes indicate that MNB outdoes all other techniques for age and gender classification by achieving the highest weighted f1-score of 0.756 and 0.905 on the test data.

## How To Run The DEMO (Inferencing):
1. Open the BN_AuthProf_Age_Gender_All.ipynb script from 'code' folder and click on the Open In Colab Button.
2. Run the script from Runtime -> Run All
3. Download exp_dataset from the BN-AuthProf_Dataset folder of the repository. Or supply your own.
## BN-AuthProf Dataset 
+ We used the BN-AuthProf_Dataset - for Training/Evaluating our models.
+ You can find the exact Splitted Dataset in our Exp_Dataset from BN-AuthProf_Dataset folder.

 ## To Cite the **BN-DRISHTI** Paper:
 ```ruby
@article{tasnim2024bn,
    title={BN-AuthProf: Benchmarking Machine Learning for Bangla Author Profiling on Social Media Texts},
    author={Tasnim, Raisa and Chowdhury, Mehanaz and Rahman, Md Ataur},
    journal={arXiv preprint arXiv:2412.02058},
    year={2024}
}
```
