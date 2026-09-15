### Lorenzo Valente

PhD candidate at the University of Hamburg (Institute of Experimental Physics, group of Gregor Kasieczka), working on generative models for fast calorimeter simulation. I work on making one generative shower model reusable across calorimeter geometries. Pre-trained on several detectors, it adapts to a new one with two orders of magnitude fewer Geant4 showers than a model trained from scratch.

[Website](https://lorenzovalente3.github.io/research/) · [INSPIRE](https://inspirehep.net/authors/3080236) · [ORCID](https://orcid.org/0009-0007-0080-8738) · [Hugging Face](https://huggingface.co/FLC-QU-hep) · [LinkedIn](https://www.linkedin.com/in/lorenzo-valente-491881201) · lorenzo.valente@uni-hamburg.de

#### Papers

- **Transferable Fast Calorimeter Shower Generation via Multi-Geometry Pre-training**, T. Buss, F. Gaede, G. Kasieczka, L. Valente, [arXiv:2608.18233](https://arxiv.org/abs/2608.18233) (2026), submitted to JINST. Study design, dataset production, training and analysis.
- **Cross-Geometry Transfer Learning in Fast Electromagnetic Shower Simulation**, F. Gaede, G. Kasieczka, L. Valente, [JINST 21 (2026) P07037](https://doi.org/10.1088/1748-0221/21/07/P07037).
- **CaloClouds3: Ultra-fast Geometry-Independent Highly-Granular Calorimeter Simulation**, H. Day-Hall et al., [JINST 21 (2026) P03018](https://doi.org/10.1088/1748-0221/21/03/P03018).
- **Joint Variational Auto-Encoder for Anomaly Detection in High Energy Physics**, L. Valente et al., [PoS ISGC&HEPiX2023 (2023) 014](https://doi.org/10.22323/1.434.0014).

#### Code and data

- [multi-calorimeter-dataset](https://github.com/FLC-QU-hep/multi-calorimeter-dataset): Geant4/DD4hep production of the SimpleBox and LEMURS point cloud shower datasets, simulation to training-ready HDF5.
- [AllShowers](https://github.com/FLC-QU-hep/AllShowers/tree/multi-geometry) and [PointCountFM](https://github.com/FLC-QU-hep/PointCountFM/tree/multi-geometry): the multi-geometry pre-training and transfer code of arXiv:2608.18233 (branch `multi-geometry`), weights on [Hugging Face](https://huggingface.co/FLC-QU-hep).
- [CaloTransfer](https://github.com/FLC-QU-hep/CaloTransfer): code of the JINST cross-geometry transfer paper.
- [ddFastSim](https://github.com/fast-sim/ddFastSim): DD4hep fast simulation framework (CERN). I develop the mesh sensitive detector extensions used for the datasets above ([PR #2](https://github.com/fast-sim/ddFastSim/pull/2)).
- [JointVAE4AD](https://github.com/LorenzoValente3/JointVAE4AD): joint continuous and discrete VAE for anomaly detection, code of the PoS 2023 paper.
- [Autoencoder-for-FPGA](https://github.com/LorenzoValente3/Autoencoder-for-FPGA): quantization-aware autoencoder deployed with hls4ml, from my master's work.
