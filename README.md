# FrugalGPT

## Directions
Let's implement a FrugalGPT service as defined in the paper [FrugalGPT: How to Use Large Language Models
While Reducing Cost and Improving Performance](https://arxiv.org/abs/2305.05176)

## Assumptions

### Providers
We are optimizing the following provider endpoints:
1. OpenAI
2. TextSynth

AND also our own model endpoint.

3. Preemo

For the purposes of this interview we can mock the OpenAI and TextSynth Endpoints.

### Scorer
Assume that we can use DistilBERT as the scorer.

### Datasets
For the purposes of this study we restrict ourselves to the [Overruling](https://huggingface.co/datasets/LawInformedAI/overruling) dataset