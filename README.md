# MoleculeQA
MoleculeQA: A Dataset to Evaluate Factual Accuracy in Molecular Comprehension (EMNLP 2024)

[![Code License](https://img.shields.io/badge/Code%20License-Apache_2.0-green.svg)](LICENSE)
[![arXiv](https://img.shields.io/badge/arXiv-2403.08192-b31b1b.svg)](https://arxiv.org/abs/2403.08192)
[![Huggingface Link](https://img.shields.io/badge/Huggingface-orange?style=flat-square&logo=huggingface)](https://huggingface.co/datasets/hcaoaf/MoleculeQA)

## Intro
Large language models are playing an increasingly significant role in molecular research, yet existing models often generate erroneous information, posing challenges to accurate molecular comprehension. Traditional evaluation metrics for generated content fail to assess a model’s accuracy in molecular understanding. To rectify the absence of factual evaluation, we present MoleculeQA, a novel question answering (QA) dataset which possesses 62K QA pairs over 23K molecules. Each QA pair, composed of a manual question, a positive option and three negative options, has consistent semantics with a molecular description from authoritative molecular corpus. MoleculeQA is not only the first benchmark for molecular factual bias evaluation but also the largest QA dataset for molecular research. A comprehensive evaluation on MoleculeQA for existing molecular LLMs exposes their deficiencies in specific areas and pinpoints several particularly crucial factors for molecular understanding.

# Updates
- [2024-11-26] 🔥 Dataset Release in [Huggingface](https://huggingface.co/datasets/hcaoaf/MoleculeQA)
- [2024-9-20] Paper accepted by EMNLP 2024. (Meta 5, OA avg. 4) -> Findings (Excuse me ?)
- [2024-3-14] Release our paper ["MoleculeQA: A Dataset to Evaluate Factual Accuracy in Molecular Comprehension"](https://arxiv.org/abs/2403.08192)

## License
This project is licensed under the Apache License 2.0. See the [LICENSE](LICENSE) file for more information.

## Citation
```
@inproceedings{lu-etal-2024-moleculeqa,
    title = "{M}olecule{QA}: A Dataset to Evaluate Factual Accuracy in Molecular Comprehension",
    author = "Lu, Xingyu  and
      Cao, He  and
      Liu, Zijing  and
      Bai, Shengyuan  and
      Chen, Leqing  and
      Yao, Yuan  and
      Zheng, Hai-Tao  and
      Li, Yu",
    editor = "Al-Onaizan, Yaser  and
      Bansal, Mohit  and
      Chen, Yun-Nung",
    booktitle = "Findings of the Association for Computational Linguistics: EMNLP 2024",
    month = nov,
    year = "2024",
    address = "Miami, Florida, USA",
    publisher = "Association for Computational Linguistics",
    url = "https://aclanthology.org/2024.findings-emnlp.216",
    pages = "3769--3789",
    abstract = "Large language models are playing an increasingly significant role in molecular research, yet existing models often generate erroneous information. Traditional evaluations fail to assess a model{'}s factual correctness. To rectify this absence, we present MoleculeQA, a novel question answering (QA) dataset which possesses 62K QA pairs over 23K molecules. Each QA pair, composed of a manual question, a positive option and three negative options, has consistent semantics with a molecular description from authoritative corpus. MoleculeQA is not only the first benchmark to evaluate molecular factual correctness but also the largest molecular QA dataset. A comprehensive evaluation on MoleculeQA for existing molecular LLMs exposes their deficiencies in specific aspects and pinpoints crucial factors for molecular modeling. Furthermore, we employ MoleculeQA in reinforcement learning to mitigate model hallucinations, thereby enhancing the factual correctness of generated information.",
}
```
