# Rethinking Evaluation Methods for Unsupervised Word Embeddings

This repository contains our presentation and teaching video for the paper **"Evaluation methods for unsupervised word embeddings"** by Tobias Schnabel, Igor Labutov, David Mimno, and Thorsten Joachims.

## Paper

Original paper: **[Evaluation methods for unsupervised word embeddings](https://aclanthology.org/D15-1036/)**

PDF: [https://aclanthology.org/D15-1036.pdf](https://aclanthology.org/D15-1036.pdf)

## Presentation

Presentation slides: **[Add your presentation link here](PASTE_PRESENTATION_LINK_HERE)**

## Teaching Video

YouTube video: **[Add your YouTube link here](PASTE_YOUTUBE_LINK_HERE)**

## Overview

This paper studies how to evaluate unsupervised word embeddings in a more meaningful way.

The main idea is that different evaluation methods can rank embedding models differently, so there is no single universal “best” embedding. The paper compares:

* **Intrinsic evaluation**: checking whether similar words are close in the embedding space.
* **Comparative evaluation**: asking humans to choose the better option between candidates.
* **Coherence / intrusion tasks**: checking whether a model can group words into meaningful neighborhoods.
* **Extrinsic evaluation**: using embeddings in downstream tasks such as sentiment classification and noun phrase chunking.

## Key Takeaways

* Standard similarity datasets can be noisy and hard to interpret.
* Relative judgments are often easier and more informative than absolute similarity scores.
* Different models perform differently depending on the task and word frequency.
* Word frequency strongly affects embedding geometry and can distort cosine similarity.
* Intrinsic scores do not always predict downstream task performance.
* Evaluation should be designed around the specific goal of the embedding method.

## What We Covered in Our Presentation

* Basic idea of word embeddings and cosine similarity
* Problems with traditional intrinsic evaluation
* Comparative evaluation using human judgments
* Coherence evaluation using the intrusion task
* Extrinsic evaluation on downstream NLP tasks
* The role of word frequency in embedding bias
* Final conclusions and practical recommendations

## Our Main Conclusion

A word embedding should not be judged using only one generic metric. The right evaluation depends on the task, and frequency effects must be considered carefully.

## Repository Contents

* Presentation slides
* Teaching video link
* README file

## Citation

If you use this work, please cite the original paper:

```bibtex
@inproceedings{schnabel-etal-2015-evaluation,
  title={Evaluation methods for unsupervised word embeddings},
  author={Schnabel, Tobias and Labutov, Igor and Mimno, David and Joachims, Thorsten},
  booktitle={Proceedings of the 2015 Conference on Empirical Methods in Natural Language Processing},
  pages={298--307},
  year={2015},
  organization={Association for Computational Linguistics}
}
```
