# Re-thinking the Nature of Planning for Safe and Personalized Treatment Management Planning using Large Language Models

> **Authors:** Ayoub et al.  
> **Conference:** *IEEE International Conference on Bioinformatics and Biomedicine (BIBM 2025)*  
> **Keywords:** Clinical AI, Large Language Models, Treatment Planning, Personalized Medicine, Reasoning, Evaluation Dataset  

---

## 🧠 Overview

This repository accompanies our **IEEE BIBM 2025** paper  
**"Re-thinking the Nature of Planning for Safe and Personalized Treatment Management Planning using Large Language Models"**.

While Large Language Models (LLMs) have made substantial progress in **diagnostic reasoning**, their capacity to deliver **safe, accurate, and personalized treatment management plans** remains limited.  

Our work introduces a **new planning paradigm** that redefines how LLMs conceptualize treatment—not as a fixed goal optimization task, but as the **systemic modulation** of a patient’s illness state toward a healthier state.

---

## 🚀 Core Contributions

### 🧩 1. Novel Evaluation Dataset
We release an **evaluation dataset of 1,015 real-world patient cases**, each containing:
- Complex, realistic **illness narratives**
- Expert-authored **field-specific treatment management plans**

This dataset supports rigorous benchmarking of LLMs’ ability to generate **clinically safe, context-aware, and personalized treatment plans**.

### 🧭 2. Novel Planning Method
We propose a **new formulation of treatment planning** as a *field modulation process*, introducing three core components:

- **Attractive Tendencies:** Latent directional vectors representing desirable shifts toward healthier states.  
- **Field Mapping:** Identification of modifiable life and health domains to define personalized illness management goals.  
- **Field Sculpting:** Generation of actionable, safe, and individualized interventions to guide patients toward resilient health trajectories.

### 📊 3. Strong Empirical Performance
Our approach achieves substantial performance gains over baseline reasoning methods (e.g., CoT, Reflexion):
- **+12 BLEU-4**
- **+11 METEOR**
- Maintains **high clinical relevance** and **computational efficiency**

---

## 🖼️ Conceptual Framework

Below is an illustration of our proposed method:


![Conceptual Framework]([assets/framework.png](https://github.com/ayoubncbae/Illness_Management_Planning/blob/main/framework2%20(1).jpg))

> **Figure:** Overview of the proposed illness planning process: Dataset construction process (a) and proposed planning method (b) used in this study.

---


## 📘 Citation

If you use this work, dataset, or methodology, please cite our **IEEE BIBM 2025** paper:

```bibtex
@inproceedings{Ayoub2025BIBM,
  title={Re-thinking the Nature of Planning for Safe and Personalized Treatment Management Planning using Large Language Models},
  author={Ayoub et al.},
  booktitle={IEEE International Conference on Bioinformatics and Biomedicine (BIBM)},
  year={2025}
}




