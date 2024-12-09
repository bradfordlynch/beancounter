# Toxicity & Demographic Analysis

## Datasets of extracted descriptor sentences
[🤗 Dataset of Descriptor Sentences](https://huggingface.co/datasets/bradfordlevy/BeanCounter-Descriptor-Sents)
We decided to make a dataset of sentences containing demographic descriptor (extracted from BeanCounter and C4-en) public on Huggingface for further research and replication purposes. This HuggingFace dataset include all sentences with specified demographic descriptors outlined in the paper. 

The supporting_datasets directory should already contain the batched extracted descriptor sentences, which can be directly used for Perspective analysis.

To download the HuggingFace dataset of descriptor sentences, you can run the following commands. You can change the last command to pull specific desired splits of the data.
```console
user:/supporting_datasets$ GIT_LFS_SKIP_SMUDGE=1 git clone https://huggingface.co/datasets/bradfordlevy/BeanCounter-Descriptor-Sents
user:/supporting_datasets$ cd BeanCounter-Descriptor-Sents
user:/supporting_datasets$ !git lfs pull --include "c4-en/*"
```
Analysis from jupyter notebooks assume that all relevant datasets are in the supporting_datasets directory. 

