# Multitask model for named entity recognition(NER) and document-level event classification

Repository contains notebook that describes training process of multitask NLP model.

[NEREL dataset](https://huggingface.co/datasets/iluvvatar/NEREL) was used to train and evaluate model.

<img width="1761" height="813" alt="image" src="https://github.com/user-attachments/assets/a889e706-793b-48df-8abb-863aa95888de" />

## Notebook structure

1. EDA
2. Parsing data
3. Tokenization, data processing
4. Model creation
5. Train/eval
6. Inference pipeline

## Final metrics on test dataset

| Model version | F1 tokens (macro): | F1 cls (micro): |
| --- | --- | --- |
| Original model after train | 0.7277777777777777 | 0.9 |
| Quantized model | 0.5925925925925926 | 0.9 |

        

          
