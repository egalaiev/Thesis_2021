# Thesis 2021: Hate speech detection from tweets
@author: egalaiev

The recent growth of social media (Twitter, Facebook, Youtube, etc.) created many different ways in which we can virtually communicate with the rest of the world. However, social media has also become a convenient medium to disseminate hate speech. Hate Speech (HS) spread through social media has fueled riots in many different parts of the world (e.g., recent genocide in Myanmar). Thus, detecting hate speech, and therefore possibly limiting it, has become crucial in the fight against misogyny and xenophobia. It is no longer possible to manually control the web because of the huge amount of data online. Therefore, creating automated systems that recognize hate speech has become a necessity today. 

Various models have been constructed in this repository, all of which are intended to detect Hate Speech from tweets.
Models included in this repository:
- Polarity & Subjectivity baseline (Data_Visualization.ipynb)
- Dictionary-based model (Baseline_Dictionary.ipynb)
- Bag-of-Words (Model_BOW.ipynb)
- N-Grams (Model_N-Grams.ipynb)
- Word embeddings such as Word2Vec & Doc2Vec (Model_Word2Vec.ipynb)
- DeepMoji (deepmoji/Model_Deepmoji.ipynb)
- BERT (Model_BERT.ipynb)
- RoBERTa (Model_roBERTa.ipynb)

Important note: SemEval 2019 Task 5, named HatEval, which encourages participants to recognize hate speech in tweets, particularly against women and immigrants, was the starting point of this work.
