# LEUKEMIA CELL CLASSIFICATION 🔬

**Swin Transformer Tiny Architecture for C-NMC 2019 Dataset**

This repository contains the source code and necessary files to reproduce the findings presented in our scientific article on the classification of leukemia cells (C-NMC 2019 Dataset) using the Swin Transformer model.

---

## 📄 **Article Citation**

If this repository is associated with a published paper, please cite it as follows:

Douglas Costa Braga, Albert de Jesus Souza, Samuel Bastos Borges Pinho, and Daniel Oliveira Dantas (in press). Classification of normal versus leukemic cells with Swin Transformer and balanced data augmentation. In Proceedings of the 21st International Joint Conference on Computer Vision, Imaging and Computer Graphics Theory and Applications, volume 4, VISAPP, pages xxx–xxx. INSTICC, SciTePress.

```
@inproceedings{Braga2026leukemic,
  author={Braga, Douglas Costa and Souza and Albert de Jesus and Pinho, Samuel Bastos Borges Pinho and Dantas, Daniel Oliveira},
  title={Classification of Normal versus Leukemic Cells with Swin Transformer and Balanced Data Augmentation},
  booktitle={Proceedings of the 21st International Joint Conference on Computer Vision, Imaging and Computer Graphics Theory and Applications},
  volume={4, VISAPP},
  year={in press},
  pages={xxx--xxx},
  publisher={SciTePress},
  organization={INSTICC},
  doi={10.5220/xxxxxxxxxxxxxxx},
  isbn={978-989-758-488-6},
  issn={2184-4321},
}
```


---

## 🚀 **Quick Setup & Reproduction**

### 1. **Code Notebook**

The classification logic, training loop, and evaluation methods are detailed in the accompanying Jupyter Notebook:

* **Notebook:** [`swin-transformer-tiny-cnmc-2019.ipynb`](https://github.com/brspinho/Leukemia-Classification-with-Explainable-A.I/blob/7dfdd3967069e2a820864beff66ba14420a3c0ff/swin-transformer-tiny-cnmc-2019.ipynb)

### 2. **Data Source**

The experiments utilized the **C-NMC 2019 Dataset**. The dataset must be downloaded from the original source on Kaggle and placed in the appropriate directory structure for the notebook to function.

* **Dataset Link:** [https://www.kaggle.com/datasets/shafiullahshafin/c-nmc-2019-dataset](https://www.kaggle.com/datasets/shafiullahshafin/c-nmc-2019-dataset)

### 3. **Hardware & Environment**

All core experiments and results reported in the article were executed on the **Kaggle platform** using the **NVIDIA Tesla P100 GPU**.

* **Execution Environment:** Kaggle Notebooks
* **GPU Used:** NVIDIA Tesla P100

---

## 💾 **Pre-trained Files & Metrics**

We provide the trained model parameters and the recorded metric to facilitate comparison and retraining.

### A. **Trained Model Parameters (for Retraining)**

The checkpoint file (`.pth`) containing the learned weights of the Swin Transformer model.

* **Download Link:** [https://drive.google.com/file/d/1b4C0jr9QEnslJketPI9IkWPZVXivjLqr/view?usp=sharing](https://drive.google.com/file/d/1b4C0jr9QEnslJketPI9IkWPZVXivjLqr/view?usp=sharing)

### B. **Archived Training Metrics (Article Results)**

Containing the Loss, Accuracy, F1-Score, etc., captured Test Results from the final run.

* **Download Link:** [https://drive.google.com/file/d/1FZoq-mJmUjUEQGX2kk-6IrTCTBk84MmD/view?usp=sharing](https://drive.google.com/file/d/1FZoq-mJmUjUEQGX2kk-6IrTCTBk84MmD/view?usp=sharing)

---

## 🧑‍💻 **Authors & Contribution**

* Douglas Costa Braga<sup>a</sup>
* Albert de Jesus Souza<sup>a</sup>
* Samuel Bastos Borges Pinho<sup>a</sup>
* Daniel Oliveira Dantas<sup>a</sup>

<sup>a</sup> Departamento de Computação, Universidade Federal de Sergipe, São Cristóvão, SE, Brasil

### Contact

For any questions regarding the code or the paper's methodology, please contact:

* **Albert de Jesus Souza** - [albert.souza@dcomp.ufs.br](mailto:albert.souza@dcomp.ufs.br)
* **Samuel Bastos Borges Pinho** - [samuel.pinho@dcomp.ufs.br](mailto:samuel.pinho@dcomp.ufs.br)
* **Daniel Oliveira Dantas** - [ddantas@dcomp.ufs.br](mailto:ddantas@dcomp.ufs.br)
