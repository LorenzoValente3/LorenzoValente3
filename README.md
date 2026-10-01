<a href="https://lorenzovalente3.github.io/research/"><img src="banner.svg" width="100%" alt="Lorenzo Valente, particle showers crossing a calorimeter"></a>

I work on making one generative shower model reusable across calorimeter geometries. Pre-trained on several detectors, it adapts to a new one with two orders of magnitude fewer Geant4 showers than a model trained from scratch.

[Website](https://lorenzovalente3.github.io/research/) · [ORCID](https://orcid.org/0009-0007-0080-8738) · [Hugging Face](https://huggingface.co/lorenzov506) · [LinkedIn](https://www.linkedin.com/in/lorenzo-valente-491881201)

#### Selected papers and code

- [Transferable Fast Calorimeter Shower Generation via Multi-Geometry Pre-training](https://arxiv.org/abs/2608.18233).\
  Code: [AllShowers](https://github.com/FLC-QU-hep/AllShowers/tree/multi-geometry) and [PointCountFM](https://github.com/FLC-QU-hep/PointCountFM/tree/multi-geometry), weights on [Hugging Face](https://huggingface.co/FLC-QU-hep).

- [Cross-Geometry Transfer Learning in Fast Electromagnetic Shower Simulation](https://doi.org/10.1088/1748-0221/21/07/P07037), JINST 21 (2026) P07037.\
  Code: [CaloTransfer](https://github.com/FLC-QU-hep/CaloTransfer).

- [CaloClouds3: Ultra-fast Geometry-Independent Highly-Granular Calorimeter Simulation](https://doi.org/10.1088/1748-0221/21/03/P03018), JINST 21 (2026) P03018.

Full list on [INSPIRE](https://inspirehep.net/authors/3080236).

#### Data and simulation

- [multi-calorimeter-dataset](https://github.com/FLC-QU-hep/multi-calorimeter-dataset): Geant4/DD4hep production of the SimpleBox and LEMURS point cloud shower datasets, from simulation to training-ready HDF5, data on [Hugging Face](https://huggingface.co/datasets/FLC-QU-hep/calorimeter-showers-multi-geometry).
- [ddFastSim](https://github.com/fast-sim/ddFastSim): DD4hep fast simulation framework, I develop the mesh sensitive detector extensions used for these datasets ([PR #2](https://github.com/fast-sim/ddFastSim/pull/2)).
