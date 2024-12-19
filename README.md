# Overview

This repository contains supplementary materials for the following conference paper:

Sukrit Leelaluk, Cheng Tang, Valdemar Švábenský, and Atsushi Shimada.\
**Knowledge Distillation in RNN-Attention Models for Early Prediction of Student Performance**.\
In Proceedings of the 40th ACM/SIGAPP Symposium on Applied Computing ([SAC 2025](https://www.sigapp.org/sac/sac2025/)).\
DOI: 10.1145/3672608.3707805

```bibtex
@inproceedings{Leelaluk2025knowledge,
    author    = {Leelaluk, Sukrit and Tang, Cheng and \v{S}v\'{a}bensk\'{y}, Valdemar and Shimada, Atsushi},
    title     = {{Knowledge Distillation in RNN-Attention Models for Early Prediction of Student Performance}},
    booktitle = {Proceedings of the 40th ACM/SIGAPP Symposium on Applied Computing},
    series    = {SAC '25},
    location  = {Sicily, Italy},
    publisher = {Association for Computing Machinery},
    address   = {New York, NY, USA},
    month     = {03},
    year      = {2025},
    numpages  = {10},
    isbn      = {979-8-4007-0629-5},
    url       = {https://doi.org/10.1145/3672608.3707805},
    doi       = {10.1145/3672608.3707805},
}
```

# File description

### `utils/rnn_attention_kd.py`
Show the structure of RNN-Attention-KD\
See Section 3.2 in the paper.

### `01_teacher_model_training.ipynb`
Training the teacher model using the entire course data to prepare for distilling knowledge to the student model.\
See Section 3.2 and 4.2.2 in the paper.

### `02_student_model_training.ipynb`
Training the student model using the knowledge from the teacher model.\
See Section 3.2 and 4.2.2 in the paper.
