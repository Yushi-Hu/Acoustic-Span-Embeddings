# Multilingual Acoustic Word Embeddings

## papers and codes

#### [Multilingual Jointly Trained Acoustic and Written Word Embeddings, Interspeech 2020](https://arxiv.org/pdf/2006.14007.pdf)
Yushi Hu, Shane Settle, Karen Livescu

[code](https://github.com/Yushi-Hu/Multilingual-AWE)

Abstract: Acoustic word embeddings (AWEs) are vector representations of spoken word segments. AWEs can be learned jointly with embeddings of character sequences, to generate phonetically meaningful embeddings of written words, or acoustically grounded word embeddings (AGWEs). Such embeddings have been used to improve speech retrieval, recognition, and spoken term discovery. In this work, we extend this idea to multiple low-resource languages. We jointly train an AWE model and an AGWE model, using phonetically transcribed data from multiple languages. The pre-trained models can then be used for unseen zero-resource languages, or fine-tuned on data from low-resource languages. We also investigate distinctive features, as an alternative to phone labels, to better share cross-lingual information. We test our models on word discrimination tasks for twelve languages. When trained on eleven languages and tested on the remaining unseen language, our model outperforms traditional unsupervised approaches like dynamic time warping. After fine-tuning the pre-trained models on one hour or even ten minutes of data from a new language, performance is typically much better than training on only the target-language data. We also find that phonetic supervision improves performance over character sequences, and that distinctive feature supervision is helpful in handling unseen phones in the target language.

#### [Acoustic Span Embeddings for Multilingual Query-by-example Search, SLT 2021](https://arxiv.org/abs/2011.11807)
Yushi Hu, Shane Settle, Karen Livescu

[code of acoustic span embeddings training](https://github.com/Yushi-Hu/Acoustic-Span-Embeddings/)

[code of QbE search](https://github.com/Yushi-Hu/Query-by-Example/)

Abstract: Query-by-example (QbE) speech search is the task of matching spoken queries to utterances within a search collection. In low- or zero-resource settings, QbE search is often addressed with approaches based on dynamic time warping (DTW). Recent work has found that methods based on acoustic word embeddings (AWEs) can improve both performance and search speed. However, prior work on AWE-based QbE has primarily focused on English data and with single-word queries. In this work, we generalize AWE training to spans of words, producing acoustic span embeddings (ASE), and explore the application of ASE to QbE with arbitrary-length queries in multiple unseen languages. We consider the commonly used setting where we have access to labeled data in other languages (in our case, several low-resource languages) distinct from the unseen test languages. We evaluate our approach on the QUESST 2015 QbE tasks, finding that multilingual ASE-based search is much faster than DTW-based search and outperforms the best previously published results on this task


## Visualization

#### Acoustic Word Embeddings and Acoustically Grounded Word Embeddings for 12 languages

[tensorflow projector visualization](http://projector.tensorflow.org/?config=https://raw.githubusercontent.com/Yushi-Hu/Multilingual-AWE/master/emb-examples/awe-agwe-config.json)

#### Acoustic Span Embeddings

## Data

Trained models are in the code links for each paper

#### Download embeddings

#### data-preprocessing
