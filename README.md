# Predictive Modeling with Temporal Graphical Representation on Electronic Health Records

This is a temporary repository for the implementation of IJCAI2024 submission 2228

## Requirements

Requirements and recommended versions:

Python (3.10.13)

pytorch (1.12.1)

torch-geometric (2.3.1)

Pyhealth (1.1.4)

wandb (optional

## Data Processing

For MIMIC-III and MIMIC-IV: refer to https://pyhealth.readthedocs.io/en/latest/api/datasets.html; 

For CCAE: Run process_ccae.ipynb in the data folder.


## Training & Evaluation

To train the model and baselines in the paper, run this command:

```
python train.py --model <TRANS/Transformer/...> --dataset <mimic3/mimic4/...>
```
