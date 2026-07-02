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

----
# 🐟 MorphoFish v4.1

**Uma Plataforma Open Source para Análise Automatizada de Morfometria, Fenótipos e Toxicologia em Zebrafish (Danio rerio)**

---

# Visão Geral

O **MorphoFish** é uma plataforma de código aberto desenvolvida para automatizar a análise de embriões, larvas e adultos de zebrafish a partir de imagens de microscopia.

O software integra segmentação de imagens, morfometria, detecção automática de órgãos, avaliação fenotípica, análise toxicológica e geração automática de relatórios científicos em um único fluxo de trabalho.

O MorphoFish foi projetado para experimentos de alto rendimento (*high-throughput*) em áreas como Biologia do Desenvolvimento, Ecotoxicologia, Farmacologia, Genética, Bioinformática e Pesquisa Biomédica.

---

# Principais Funcionalidades

## Análise Morfométrica

* Segmentação automática do peixe
* Medição da área corporal
* Medição do perímetro
* Estimativa do comprimento corporal
* Identificação automática dos espécimes

---

## Detecção Automática de Órgãos

Atualmente o software detecta automaticamente:

* Olho
* Coração
* Somitos
* Saco vitelino
* Bexiga natatória

Novos órgãos poderão ser adicionados por meio de módulos independentes.

---

## Classificação Fenotípica

Avaliação automática do desenvolvimento conforme a idade do animal.

Estágios suportados:

* Embrião (hpf)
* Larva (dpf)
* Adulto

O sistema pode avaliar alterações como:

* Edema pericárdico
* Edema do saco vitelino
* Alterações craniofaciais
* Deformidades da coluna
* Alterações da bexiga natatória
* Atraso no desenvolvimento

---

## Módulo de Toxicologia

Ferramentas para análise toxicológica seguindo práticas científicas.

Inclui:

* Escore de toxicidade baseado em critérios da OECD
* Estimativa de LC50
* Estimativa de EC50
* Curvas dose–resposta
* Análise de múltiplas concentrações

---

## Estatísticas

Geração automática de análises estatísticas, incluindo:

* Estatísticas descritivas
* Comparação entre grupos experimentais
* ANOVA
* Tabelas para publicação científica

---

## Figuras Científicas

Geração automática de gráficos de qualidade para publicação:

* Comparação entre grupos
* Curvas dose–resposta
* Curvas de LC50
* Curvas de EC50

---

## Paper Engine

Geração automática de relatórios científicos contendo:

* Resumo dos resultados
* Análises morfométricas
* Resultados toxicológicos
* Figuras
* Resumos estatísticos

O objetivo é acelerar a elaboração de artigos científicos.

---

# Fluxo de Trabalho

1. Faça upload de uma ou várias imagens.
2. Selecione o estágio de desenvolvimento.
3. Escolha o grupo experimental.
4. Execute a análise automática.
5. Revise as medidas morfométricas.
6. Analise os órgãos detectados.
7. Calcule os parâmetros toxicológicos.
8. Gere gráficos para publicação.
9. Exporte os dados experimentais.
10. Gere automaticamente um relatório científico.

---

# Processamento em Lote

O MorphoFish suporta análise simultânea de vários espécimes.

Exemplo de organização:

```text
Controle
 ├── peixe_001.png
 ├── peixe_002.png
 ├── peixe_003.png

Tratamento 1
 ├── peixe_001.png
 ├── peixe_002.png

Tratamento 2
 ├── peixe_001.png
 ├── peixe_002.png
```

Todos os espécimes são automaticamente reunidos em um único conjunto de dados experimental.

---

# Instalação

Clone o repositório:

```bash
git clone https://github.com/seu_usuario/MorphoFish.git
```

Instale as dependências:

```bash
pip install -r requirements.txt
```

Execute o programa:

```bash
streamlit run appGui.py
```

---

# Estrutura do Projeto

```text
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

# Dependências

* Python 3.11 ou superior
* Streamlit
* OpenCV
* NumPy
* Pandas
* Matplotlib
* SciPy
* scikit-learn

---

# Aplicações

O MorphoFish pode ser utilizado em:

* Biologia do Desenvolvimento
* Ecotoxicologia
* Descoberta de Fármacos
* Triagem Toxicológica
* Genética do Desenvolvimento
* Neurobiologia
* Monitoramento Ambiental
* Bioinformática
* Fenotipagem em Alto Rendimento

---

# Desenvolvimentos Futuros

Recursos planejados:

* Segmentação baseada em Deep Learning (U-Net)
* Detecção de órgãos com YOLO
* Contagem automática de células
* Quantificação de fluorescência
* Análise comportamental
* Rastreamento em time-lapse
* Análise de placas multiwell
* Processamento em nuvem
* Classificação fenotípica com Inteligência Artificial

---

# Como Citar

Caso utilize o MorphoFish em pesquisas científicas, cite a publicação associada quando estiver disponível.

---

# Licença

Este projeto é distribuído sob a licença MIT.

---

# Autoria

Desenvolvido por:

**Jânice Roberta de Paula**

Computação • Bioinformática • Inteligência Artificial • Processamento de Imagens Científicas

---

# Contato

Para dúvidas, sugestões, colaborações ou contribuições, abra uma *Issue* ou envie um *Pull Request* no repositório oficial do projeto.

