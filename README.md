# BN-AuthProf
Author Profiling on Bangla Social Media Texts. 
---
**BN-AuthProf** : Bangla Author Profiling Dataset

Although research on author profiling has quite progressed in  abundant resources languages, it is still infancy for limited resources languages such as Bengali. This paper focuses on author profiling in the Bangla language, aiming to extract valuable insights about anonymous authors based on their writing style on social media. The primary objective is to introduce and benchmark the performance of machine learning approaches on a newly created Bangla Author Profiling dataset, BN-AuthProf. The dataset comprises 30,131 social media posts from 300 authors, labeled by their age and gender. Experimentation carried out using various machine learning (SVM, MNB, DT, LR, KNN), deep neural networks (LSTM, CNN, BiLSTM, CNN+BiLSTM) based approaches. Experimental outcomes indicate that MNB outdoes all other techniques for age and gender classification by achieving the highest weighted f1-score of 0.756 and 0.905 on the test data.
## How To Run The DEMO (Inferencing on Single Image):
1. Open the BN_AuthProf_Age_Gender_All.ipynb script from 'code' folder and click on the Open In Colab Button.
2. Run the script from Runtime -> Run All
3. Download exp_dataset from the BN-AuthProf_Dataset folder of the repository. Or supply your own.
## BN-AuthProf Dataset 
+ We used the BN-AuthProf_Dataset - for Training/Evaluating our models.
+ You can find the exact Splitted Dataset in our Exp_Dataset from BN-AuthProf_Dataset folder.
