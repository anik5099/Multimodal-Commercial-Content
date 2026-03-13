# MDC³ & TSFC: Multimodal Commercial Content Classification in Bengali

This repository contains resources related to two research works on **multimodal commercial content classification for Bengali social media**.

1. **MDC³ Dataset** – A multimodal dataset of Bengali social media posts.  
2. **TSFC Model** – A hierarchical multimodal classification framework using cross-attention.

These works aim to advance **multimodal NLP research for low-resource languages**, particularly **Bengali**, by providing datasets and models for **commercial content detection and categorization**.

---

# 📊 MDC³: A Novel Multimodal Dataset for Commercial Content Classification in Bengali

### Authors
**Anik Mahmud Shanto, Mst. Sanjida Jamal Priya, Fahim Shakil Tamim, Mohammed Moshiul Hoque**

📅 **Publication:** April 2025  
📍 **Venue:** NAACL Student Research Workshop (NAACL-SRW 2025)

🔗 **Paper:**  
https://aclanthology.org/2025.naacl-srw.31/

---

## 📜 Abstract

Identifying commercial posts in resource-constrained languages among diverse and unstructured content remains a significant challenge for automatic text classification tasks. To address this problem, we introduce **MDC³ (Multimodal Dataset for Commercial Content Classification)**, a novel dataset consisting of **5,007 annotated Bengali social media posts**, categorized into **commercial** and **non-commercial** classes.

We also provide a **comprehensive annotation guideline** that can facilitate future dataset creation for resource-constrained languages. Furthermore, we conduct extensive experiments on MDC³ considering both **unimodal and multimodal approaches**.

Experimental results show that the **late fusion of textual (mBERT) and visual (ViT) models (ViT + mBERT)** achieves the best performance with an **F1-score of 90.91**, significantly outperforming other baseline models.

---
## 📑 Citation  
If you use this dataset or paper, please cite it as follows:

```bibtex
@inproceedings{shanto-etal-2025-mdc3,
    title = "{MDC}$^3$: A Novel Multimodal Dataset for Commercial Content Classification in {B}engali",
    author = "Shanto, Anik Mahmud and
              Priya, Mst. Sanjida Jamal and
              Tamim, Fahim Shakil and
              Hoque, Mohammed Moshiul",
    editor = "Ebrahimi, Abteen and
              Haider, Samar and
              Liu, Emmy and
              Haider, Sammar and
              Leonor Pacheco, Maria and
              Wein, Shira",
    booktitle = "Proceedings of the 2025 Conference of the Nations of the Americas Chapter of the Association for Computational Linguistics: Human Language Technologies (Volume 4: Student Research Workshop)",
    month = apr,
    year = "2025",
    address = "Albuquerque, USA",
    publisher = "Association for Computational Linguistics",
    url = "https://aclanthology.org/2025.naacl-srw.31/",
    pages = "311--320",
    ISBN = "979-8-89176-192-6",
    abstract = "Identifying commercial posts in resource-constrained languages among diverse and unstructured content remains a significant challenge for automatic text classification tasks. To address this, this work introduces a novel dataset named MDC$^3$ (Multimodal Dataset for Commercial Content Classification), comprising 5,007 annotated Bengali social media posts classified as commercial and noncommercial. A comprehensive annotation guideline accompanying the dataset is included to aid future dataset creation in resource-constrained languages. Furthermore, we performed extensive experiments on MDC$^3$ considering both unimodal and multimodal domains. Specifically, the late fusion of textual (mBERT) and visual (ViT) models (i.e., ViT+mBERT) achieves the highest F1 score of 90.91, significantly surpassing other baselines."
}

---

# 🧠 TSFC: A Hierarchical Classification Framework for Multimodal Commercial Contents in Bengali

### Authors
**Anik Mahmud Shanto, Fahim Shakil Tamim, Mst. Sanjida Jamal Priya, Mohammed Moshiul Hoque, Enamul Hoque Prince**

📅 **Publication:** 2026  
📍 **Venue:** IEEE Access (Q1 Journal)

🔗 **Paper:**  
https://ieeexplore.ieee.org/document/11369232

---

## 📜 Abstract

Social media has become a crucial platform for businesses to promote products, significantly influencing consumer behavior and advertising effectiveness. Automatically identifying commercial content from diverse social media posts is essential for targeted advertising and brand monitoring.

Although multimodal content classification has progressed significantly for **high-resource languages**, similar research for **low-resource languages such as Bengali** remains limited.

To address this gap, we introduce **MHDC³ (Multimodal Hierarchical Dataset for Commercial Content Classification)**, which extends MDC³ to support **hierarchical classification**.

The dataset contains **5,007 Bengali social media posts**, categorized into:

### Level 1 (Coarse-grained)
- Commercial (Com)
- Non-commercial (NCom)

### Level 2 (Fine-grained commercial categories)
- Fashion (Fa)
- Food (Fo)
- Lifestyle (LS)
- Trends & Technology (T&T)

To solve this task, we propose **TSFC (Text-Self-Fusion-Cross)**, a **cross-attention-based multimodal model**. The architecture first performs **self-attention on textual features**, followed by **cross-modal fusion with visual representations**.

Extensive experiments demonstrate that TSFC outperforms several state-of-the-art multimodal baselines, achieving:

- **94.38% F1-score for coarse-grained classification**
- **94.80% F1-score for fine-grained classification**

---

# 📂 Dataset Overview

| Dataset | Language | Samples | Modalities | Tasks |
|--------|----------|--------|-----------|------|
| MDC³ | Bengali | 5,007 | Image + Text | Binary classification |
| MHDC³ | Bengali | 5,007 | Image + Text | Hierarchical classification |

---

# 📑 Citation

If you use this dataset or model in your research, please cite the following paper.

```bibtex
@ARTICLE{11369232,
  author={Shanto, Anik Mahmud and Tamim, Fahim Shakil and Priya, Mst. Sanjida Jamal and Hoque, Mohammed Moshiul and Prince, Enamul Hoque},
  journal={IEEE Access}, 
  title={TSFC: A Hierarchical Classification Framework for Multimodal Commercial Contents in Bengali}, 
  year={2026},
  volume={14},
  pages={28411-28434},
  doi={10.1109/ACCESS.2026.3659712}
}
