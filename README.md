# Building an Effective Misogyny Detection Classifier for Low Resource Languages

This repository supports ongoing research into detecting hate speech in **Swedish**, a low-resource language, leveraging the power of Transformer models. The project explores the effectiveness of large multilingual models (e.g., mBERT, XLM-R) and various cross-lingual transfer learning techniques compared to monolingual approaches.

This work is part of my MSc in Language Sciences at UCL.

---

### Goals

*   Compare the performance of multilingual vs. monolingual Transformer models on Swedish misogyny detection.
*   Investigate the effectiveness of different transfer learning strategies:
    *   Zero-Shot Inference
    *   Cross-Lingual Fine-tuning (using English, German, Danish datasets)
    *   Inoculation / Few-Shot Fine-tuning (using minimal Swedish data)
*   Contribute insights into tackling NLP tasks with limited target-language data.

### 🛠️ Technologies Used

*   **Core Libraries:** Python, Hugging Face (`transformers`, `datasets`, `evaluate`), PyTorch / TensorFlow
*   **Models (Examples):** mBERT, XLM-RoBERTa, Swedish BERT variants (KB-BERT etc.)
*   **Environment:** Google Colaboratory (due to GPU requirements)

### Project Status: Work In Progress

This is an **active research project** currently underway, and this repository primarily serves as a placeholder and documentation hub. The code is experimental and subject to frequent updates and refinements as the research progresses towards a corresponding paper.

### Code Access

The primary implementation and experiments are currently conducted within a **Google Colab notebook** due to the computational resources required for training and evaluating Transformer models.

**Access the Colab Notebook Here:** [**https://colab.research.google.com/drive/1MatYWBgW2FLe-u_thPLUvdP9uqgOKxWi?usp=sharing**]

### Planned Future Work 

*   Complete comparative analysis across all planned models and techniques.
*   Refine evaluation metrics and error analysis.
*   Finalise the associated research paper/report.
*   Potentially refactor code into more modular Python scripts (post-research phase).

---
