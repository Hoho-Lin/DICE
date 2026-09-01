# DICE: Decentralized Incentive-driven Federated Learning for Efficient & Scalable Customization of Pretrained Models in Web3

This repository hosts the **technical report** of **DICE**, a novel blockchain-powered federated learning (BCFL) algorithm designed to customize large pretrained models (PMs) in **resource-constrained and trustless Web3 environments**.

---

## Overview

Customizing Pretrained Models (PMs) for downstream tasks demands task-specific data, which burgeoning Web3 applications provide abundantly. Blockchain-powered federated learning (BCFL) offers a secure and privacy-preserving paradigm to customize PMs among **self-interested** and **untrusted** Web3 participants. Yet, existing BCFL algorithms face severe **efficiency** and **scalability** challenges when applied to large PMs, due to their substantial computational and memory requirements and the hardware constraints of many participants. 

**DICE** is a novel BCFL algorithm that addresses the efficiency and scalability challenges of customizing large PMs in Web3 via two sets of synergistic techniques: 

(i) a **dynamic progressive learning** scheme and a **model slice verification** scheme to enable a wider range of honest participants, including those unable to deploy the full model, to engage in customizing PMs, while preserving model utility; 

(ii) a **tree-structured committee consensus** protocol and an **efficiency-driven incentive** scheme to address the dominant bottleneck that hinders existing BCFL algorithms from scaling to a larger number of data holders for customizing data-hungry large PMs, while maintaining security. 

---

## Citation

If you use DICE or the technical report in your research, please cite:

```bibtex
@article{lin2026dice,
  title   = {DICE: Decentralized Incentive-driven Federated Learning for Efficient & Scalable Customization of Pretrained Models in Web3},
  author  = {Hong Lin, Zhongle Xie, Lidan Shou, Ke Chen, Gang Chen},
  journal = {Proceedings of the 35th ACM International Conference on Information and Knowledge Management (CIKM '26)},
  year    = {2026},
  doi     = {10.1145/3799682.3840574}
}
