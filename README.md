# novel-chapter-dataset
Novel Chapter Dataset

This repository contains data files related to the paper
Exploring Content Selection in Summarization of Novel Chapters. Faisal Ladhak, Bryan Li, Yaser Al-Onaizan, and Kathleen McKeown. ACL 2020 (short).

1) Summaries\
Unfortunately we do not have the rights to distribute the data. In order for others to replicate our dataset, we provide three .txt files, where each line represent a book/chapter pair, of the format:
```
<book title>.<chapter(s)>
```

Some sample lines from val.txt are shown below:
```
Adventures of Huckleberry Finn.Chapter 32-35
Adventures of Huckleberry Finn.Chapter 32
Adventures of Huckleberry Finn.Chapter 33
Adventures of Huckleberry Finn.Chapter 34
Adventures of Huckleberry Finn.Chapter 35
```

In this case, one of the study guide sources does not have summaries for each of the individual chapters, but instead has a single aggregated summary of the three chapters. In cases such as this, we combine the individual chapter summaries from the other sources to created aggregated summaries, so that we have multiple references. Note that the val.txt file also contains the individual chapter summary instances from the other sources.



In order to reproduce the dataset accurately, we recommend that you use the archived version of the online study guides from https://archive.org, with the following timestamp:
```
20191015
```


2) Books\
We will provide a zipped file contained the original book text from Project Gutenberg, as the license is in the public domain. We have spent a good amount of effort manually cleaning up the text, and standardizing chapter titles and headings, so we hope this will be useful to the community.

This will be added to the repository before ACL in July 2020.
