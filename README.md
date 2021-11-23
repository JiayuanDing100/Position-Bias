# Position-Bias


This repository provides the dataset analyzed in our paper: " [An Experimental Study of The Effects of Position Bias on Emotion Cause Extraction](https://arxiv.org/pdf/2007.15066.pdf)," Jiayuan Ding and Mayank Kejriwal. The first one is the original one while the second and third one without position bias are proposed by us.

Emotion Cause Extraction (ECE) aims to identify emotion causes from a document after annotating the  emotion keywords. We utilized only position information  relative to the emotion cause to accomplish this goal. Since position information alone without observing the text resulted in higher F-measure, we therefore uncovered a bias in the ECE single genre Sina-news benchmark. We empirically show that high accuracy rate of current state-of-art deep learning models that utilize location information is only evident in datasets that contain such position biases. The accuracy drastically reduced when a dataset with balanced location distribution is introduced. We therefore conclude that it is the innate bias in this benchmark that caused high accuracy rate of these deep learning models in ECE.  We hope that the case study in this paper presents both a cautionarylesson, as well as a template for further studies,in interpreting the superior fit of deep learningmodels without checking for bias. We also make the balanced dataset and rewritten one to be public in this repo.



- **clause_keywords_emotion.txt (original one)**：

|Position|Percentage|
|:----|:--|
Previous 10 Clauses |  0.04\% |
Previous 9 Clauses |  0.04\% |
Previous 7 Clauses |  0.13\% |
Previous 6 Clauses |  0.32\% |
Previous 5 Clauses |  0.32\% |
Previous 4 Clauses |  0.59\% |
Previous 3 Clauses |  1.70\% |
Previous 2 Clauses |  8.12\% |
**Previous 1 Clauses** | **54.45\%** |
**In the same clauses** |  **23.58\%** |
Next 1 Clauses |  7.47\% |
Next 2 Clauses |  2.21\% |
Next 3 Clauses |  0.50\% |
Next 4 Clauses |  0.18\% |
Next 5 Clauses |  0.09\% |
Next 7 Clauses |  0.04\% |
Next 8 Clauses |  0.09\% |
Next 12 Clauses |  0.04\% |


- **clause_keywords_emotion_balance.txt (the size of dataset decreases)**:

|Position|Percentage|
|:----|:--|
Previous 10 Clauses |  0.13\% |
Previous 9 Clauses |  0.13\% |
Previous 7 Clauses |  0.39\% |
Previous 6 Clauses |  0.90\% |
Previous 5 Clauses |  0.90\% |
Previous 4 Clauses |  1.54\% |
Previous 3 Clauses |  4.11\% |
**Previous 2 Clauses** |  **18.87\%** |
**Previous 1 Clauses** | **22.08\%** |
**In the same clauses** |  **21.69\%** |
**Next 1 Clauses** |  **20.41\%** |
Next 2 Clauses |  6.16\% |
Next 3 Clauses |  1.41\% |
Next 4 Clauses |  0.51\% |
Next 5 Clauses |  0.26\% |
Next 7 Clauses |  0.13\% |
Next 8 Clauses |  0.26\% |
Next 12 Clauses |  0.13\% |

- **clause_keywords_emotion_rewrite_regularized.txt (same size with original datatset and not changing original semantics)**
(Based on the principle of not changing original semantic intention, we rewrite sentences and adjust the position of emotional cause clauses in order to make the position distribution more balanced. We keep the same size of this dataset with original one.):

|Position|Percentage|
|:----|:--|
Previous 10 Clauses |  0.05\% |
Previous 9 Clauses |  0.05\% |
Previous 7 Clauses |  0.14\% |
Previous 6 Clauses |  0.32\% |
Previous 5 Clauses |  0.37\% |
Previous 4 Clauses |  0.83\% |
Previous 3 Clauses |  2.31\% |
**Previous 2 Clauses** |  **13.25\%** |
**Previous 1 Clauses** | **38.74\%** |
**In the same clauses** |  **23.60\%** |
**Next 1 Clauses** |  **16.85\%** |
Next 2 Clauses |  2.45\% |
Next 3 Clauses |  0.55\% |
Next 4 Clauses |  0.18\% |
Next 5 Clauses |  0.09\% |
Next 7 Clauses |  0.05\% |
Next 8 Clauses |  0.10\% |
Next 12 Clauses |  0.05\% |



## Cite

Please cite [our paper](https://arxiv.org/pdf/2007.15066.pdf) if you use this new dataset without position bias in your own work:

```
@article{ding2020experimental,
  title={An experimental study of the effects of position bias on emotion causeextraction},
  author={Ding, Jiayuan and Kejriwal, Mayank},
  journal={arXiv preprint arXiv:2007.15066},
  year={2020}
}
```
