# CLTS-plus-Dataset
CLTS+: A Chinese Long Text Summarization Dataset with Abstractive Summaries

## Introduction
We have proposed [CLTS](https://github.com/lxj5957/CLTS-Dataset), the ***C***hinese ***L***ong ***T***ext ***S***ummarization Dataset. However, CLTS is an extractive dataset: extractive summaries frequently borrow words and phrases from their source text, which leads to the fact that models trained on CLTS will extract whole sentences from articles to form summaries when predicting. 

In order to solve this problem, we propse another two version datasets called **Pre-CLTS+** and **CLTS+** respectively. The ground-truth in **Pre-CLTS+** is the reference summaries in CLTS after paraphrasing. As for **CLTS+**, it is based on Pre-CLTS+ and we replace words in the summaries with their synonym using a Thesaurus without changing the meaning of the sentence. In CLTS+, there are no article-summary pairs that the reference summary is completely extracted from the source article.

## Samples
We select some samples from CLTS+ and you can see them in [samples.txt](https://github.com/lxj5957/CLTS-plus-Dataset/blob/main/samples.txt)

## Download
[Pre-CLTS+](https://pan.baidu.com/s/1FHCaYaVULWSj7dNqC14s1A) and [CLTS+](https://pan.baidu.com/s/10cwtrvyLXMiq2hvKD_Z-uw) are all available from the link. If you want to get the password, please feel free to contact with us by: liuxiaojun@iie.ac.cn.
