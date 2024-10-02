# Attention Heads Partitioning and Percentile Quantization for Efficient ECC Transformers
Submitted to NeurIPS 2025

## Install
`pip install -r requirements.txt`

## Script
Use the following command to train a 6 layers AECCT of dimension 128 on the LDPC(49,24) code:

`python main.py --code LDPC_N49_K24 --N_dec 6 --d_model 128`