# Combating Hallucination and Misinformation: Factual Information Generation with Tokenized Generative Transformer

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT)

## Overview

This repository contains the research paper titled "Combating Hallucination and Misinformation: Factual Information Generation with Tokenized Generative Transformer," published in the Proceedings of the Joint 3rd NLP4DH and 8th IWCLUL, December 1-3, 2023, jointly organized by [Waseda University, Tokyo](https://www.waseda.jp/top/en/) and [Rootroo](https://rootroo.com/en/).

The paper proposes a novel framework for generating accurate and relevant information from large corpora of text, combining a contextual topic modeling algorithm (Co-LDA) with a tokenizer-based generative transformer (TGT) network. The approach aims to overcome the limitations of existing language models, such as hallucination and misinformation generation, by capturing contextual relationships between topics and generating informative sentences based on extracted topic words.

## Key Features

- **Contextual LDA (Co-LDA)**: A topic modeling algorithm that emphasizes context for more meaningful topic representations, enabling the extraction of cohesive and semantically rich topics.
- **Tokenized Generative Transformer (TGT)**: A generative transformer network that leverages masked topic words from Co-LDA to produce factually consistent and coherent sentences.
- **Perplexity-Similarity Scores**: A novel evaluation metric for assessing the semantic similarity between original and generated information, considering variable-length sentence comparisons.

## Important Notice

Please note that we cannot provide the source code immediately due to ethical reasons and the extended version of this paper being under peer-review in a journal. However, we plan to release the code once the peer-review process is complete and approvals are obtained.

## Contact

For any inquiries or further information, please contact the corresponding author:

**Sourav Das** (sourav.das.research@gmail.com / sourav_phd21@iiitkalyani.ac.in)

## Citation

If you find this research helpful in your work, please consider citing the paper:

```bibtex
@inproceedings{das2023combating,
  title={Combating Hallucination and Misinformation: Factual Information Generation with Tokenized Generative Transformer},
  author={Das, Sourav and Chatterji, Sanjay and Mukherjee, Imon},
  booktitle={Proceedings of the Joint 3rd International Conference on Natural Language Processing for Digital Humanities and 8th International Workshop on Computational Linguistics for Uralic Languages},
  pages={143--152},
  year={2023}
}
