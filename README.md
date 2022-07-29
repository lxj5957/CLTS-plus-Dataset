# CLTS-plus-Dataset
CLTS+: A Chinese Long Text Summarization Dataset with Abstractive Summaries

## Introduction
We have proposed [CLTS](https://github.com/lxj5957/CLTS-Dataset), the ***C***hinese ***L***ong ***T***ext ***S***ummarization Dataset. However, CLTS is an extractive dataset: extractive summaries frequently borrow words and phrases from their source text, which leads to the fact that models trained on CLTS will extract whole sentences from articles to form summaries when predicting. 

In order to solve this problem, we propose **CLTS+** dataset. The ground-truth in **CLTS+** is the reference summaries in CLTS after paraphrasing. Meanwhile, some inconsistencies will inevitably occur during the process of paraphrasing; for example, people and place names in summaries after paraphrasing can’t be aligned with those in CLTS reference summaries. Therefore, we correct errors of factual inconsistencies to reduce the noise in the dataset and improve the prediction accuracy of models.

This work has been accepted by [ICANN2022](https://e-nns.org/icann2022/), we will update the paper link as soon as they published it.

## Samples
We select some samples from CLTS+ and you can see them in [samples.txt](https://github.com/lxj5957/CLTS-plus-Dataset/blob/main/samples.txt)

## Download
[CLTS+](https://pan.baidu.com/s/1FHCaYaVULWSj7dNqC14s1A) is available from the link. And the pass word is ***7yvn***.
