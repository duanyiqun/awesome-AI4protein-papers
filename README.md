# Awesome AI for Proteins

A curated list of papers and open-source projects applying **Artificial Intelligence to Protein Science**, including structure prediction, design, sequence generation, interaction prediction, and dynamic simulations. Contributions welcome!

---

## Table of Contents

- [Structure Prediction](#structure-prediction)
- [Protein Design](#protein-design)
- [Sequence Generation](#sequence-generation)
- [Protein-Protein Interaction Prediction](#protein-protein-interaction-prediction)
- [Folding Simulation and Dynamics](#folding-simulation-and-dynamics)

---

## Structure Prediction

### 2023
- **[ESMFold: Evolutionary-scale prediction of atomic-level protein structure](https://www.science.org/doi/10.1126/science.ade2574)** – [[Code](https://github.com/facebookresearch/esm)]  
  Predicts 3D structures directly from single sequences using a 15B parameter language model, nearly matching AlphaFold2 accuracy.

### 2022
- **[OmegaFold: High-resolution de novo structure prediction from primary sequence](https://www.biorxiv.org/content/10.1101/2022.07.21.500999v1)** – [[Code](https://github.com/HeliXonProtein/OmegaFold)]  
  Eliminates the need for MSAs by predicting accurate protein structures from a single sequence.

### 2021
- **[RoseTTAFold: Accurate prediction of protein structures and interactions](https://www.science.org/doi/10.1126/science.abj8754)** – [[Code](https://github.com/RosettaCommons/RoseTTAFold)]  
  Introduces a 3-track model integrating sequence, distance, and coordinates for accurate fast prediction.

- **[AlphaFold2: Highly accurate protein structure prediction](https://www.nature.com/articles/s41586-021-03819-2)** – [[Code](https://github.com/deepmind/alphafold)]  
  Transformer-based structure predictor solving the protein folding problem with near-experimental accuracy.

### 2020
- **[AlphaFold1: Deep learning potentials for structure prediction](https://www.nature.com/articles/s41586-019-1923-7)**  
  Introduces deep residual networks for predicting inter-residue distances for 3D folding.

- **[trRosetta: Interresidue orientations improve structure prediction](https://www.pnas.org/content/117/3/1496)** – [[Code](https://github.com/gjongh/trRosetta)]  
  Predicts distance and orientation distributions from MSA to guide Rosetta folding.

---

## Protein Design

### 2023
- **[RFdiffusion: De novo design with diffusion models](https://www.nature.com/articles/s41586-023-05937-2)** – [[Code](https://github.com/RosettaCommons/RFdiffusion)]  
  A generative diffusion model for protein backbones and complexes, enabling novel fold and motif creation.

- **[Chroma: Programmable generative protein model](https://www.nature.com/articles/s41586-023-06728-8)**  
  Diffusion-based backbone and sequence generator with controllable prompts (e.g. symmetry, function).

### 2022
- **[ProteinMPNN: Robust sequence design](https://www.science.org/doi/10.1126/science.add2187)** – [[Code](https://github.com/dauparas/ProteinMPNN)]  
  Graph-based neural network with state-of-the-art sequence recovery and experimental validation.

- **[Hallucination and Inpainting of functional sites](https://www.science.org/doi/10.1126/science.abn2100)**  
  Uses structure prediction networks to design proteins containing desired catalytic or binding sites.

### 2019
- **[Graph-based generative models for design](https://papers.nips.cc/paper_files/paper/2019/hash/f3a4ff4839c56a5f460c88cce3666a2b-Abstract.html)**  
  Inverse folding using graph neural networks to generate sequences for 3D backbones.

---

## Sequence Generation

### 2023
- **[ProGen2: Language models for protein design](https://www.nature.com/articles/s41587-022-01618-2)**  
  Transformer LMs that generate novel enzymes and control properties via conditioning.

### 2022
- **[ProtGPT2: Unsupervised generation of plausible sequences](https://www.nature.com/articles/s41467-022-32007-7)** – [[Model](https://huggingface.co/nferruz/ProtGPT2)]  
  GPT-2 model trained on UniProt generates diverse, foldable de novo sequences.

### 2021
- **[ProteinGAN: Sequence generation via GANs](https://www.nature.com/articles/s42256-021-00310-5)** – [[Code](https://github.com/Biomatter-Designs/ProteinGAN)]  
  GAN-based method generating functional enzyme variants with low sequence identity.

### 2018
- **[DeepSequence: Generative VAEs for functional variation](https://www.nature.com/articles/s41592-018-0138-4)** – [[Code](https://github.com/debbiemarkslab/DeepSequence)]  
  VAE trained on MSAs models the landscape of functional sequences and mutation effects.

---

## Protein-Protein Interaction Prediction

### 2021
- **[AlphaFold-Multimer: Predicting complex assemblies](https://www.biorxiv.org/content/10.1101/2021.10.04.463034v1)** – [[Code](https://github.com/deepmind/alphafold)]  
  Extension of AlphaFold2 to multimeric complexes with high interface accuracy.

### 2022
- **[EquiDock: SE(3)-Equivariant protein docking](https://openreview.net/forum?id=GQjaI9mLet)** – [[Code](https://github.com/octavian-ganea/equidock_public)]  
  Predicts docking poses without sampling, using equivariant GNNs for fast, accurate alignment.

### 2019
- **[MaSIF: Geometric deep learning for interfaces](https://www.nature.com/articles/s41592-019-0666-6)** – [[Code](https://github.com/LPDI-EPFL/masif)]  
  Learns geometric "fingerprints" on protein surfaces to predict and match interaction sites.

### 2017
- **[PIPR: Recurrent networks for interaction prediction](https://academic.oup.com/bioinformatics/article/33/1/65/2525683)**  
  Siamese GRU-based sequence encoder for classifying interacting protein pairs.

---

## Folding Simulation and Dynamics

### 2023
- **[TorchMD-Net: Neural potentials for protein thermodynamics](https://www.nature.com/articles/s41467-023-41343-1)** – [[Code](https://github.com/torchmd/torchmd-net)]  
  ML-trained coarse-grained potentials model folding thermodynamics at 1000x speed-up.

### 2019
- **[Boltzmann Generators: Sample equilibrium states with flows](https://www.science.org/doi/10.1126/science.aaw1147)**  
  Samples folding conformations directly from Boltzmann distribution via invertible flows.

### 2018
- **[Amber/ML Potentials: Hybrid physics-based simulation](https://www.pnas.org/content/115/21/E4758)**  
  Combines neural networks with classical force fields for atomic-resolution folding.

---

## License

[CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) – Feel free to copy, share, and contribute with attribution.

---

**Contributions welcome!**
- Pull requests: Add papers, fix links, suggest categories
- Issues: Request features, suggest improvements

> Maintained with ❤️ by the AI4Proteins community.

