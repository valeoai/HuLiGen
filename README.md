# *HuLiGen*: Human LiDAR Generation from Parametric Body Models

This repository will host the official Python implementation for our paper:
> **HuLiGen: Human LiDAR Generation from Parametric Body Models**  
> *Salma Galaaoui, Nermin Samet, and David Picard*  
> [Link to arXiv](https://arxiv.org/pdf/2610.10196)

---

## 🚀 Code Release — Coming Soon
The Python code, training and evaluation scripts for the Flow Matching model as well as our downstream synthetic training data and checkpoints are being cleaned and packaged.

## 📌 Abstract
LiDAR point clouds of humans are extremely expensive to collect and annotate, thus represent a scarce resource that hinders the development of human analysis using this modality. To alleviate this scarcity, prior work relies on simulated human LiDAR, but such samples do not fully reflect the geometry and sensing characteristics of real observations. In contrast, we introduce HuLiGen, a generative model that generates human LiDAR point clouds from a parametric body model, using a point transformer trained with a flow-matching objective. We show that our generated point clouds are closer to the real capture distribution. Using HuLiGen to generate synthetic data, we propose a synthetic-only pretraining scheme for LiDAR-based HPE that achieves state-of-the-art performance, with even larger gains in low-annotation and low-data regimes, where MPJPE is reduced by up to 50%.

## 📝 Citation
If you find our work useful, please bookmark this repository and cite this work:

```bibtex
@misc{galaaouiHuLiGenHumanLiDAR2026,
      title={HuLiGen: Human LiDAR Generation from Parametric Body Models}, 
      author={Salma Galaaoui and Nermin Samet and David Picard},
      year={2026},
      eprint={2610.10196},
      archivePrefix={arXiv},
      primaryClass={cs.CV},
      url={https://arxiv.org/abs/2610.10196}, 
}
```
