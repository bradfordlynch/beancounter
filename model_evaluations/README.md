# Evaluations of Continued-Pretrained Models on Financial, Toxicity and General LLM Benchmarks

## Getting continued-pretrained models
[pythia-1.4 b continued pretrained on BeanCounter](https://huggingface.co/bradfordlevy/pythia-1.4b-bc-cp) \
[phi-1.5 continued pretrained on BeanCounter](https://huggingface.co/bradfordlevy/phi-1_5-bc-cp)

In order to access the above models, you need to go to the respective links and share your contact information by clicking on "Agree and access repository". When you are running the evaluations in the notebooks, please make sure to have logged in with the huggingface-cli within the notebook. See the command below for logging in with [access tokens](https://huggingface.co/docs/hub/en/security-tokens).

```
from huggingface_hub import login
login()
```

## Expand resulting_scores.tar.zst
You can un-tar the resulting_scores directory with the following command:
```console
user:/model_evaluations$ tar -xaf resulting_scores.tar.zst
```

This directory contains all the scores produced by running evaluations within the notebooks.
