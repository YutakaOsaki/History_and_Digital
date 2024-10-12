# DH-412: Exploring Semantic Shifts of Benevolence in Confucianism with NLP Techniques

## Abstract
This study investigates the semantic evolution of the concept of benevolence (仁, Ren) in Confucian philosophy, focusing on its transformations from the Pre-Qin period through the Western Han and Eastern Han dynasties (480 BCE - 192 CE). Utilizing data from the Chinese Text Project, we compiled a dataset of 26 significant Confucian texts, comprising 697 chapters, with 346 specifically discussing benevolence. Our project integrates quantitative distant reading methods from computational linguistics to study semantic changes and qualitative close reading methods to explore the relationship between language and discourse. By employing natural language processing (NLP) techniques, including word embedding, self-similarity analysis, and topic modeling, we traced the shifts in both the denotation and connotation of benevolence. Our findings reveal that while the core meaning of benevolence remained stable, notable variations occurred due to socio-political changes, particularly during the Western Han Dynasty when Confucianism was institutionalized. These results underscore the adaptability of Confucian thought and its enduring relevance through significant historical transitions.

## Codes Contents
* `data` folder: contains all Confucianism data that extracted [Chinese Text Project](https://ctext.org/)
* `01_preproccesing.ipynb`: making tidy datasets and doing word segmentation
* `02_cooccurence.ipynb`: Conducting co-occurrence analysis
* `03_bertopic.ipynb`: Performing topic modeling using BERTopic
* `04_selfsimilarity.ipynb`: Implementing Self-Similarity and relevance between benevolence and keywords
