---
configs:
- config_name: default
  data_files:
  - split: train_orig
    path: "sst2_train_orig.csv"
  - split: train_orig_eda
    path: "sst2_train_orig_eda.csv"
  - split: train_orig_eda_embedding
    path: "sst2_train_orig_eda_embedding.csv"
  - split: train_orig_eda_embedding_wordnet
    path: "sst2_train_orig_eda_embedding_wordnet.csv"
  - split: val
    path: "sst2_val.csv"
---

# sst2-augmented

This dataset is the augmented version of the [SST-2](https://huggingface.co/datasets/stanfordnlp/sst2) dataset.
