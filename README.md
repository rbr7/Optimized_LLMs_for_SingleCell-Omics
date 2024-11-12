# Foundational models for single-cell multi-omics using low-rank gradient approximation techniques
 

## Project Overview

This project focuses on developing a memory-efficient Large Language Model (LLM) architecture for analyzing single-cell multi-omics (sc-omics) data. sc-omics provides deep insights into cellular processes, but the high-dimensionality and complexity of the data pose significant computational challenges. Traditional LLM architectures are often resource-intensive, making them inaccessible for many researchers. This project introduces an optimized architecture that significantly reduces memory usage and computational costs while maintaining the accuracy required for sc-omics analysis.

### Key Features:
- **Low Memory Usage:** Utilizing a Gradient Low-Rank (GaLore) projection method, the model reduces memory requirements by optimizing gradient calculations without sacrificing performance.
- **Single-Cell Genomic Data:** The model is designed to process and analyze high-dimensional single-cell data, providing deeper insights into cellular biology.
- **Transformer-Based Architecture:** Incorporates a Masked Attention Transformer for gene expression prediction, cell type classification, and gene network inference.

## Methods

- **Gradient Low-Rank Projection (GaLore):** This method exploits the low-rank structure of gradients during training to optimize memory usage.
- **scGPT Network Architecture:** The architecture consists of input embeddings, masked attention transformer layers, and fine-tuning mechanisms for gene expression and cell type classification tasks.
- **Optimization with ADAM:** The model integrates GaLore with the ADAM optimizer to further reduce memory usage during training.

## Results

- Memory usage was reduced by approximately 10% compared to full-rank optimization methods.
- The model achieves competitive accuracy for cell type classification while operating within reduced memory constraints.

## Future Work

Future efforts aim to:
- Extend the model to handle more complex sc-omics tasks like batch correction and gene network inference.
- Scale the model to analyze larger datasets across multiple species or conditions.
- Develop real-time analysis tools for clinical and biotechnological applications.

 



