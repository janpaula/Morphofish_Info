# 🐟 MorphoFish v4.1

**An Open-Source Platform for Automated Morphometric, Phenotypic and Toxicological Analysis of Zebrafish (Danio rerio)**

---

## Overview

MorphoFish is an open-source software platform developed for automated analysis of zebrafish embryos and larvae from microscopy images.

The software combines image segmentation, morphometric measurements, organ detection, phenotype assessment, toxicological analysis and scientific report generation into a single workflow.

MorphoFish was designed to simplify high-throughput experiments in developmental biology, ecotoxicology, pharmacology and biomedical research.

---

## Main Features

### Morphometric Analysis

* Automatic fish segmentation
* Body area measurement
* Perimeter measurement
* Body length estimation
* Automatic specimen identification

---

### Organ Detection

Current modules include automatic detection of:

* Eye
* Heart
* Somites
* Yolk sac
* Swim bladder

Additional organs can be incorporated through new detection modules.

---

### Phenotype Classification

Automatic phenotype evaluation according to developmental stage.

Supported stages include:

* Embryo (hpf)
* Larva (dpf)
* Adult

Phenotypic abnormalities evaluated include:

* Pericardial edema
* Yolk edema
* Craniofacial alterations
* Spine defects
* Swim bladder abnormalities
* Developmental delay

---

### Toxicology Module

Scientific toxicology analysis including:

* OECD-style toxicity scoring
* LC50 estimation
* EC50 estimation
* Dose-response curves
* Batch toxicity analysis

---

### Statistics

Automatic statistical analysis including:

* Descriptive statistics
* Group comparison
* ANOVA
* Publication-ready summary tables

---

### Scientific Figures

Automatically generates publication-quality figures including:

* Group comparison plots
* Dose-response curves
* LC50 plots
* EC50 plots

---

### Paper Engine

Automatically generates scientific reports including:

* Results summary
* Morphometric analysis
* Toxicology analysis
* Figures
* Statistical summaries

Designed to accelerate manuscript preparation.

---

## Workflow

1. Upload one or multiple microscopy images.
2. Select developmental stage.
3. Select experimental group.
4. Run automatic analysis.
5. Review morphometric measurements.
6. Evaluate detected organs.
7. Calculate toxicity endpoints.
8. Generate publication-quality figures.
9. Export datasets.
10. Generate scientific report.

---

## Batch Processing

MorphoFish supports analysis of multiple specimens in a single run.

Typical workflow:

```
Control
 ├── Fish_001.png
 ├── Fish_002.png
 ├── Fish_003.png

Treatment 1
 ├── Fish_001.png
 ├── Fish_002.png

Treatment 2
 ├── Fish_001.png
 ├── Fish_002.png
```

All specimens are automatically accumulated into a single experimental dataset.

---

## Installation

Clone the repository:

```bash
git clone https://github.com/your_username/MorphoFish.git
```

Install dependencies:

```bash
pip install -r requirements.txt
```

Run the application:

```bash
streamlit run appGui.py
```

---

## Project Structure

```
MorphoFish/

appGui.py

segmentation.py

tracking.py

morphometry.py

phenotype.py

organ_measurements.py

somite_detector.py

eye_detector.py

heart_detector.py

yolk_detector.py

swim_bladder_detector.py

toxicity_scoring.py

lc50_ec50.py

dose_response.py

figure_generator.py

paper_engine_v3.py

results/

README.md
```

---

## Dependencies

* Python 3.11+
* Streamlit
* OpenCV
* NumPy
* Pandas
* Matplotlib
* SciPy
* scikit-learn

---

## Applications

MorphoFish can be applied in:

* Developmental Biology
* Ecotoxicology
* Drug Discovery
* Toxicological Screening
* Developmental Genetics
* Neurobiology
* Environmental Monitoring
* Bioinformatics
* High-throughput Phenotyping

---

## Future Development

Planned features include:

* Deep learning segmentation (U-Net)
* YOLO-based organ detection
* Cell counting
* Fluorescence quantification
* Behavioral analysis
* Time-lapse tracking
* Multi-well plate analysis
* Cloud computing support
* AI-assisted phenotype classification

---

## Citation

If you use MorphoFish in your research, please cite the associated publication once available.

---

## License

This project is distributed under the MIT License.

---

## Authors

Developed by:

**Jânice Roberta de Paula**

Computational Biology • Bioinformatics • Artificial Intelligence • Scientific Imaging

---

## Contact

For questions, collaborations or contributions, please open an issue or submit a pull request through the project repository.

