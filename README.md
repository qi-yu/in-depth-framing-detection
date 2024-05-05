# Framing Detection: Synergizing NLP Techniques and Theoretical Linguistic Insights

## 1. About 

This repository contains all data and code for Yu (2024, to appear), dissertation, University of Konstanz.

**A short summary:**

Earlier NLP studies on automated framing detection focus primarily on the detection of framing induced by topic coverage (what we dub as *topical framing*). 
This often oversimplifies the complex phenomenon of framing as a mere matter of topic coverage, leading to superficial modelling.

We argue that the automated detection of framing should not only focus on topical framing, 
but also framing arising from topic-agnostic linguistic features that rhetorically manipulate the way how a frame in communication should be integrated into the hearers’ frames in thought (we refer to such framing effect as *rhetorical framing*). 
We empirically verify the argued importance of the rhetorical framing features with a large-scale study on framing strategies employed by three
nationwide daily newspapers in Germany (BILD, FAZ, and SZ) in their reports on the European Refugee Crisis from 2014 to 2018.

## 2. Content of the Repository

| Folder                   | Description                                                                                                                                                                                                                                                                                                 |
|--------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| ```experiment_1_overall_discursive_packaging```               |   An initial exploration of the overall discursive packaging in the three newspapers utilizing both topical and rhetorical framing features.                                                                    |
| ```experiment_2_framing_from_presuppositions```   | An investigation of framing effects evoked by presuppositions triggered by the iterative adverb *again*. The fine-tuned BERT model resulting from this experiment is to be found on [Huggingface](https://huggingface.co/qi-yu/bert-german-news/blob/main/README.md).                                                                                                                                                                                                          |
| ```experiment_3_framing_from_modal_particles```             | An examination of framing effects of modal particles used in causal discourse relation.    |


## 3. Acknowledgement
This dissertation is funded by the Deutsche Forschungsgemeinschaft (DFG – German Research Foundation) under Germany‘s Excellence Strategy – EXC-2035/1 – 390681379.
