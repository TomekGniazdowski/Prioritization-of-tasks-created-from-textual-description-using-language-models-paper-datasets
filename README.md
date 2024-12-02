# Prioritization-of-tasks-created-from-textual-description-using-language-models-paper-datasets
_Prioritization of tasks created from textual description using language models_ [[paper]()].

Marek Bazan, Tomasz Gniazdowski, Maciej Marchwiany

April 2024; _JT Weston_, Warsaw; _Wrocław University of Science and Technology_, Wrocław

## Info
The repository contains anonimized "Real Dataset" and translated "Enron Dataset" used as part of the research carried out for the article. __Datasets are available only for reaserch purposes.__

## Dataset masks
To use the data, you need to replace the masks with random, various values. Used masks are:
- [COMMAND] (programming command),
- [COMPANY NAME],
- [DATE],
- [DAY],
- [E-MAIL ADRESS],
- [FOLDER PATH],
- [GEOGRAPHIC NAME],
- [HOUR],
- [ID] (a string of letters and numbers),
- [LINK],
- [PERSON NAME],
- [TIME],
- [VALUE] (numerical value, most often refers to an amount of money).

In case of any question do not hesitate to ask 😄 via emails: marek.bazan@pwr.edu.pl & tomasz.gniazdowski@jtweston.pl.
## Citation
@article{BAZAN20243303,
title = {Prioritization of tasks created from textual description using language models},
journal = {Procedia Computer Science},
volume = {246},
pages = {3303-3312},
year = {2024},
note = {28th International Conference on Knowledge Based and Intelligent information and Engineering Systems (KES 2024)},
issn = {1877-0509},
doi = {https://doi.org/10.1016/j.procs.2024.09.309},
url = {https://www.sciencedirect.com/science/article/pii/S1877050924023305},
author = {Marek Bazan and Tomasz Gniazdowski and Maciej E. Marchwiany},
keywords = {task priority estimation, XLM-RoBERTa, BERT, email messages annotations, regression task in NLP, Polish NLP},
abstract = {In this article, we introduce a novel method to improve the quality of priority prediction on small datasets. Our approach combines data augmentation with automatic annotation using an open dataset (like Enron). We investigated various annotation methodologies, including Best-Worst scaling (BWS), Pair-wise annotation, and annotation using pairs created by comparing models. The new method increases precision by more than 10% with respect to the best baseline and reduces Mean Squared Error by about 40%. Additionally, we worked on texts in the Polish language (both native, real data or translated to Polish), enabling the benchmarking of two language models: XLM-RoBERTa and HerBERT for Polish. Through numerical experiments, we demonstrate the effectiveness of our method, showcasing its potential for real-world applications. Additionally, our results serve as a compelling example of transfer learning for contrastive learning.}
}
