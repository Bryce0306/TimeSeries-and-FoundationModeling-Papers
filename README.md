# Time Series and Foundation Modeling Papers
This repository collects and organizes research papers on time series analysis and foundation models.   

#### Abbreviations
- **LSTF**: Long Sequence Time-Series Forecasting  
- **MTS**: Multivariate Time Series  
- **TSFMs**: Time Series Foundation Models  

#### Organization
 The organization of this repository is inspired by the taxonomy proposed in the paper [Foundation Models for Time Series Analysis: A Tutorial and Survey](https://arxiv.org/abs/2403.14735). Papers are categorized into the following groups:
1. **Model Architecture**: Papers are grouped based on the underlying architecture, such as:
   - **Transformer-based Models**
   - **Non-transformer-based Models**
   - **Diffusion-based Models**

2. **Pre-training Techniques**: Subcategories under each architecture are based on the learning methods used, including:
   - Fully-supervised
   - Self-supervised (e.g., contrastive learning, generative learning)

3. **Adaptation Strategies**: Methods for applying foundation models to specific tasks, such as:
   - Zero-shot learning
   - Fine-tuning
   - Prompt engineering

Each paper is listed under its respective category with its title, authors, proceeding, keywords, and a link to the full text.

## Transformer-based Models

| Author            | Title                                                | Proceeding   | KeyWords | Link                                     |
|-------------------|------------------------------------------------------|--------------|----------|------------------------------------------|
| Yuxuan Liang, et al. | Foundation Models for Time Series Analysis: A Tutorial and Survey  | KDD 2024 | Survey Paper, TSFMs | https://arxiv.org/abs/2403.14735 |
| Mingtian Tan, et al. | Are Language Models Actually Useful for Time Series Forecasting?  | NeurIPS 2024 | LLM | https://arxiv.org/abs/2406.16964 |
| Xin Liu, et al. | Large Language Models are Few-Shot Health Learners  |  | LLM, Health | https://arxiv.org/abs/2305.15525 |
| Yong Liu, et al. | AutoTimes: Autoregressive Time Series Forecasters via Large Language Models | NeurIPS 2024 | LLM, Forecast, Autoregressive | https://arxiv.org/abs/2402.02370 |
| H. Kamarthi and B.A.Prakash | Large Pre-trained time series models for cross-domain Time series analysis tasks | NeurIPS 2024 | LLM, SSL, Cross-Domain | https://arxiv.org/abs/2311.11413 |
| H. Ji and P.Zhou | Advancing PPG-Based Continuous Blood Pressure Monitoring from a Generative Perspective | SENSYS 2024 | Diffusion Model, Medical | https://dl.acm.org/doi/abs/10.1145/3666025.3699365 |

## Transformer-based
| Author            | Title                                                | Proceeding   | KeyWords | Link                                     |
|-------------------|------------------------------------------------------|--------------|----------|------------------------------------------|
| Yihe Wang, et al. | Medformer: A Multi-Granularity Patching Transformer for Medical Time-Series Classification | NeurIPS 2024 | Transformer, Medical, Classification | https://arxiv.org/abs/2405.19363 |
| Haoyi Zhou, et al. | Informer: Beyond Efficient Transformer for Long Sequence Time-Series Forecasting | AAAI 2021 | Transformer, LSTF | https://arxiv.org/abs/2012.07436 |
| Qingsong Wen, et al. | Transformers in Time Series: A Survey | IJCAI 2023 | Transformer, Survey Paper | https://arxiv.org/abs/2202.07125 |
| Y. Zhang and J. Yan | Crossformer: Transformer Utilizing Crossdimension Dependency for Multivariate Time Series Forecasting | ICLR 2023 | Transformer, MTS | https://openreview.net/forum?id=vSVLM2j9eie |
| Yuqi Nie, et al. | (PatchTST) A Time Series is Woeth 64 Words:  Long-Term Forecasting with Transformers | ICLR 2023 | Transformer, SSL | https://arxiv.org/abs/2211.14730 |


## SSL
| Author            | Title                                                | Proceeding   | KeyWords | Link                                     |
|-------------------|------------------------------------------------------|--------------|----------|------------------------------------------|
| Kexin Zhang, et al. | Self-Supervised Learning for Time Series Analysis: Taxonomy, Progress, and Prospects | IEEE 2024 | SSL, Survey Paper | https://arxiv.org/abs/2306.10125 |
| Zhe Li, et al. | Ti-MAE: Self-Supervised Masked Time Series Autoencoders  |   | MAE, SSL | https://arxiv.org/abs/2301.08871 |
| Zhihan Yue, et al. | TS2Vec: Towards Universal Representation of Time Series  |  AAAI 2022 | Contrastive Learning, SSL | https://arxiv.org/abs/2106.10466 |
| Dongsheng Luo, et al. | Time Series Contrastive Learning with Information-Aware Augmentations | AAAI 2023 | Contrastive Learning, SSL | https://arxiv.org/abs/2303.11911 |
| Jiaxiang Dong, et al. | SimMTM: A Simple Pre-Training Framework for Masked Time-Series Modeling | NeurIPS 2023 | SSL, Masked Modeling | https://arxiv.org/abs/2302.00861 |
| Yucheng Shi, et al. | GiGaMAE: Generalizable Graph Masked Autoencoder via Collaborative Latent Space Reconstruction  | CIKM 2023 | MAE | https://arxiv.org/abs/2308.09663 |

