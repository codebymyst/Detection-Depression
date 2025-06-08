# Depression Detection from Social Media Texts Using Deep Learning

## Overview  
Depression is one of the most common mental health disorders, significantly affecting individuals' quality of life. With the rise of social media, a vast amount of textual data is generated daily, containing valuable insights into users' mental and emotional states.  

This project presents a deep learning-based approach for detecting depression from social media texts—even when users do not explicitly mention their condition or may not even be aware of it themselves.  

## Goal  
The goal of this project is to develop an efficient deep learning-based method capable of detecting depression in user-generated texts, even in the absence of explicit depressive keywords. The model focuses on learning subtle and complex language patterns associated with depression without relying on direct indicators.

## Methodology  
To overcome the limitations of previous approaches that rely heavily on keywords, our model is trained on data where depression-related keywords have been removed. This allows the model to focus on indirect linguistic cues and emotional expressions.

The architecture integrates several advanced deep learning techniques:

- **BERT** for feature extraction and managing language complexities  
- **CNN** for local feature extraction  
- **BiLSTM** for understanding long-term dependencies  
- **Attention mechanism** for emphasizing emotionally relevant features

## Results  
The proposed hybrid model outperforms individual models and previous keyword-based approaches. It demonstrates high accuracy in detecting signs of depression in both keyword-rich and keyword-free datasets.  

This improvement is due to the combination of:
- **CNN's** ability to capture important local features
- **BiLSTM's** strength in modeling sequential patterns
- **Attention's** capacity to focus on the most informative parts of the text

## Related Work and Comparison  
Previous studies mainly relied on datasets labeled with depression-related keywords, limiting their ability to detect hidden signs of mental distress. Our model, trained on keyword-removed data, overcomes this by learning deeper contextual and emotional signals.  

Evaluations show that our method performs better than previous approaches, demonstrating its effectiveness on both keyword-present and keyword-absent datasets.

## Contribution  
This project offers a novel and effective approach to depression detection by:
- Removing keyword dependency  
- Utilizing BERT embeddings for linguistic feature extraction  
- Combining **CNN**, **BiLSTM**, and **Attention** for robust classification  
- Identifying **indirect signs** of depression from text with high accuracy

## Dataset  
You can access the dataset used for this project click [here](https://tsinghuaeducn-my.sharepoint.com/personal/xin_wang_tsinghua_edu_cn/_layouts/15/onedrive.aspx?id=%2Fpersonal%2Fxin%5Fwang%5Ftsinghua%5Fedu%5Fcn%2FDocuments%2FDataset%5FMDDL%2Ezip&parent=%2Fpersonal%2Fxin%5Fwang%5Ftsinghua%5Fedu%5Fcn%2FDocuments&ga=1) to download the dataset.

