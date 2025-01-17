# <h1 align="center">Awesome ML-for-Spectroscopy Papers</h1>

本列表聚焦“**Spectra Prediction**”与“**Structure Elucidation**”两大主题，并将其它相关任务（如功能基预测、分子生成、反应预测等）归为若干更大类别。欢迎补充！

## Table of Contents

- [Structure Elucidation](#structure-elucidation)
- [Spectra Prediction](#spectra-prediction)
- [Ion & Fragmentation](#ion--fragmentation)
- [Metabolites & Functional Groups](#metabolites--functional-groups)
- [Reaction & Catalyst](#reaction--catalyst)
- [Molecular Generation & Retrieval](#molecular-generation--retrieval)
- [NMR & Advanced Properties](#nmr--advanced-properties)

---

## Structure Elucidation

- **Unraveling Molecular Structure: A Multimodal Spectroscopic Dataset for Chemistry**  
  [paper](https://nips.cc/virtual/2024/poster/97441) ・ *Venue*: Tetrahedron Computer Methodology ・ *Dataset*: USPTO, NIST Gas-Phase IR Database

- **Can LLMs Solve Molecule Puzzles? A Multimodal Benchmark for Molecular Structure Elucidation**  
  [paper](https://github.com/KehanGuo2/MolPuzzle) ・ *Venue*: NeurIPS-24 ・ *Dataset*: constructed from textbook

- **A framework for automated structure elucidation from routine NMR spectra**  
  [paper](https://pubs.rsc.org/en/content/articlelanding/2021/sc/d1sc04105c) ・ *Venue*: Chem Science ・ *Dataset*: GDB-13

- **Cross-Modal Retrieval Between 13C NMR Spectra and Structures Based on Focused Libraries**  
  [paper](https://pubs.acs.org/doi/10.1021/acs.analchem.3c04294) ・ *Venue*: Analytical Chemistry ・ *Dataset*: ChEMBL, COCONUT

- **Conditional Molecular Generation Net Enables Automated Structure Elucidation Based on 13C NMR Spectra and Prior Knowledge**  
  [paper](https://pubs.acs.org/doi/10.1021/acs.analchem.2c05817) ・ *Venue*: Analytical Chemistry ・ *Dataset*: PubChem

- **Deep Reinforcement Learning for Molecular Inverse Problem of Nuclear Magnetic Resonance Spectra to Molecular Structure**  
  [paper](https://pubs.acs.org/doi/10.1021/acs.jpclett.2c00624) ・ *Venue*: Journal of Physical Chemistry Letters ・ *Dataset*: nmrshiftdb2

- **Enhancing Chemical Reaction Monitoring with a Deep Learning Model for NMR Spectra Image Matching to Target Compounds**  
  [paper](https://pubs.acs.org/doi/10.1021/acs.jcim.4c00522) ・ *Venue*: JCIM

- **Learning the Language of NMR: Structure Elucidation from NMR spectra using Transformer Models**  
  [paper](https://openreview.net/forum?id=akFqQokObE) ・ *Venue*: AI4Mat-NeurIPS 2023 ・ *Dataset*: Pistachio

- **Deep imitation learning for molecular inverse problems**  
  [paper](https://proceedings.neurips.cc/paper/2019/file/b0bef4c9a6e50d43880191492d4fc827-Paper.pdf) ・ *Venue*: NeurIPS-19 ・ *Dataset*: PubChem & nmrshiftdb2

- **Leveraging infrared spectroscopy for automated structure elucidation**  
  [paper](https://www.nature.com/articles/s42004-024-01341-w) ・ *Venue*: Communications Chemistry ・ *Dataset*: NIST

- **Spectro: A multi-modal approach for molecule elucidation using IR and NMR data**  
  [paper](https://openreview.net/forum?id=K5U7D7YpN0) ・ *Venue*: AI4Mat-NeurIPS 2024

- **DeepSAT: Learning Molecular Structures from Nuclear Magnetic Resonance Data**  
  [paper](https://link.springer.com/article/10.1186/s13321-023-00738-4) ・ *Venue*: Journal of Cheminformatics

- **Database Independent Automated Structure Elucidation of Organic Molecules Based on IR, 1H NMR, 13C NMR, and MS Data**  
  [paper](https://pubs.acs.org/doi/10.1021/acs.jcim.3c01146) ・ *Venue*: Journal of Chemical Information and Modeling

---

## Spectra Prediction

- **Unraveling Molecular Structure: A Multimodal Spectroscopic Dataset for Chemistry**  
  [paper](https://nips.cc/virtual/2024/poster/97441) ・ *Venue*: Tetrahedron Computer Methodology

- **Using Graph Neural Networks for Mass Spectrometry Prediction**  
  [paper](https://arxiv.org/abs/2010.04661) ・ *Venue*: NeurIPS-22

- **Equivariant message passing for the prediction of tensorial properties and molecular spectra**  
  [paper](https://proceedings.mlr.press/v139/schutt21a/schutt21a.pdf) ・ *Venue*: Nature

- **Machine learning molecular dynamics for the simulation of infrared spectra**  
  [paper](https://pubs.rsc.org/en/content/articlelanding/2017/sc/c7sc02267k) ・ *Venue*: ICML-22

- **Machine learning of solvent effects on molecular spectra and reactions**  
  [paper](https://pubs.rsc.org/en/content/articlelanding/2021/sc/d1sc02742e) ・ *Venue*: ICML-22

- **MassFormer: Tandem Mass Spectrum Prediction for Small Molecules using GraphTransformers**  
  [paper](https://arxiv.org/pdf/2111.04824) ・ *Venue*: Nature Machine Learning

- **Mass spectra prediction with structural motif-based graph neural networks**  
  [paper](https://www.nature.com/articles/s41598-024-51760-x) ・ *Venue*: Chem Science

- **Rapid Approximate Subset-Based Spectra Prediction for Electron Ionization–Mass Spectrometry**  
  [paper](https://pubs.acs.org/doi/10.1021/acs.analchem.2c02093) ・ *Venue*: Analytical Chemistry ・ *Dataset*: NIST

- **Multi-scale Sinusoidal Embeddings Enable Learning on High Resolution Mass Spectrometry Data**  
  [paper](https://arxiv.org/abs/2207.02980) ・ *Venue*: arXiv

- **Efficiently predicting high resolution mass spectra with graph neural networks**  
  [paper](https://arxiv.org/abs/2301.11419) ・ *Venue*: arXiv

- **Generating Molecular Fragmentation Graphs with Autoregressive Neural Networks**  
  [paper](https://pubs.acs.org/doi/full/10.1021/acs.analchem.3c04654) ・ *Venue*: Analytical Chemistry ・ *Dataset*: NIST20, NPLIBI (GNPS)

- **Prediction of Vacuum Ultraviolet/Ultraviolet Gas-Phase Absorption Spectra Using Molecular Feature Representations and Machine Learning**  
  [paper](https://pubs-acs-org.proxy.library.nd.edu/doi/10.1021/acs.jcim.4c00676) ・ *Venue*: JCIM

- **Raman Spectra of Amino Acids and Peptides from Machine Learning Polarizabilities**  
  [paper](https://pubs.acs.org/doi/10.1021/acs.jcim.4c00077) ・ *Venue*: JCIM

- **Machine Learning Models for Predicting Molecular UV–Vis Spectra with Quantum Mechanical Properties**  
  [paper](https://pubs.acs.org/doi/10.1021/acs.jcim.2c01662) ・ *Venue*: JCIM

- **Boosting the Modeling of Infrared and Raman Spectra of Bulk Phase Chromophores with Machine Learning**  
  [paper](https://pubs.acs.org/doi/10.1021/acs.jctc.4c00630) ・ *Venue*: JCTC

- **Accelerating Molecular Vibrational Spectra Simulations with a Physically Informed Deep Learning Model**  
  [paper](https://pubs.acs.org/doi/10.1021/acs.jctc.4c00173) ・ *Venue*: JCTC

- **Graph Neural Networks for Learning Molecular Excitation Spectra**  
  [paper](https://pubs.acs.org/doi/10.1021/acs.jctc.2c00255) ・ *Venue*: JCTC

- **Reconstruction of Nuclear Ensemble Approach Electronic Spectra Using Probabilistic Machine Learning**  
  [paper](https://pubs.acs.org/doi/10.1021/acs.jctc.2c00004) ・ *Venue*: JCTC

- **Physically inspired deep learning of molecular excitations and photoemission spectra**  
  [paper](https://pubs.rsc.org/en/content/articlelanding/2021/sc/d1sc01542g) ・ *Venue*: Chem Science

- **Deep Learning for Generating Phase-Conditioned Infrared Spectra**  
  [paper](https://pubs.acs.org/doi/10.1021/acs.analchem.4c04786) ・ *Venue*: Analytical Chemistry

- **Machine learning of optical properties of materials – predicting spectra from images and images from spectra**  
  [paper](https://pubs.rsc.org/en/content/articlelanding/2019/sc/c8sc03077d) ・ *Venue*: Chem Science  
  *(另列于 [NMR & Advanced Properties](#nmr--advanced-properties) 中的“image generation”相关)*

- **Machine learning of solvent effects on molecular spectra and reactions**  
  [paper](https://pubs.rsc.org/en/content/articlelanding/2021/sc/d1sc02742e) ・ *Venue*: Chem Science

- … (更多同属“Spectra Prediction”可按需添加)

---

## Ion & Fragmentation

> 包含：Retention Time Prediction, Fragment Ion Intensity, Precursor Charge State, product formula, mass-spectra-based tasks, amino-acid (peptide) prediction等

- **PROSPECT PTMs: Rich Labeled Tandem Mass Spectrometry Dataset of Modified Peptides for Machine Learning in Proteomics**  
  [paper](https://nips.cc/virtual/2024/poster/97558) ・ *Venue*: NeurIPS-24

- **Prefix-Tree Decoding for Predicting Mass Spectra from Molecules**  
  [paper](https://proceedings.neurips.cc/paper_files/paper/2023/hash/97d596ca21d0751ba2c633bad696cf7f-Abstract-Conference.html) ・ *Venue*: NeurIPS-23

- **De novo mass spectrometry peptide sequencing with a transformer model**  
  [paper](https://proceedings.mlr.press/v162/yilmaz22a.html) ・ *Venue*: NeurIPS-23

- **PROSPECT: Labeled tandem mass spectrometry dataset for machine learning in proteomics.**  
  [paper](https://openreview.net/forum?id=4nAe0PS7D-l) ・ *Venue*: arXiv

(可继续补充同类)

---

## Metabolites & Functional Groups

> 包含：功能基预测、代谢物注释、亚结构分类、筛选方法、光谱分类等

- **Functional Group Identification for FTIR Spectra Using Image-Based Machine Learning Models**  
  [paper](https://pubs.acs.org/doi/10.1021/acs.analchem.1c00867) ・ *Venue*: Analytical Chemistry

- **Spectral deep learning for prediction and prospective validation of functional groups**  
  [paper](https://pubs.rsc.org/en/content/articlelanding/2020/sc/c9sc06240h) ・ *Venue*: Chem Science ・ *Dataset*: NIST

- **CBMAFF-Net: An Intelligent NMR-Based Nontargeted Screening Method for New Psychoactive Substances**  
  [paper](https://pubs.acs.org/doi/abs/10.1021/acs.analchem.3c02540) ・ *Venue*: Analytical Chemistry

- **Systematic classification of unknown metabolites using high-resolution fragmentation mass spectra**  
  [paper](https://www.nature.com/articles/s41587-023-01740-3) ・ *Venue*: Nature Biotechnology ・ *Dataset*: NIST, GNPS, MassBank, etc.

- **CMSSP: A Contrastive Mass Spectra-Structure Pretraining Model for Metabolite Identification**  
  [paper](https://pubs.acs.org/doi/full/10.1021/acs.analchem.3c04654) ・ *Venue*: Analytical Chemistry

- **METASPACE-ML: Context-specific metabolite annotation for imaging mass spectrometry using machine learning**  
  [paper](https://www.nature.com/articles/s41467-023-41950-3) ・ *Venue*: Nature Communications

- **MSnet: A Neural Network which Classifies Mass Spectra**  
  [paper](https://www.sciencedirect.com/science/article/pii/089855299090053B) ・ *Venue*: arXiv

- **Accurate and Efficient Structure Elucidation from Routine One-Dimensional NMR Spectra Using Multitask Machine Learning**  
  [paper](https://pubs.acs.org/doi/10.1021/acscentsci.4c01132) ・ *Venue*: ACS Central Science ・ *Dataset*: SpectraBase  

- **Self-supervised clustering of mass spectrometry imaging data using contrastive learning**  
  [paper](https://pubs.rsc.org/en/content/articlelanding/2022/sc/d1sc04077d) ・ *Venue*: Chem Science

(可继续补充同类)

---

## Reaction & Catalyst

> 反应预测、催化剂设计相关

- **Graph-based machine learning interprets and predicts diagnostic isomer-selective ion–molecule reactions in tandem mass spectrometry**  
  [paper](https://pubs.rsc.org/en/content/articlelanding/2020/sc/d0sc02530e) ・ *Venue*: Chem Science

- **Automation and machine learning augmented by large language models in a catalysis study**  
  [paper](https://pubs.rsc.org/en/content/articlelanding/2024/sc/d3sc07012c) ・ *Venue*: Chem Science

(可继续补充同类)

---

## Molecular Generation & Retrieval

> 包含：分子生成、检索、库搜索等

- **MassSpecGym: A benchmark for the discovery and identification of molecules**  
  [paper](https://arxiv.org/abs/2410.23326) ・ *Venue*: NeurIPS-24

(可补充更多分子生成 / 检索相关)

---

## NMR & Advanced Properties

> 其它高阶性质/任务：NMR耦合常数、化学位移、光学/振动谱性质、peak image增强、图像生成、光谱重建等

- **IMPRESSION – prediction of NMR parameters for 3-dimensional chemical structures using machine learning with near quantum chemical accuracy**  
  [paper](https://pubs.rsc.org/en/content/articlelanding/2020/sc/c9sc03854j) ・ *Venue*: Chem Science ・ *Dataset*: CSD

- **Review and Prospect: Deep Learning in Nuclear Magnetic Resonance Spectroscopy**  
  [paper](https://chemistry-europe.onlinelibrary.wiley.com/doi/10.1002/chem.202000246) ・ *Venue*: Chemistry: A European Journal

- **Prediction of 1H NMR Coupling Constants with Associative Neural Networks Trained for Chemical Shifts**  
  [paper](https://pubs.acs.org/doi/10.1021/ci700172n) ・ *Venue*: JCIM

- **Predicting scalar coupling constants by graph angle-attention neural network**  
  [paper](https://www.nature.com/articles/s41598-021-97146-1) ・ *Venue*: Scientific Reports ・ *Dataset*: QM9

- **Neural Message Passing for NMR Chemical Shift Prediction**  
  [paper](https://pubs.acs.org/doi/10.1021/acs.jcim.0c00195) ・ *Venue*: JCIM ・ *Dataset*: nmrshiftdb2

- **Predictive Modeling of NMR Chemical Shifts without Using Atomic-Level Annotations**  
  [paper](https://pubs.acs.org/doi/10.1021/acs.jcim.0c00494) ・ *Venue*: JCIM ・ *Dataset*: nmrshiftdb2

- **Rapid prediction of NMR spectral properties with quantified uncertainty**  
  [paper](https://jcheminf.biomedcentral.com/articles/10.1186/s13321-019-0374-3) ・ *Venue*: Journal of Cheminformatics ・ *Dataset*: nmrshiftdb2

- **Resolution Enhancement of Metabolomic J-Res NMR Spectra Using Deep Learning**  
  [paper](https://pubs.acs.org/doi/10.1021/acs.analchem.4c04786) ・ *Venue*: Analytical Chemistry

- **Deep learning enabled ultra-high quality NMR chemical shift resolved spectra**  
  [paper](https://pubs.rsc.org/en/content/articlelanding/2024/sc/d4sc04742g) ・ *Venue*: Chem Science

- **Two-Dimensional Laplace NMR Reconstruction through Deep Learning Enhancement**  
  [paper](https://pubs.acs.org/doi/10.1021/jacs.4c05211) ・ *Venue*: JACS

- **Repairing Noise-Contaminated Low-Frequency Vibrational Spectra with an Attention U-Net**  
  [paper](https://pubs.acs.org/doi/10.1021/jacs.4c10893) ・ *Venue*: JACS

- **Spectroscopy-Guided Deep Learning Predicts Solid–Liquid Surface Adsorbate Properties in Unseen Solvents**  
  [paper](https://pubs.acs.org/doi/10.1021/jacs.3c10921) ・ *Venue*: JACS

- **DeepSPInN – deep reinforcement learning for molecular structure prediction from infrared and 13C NMR spectra**  
  [paper](https://pubs.rsc.org/en/content/articlelanding/2024/dd/d4dd00008k) ・ *Venue*: Digital Discovery

(可继续补充其他与NMR或复杂性质建模相关的工作)

---

> 如有任何遗漏，或想补充其他有价值的 ML+光谱研究，欢迎 PR 或 Issue！

<br/>

## Contributing
非常感谢任何对本库的贡献或建议，欢迎在此基础上进行增改！

## Contact
- *Email*: [your_email@example.com](mailto:your_email@example.com)  
