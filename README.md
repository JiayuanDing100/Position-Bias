# Position-Bias

This repository provides the dataset analyzed in our paper: " An Experimental Study of The Effects of Position Bias on Emotion Cause Extraction," Jiayuan Ding and Mayank Kejriwal. The first one is the original one while the second and third one without position bias are proposed by us.

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

- **clause_keywords_emotion_rewrite_regularized.txt (Based on the principle of not changing original semantic intention, we rewrite sentences and adjust the position of emotional cause clauses in order to make the position distribution more balanced. We keep the same size of this dataset with original one.)**:
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


clause_keywords_emotion_rewrite_regularized.txt (Based on the principle of not changing original semantic intention, we rewrite sentences and adjust the position of emotional cause clauses in order to make the position distribution more balanced. We keep the same size of this dataset with original one.):
[('-1', 0.3873499538319483), ('0', 0.23591874422899353), ('1', 0.16851338873499538), ('-2', 0.13250230840258542), ('2', 0.024469067405355493), ('-3', 0.023084025854108958), ('-4', 0.008310249307479225), ('3', 0.00554016620498615), ('-5', 0.003693444136657433), ('-6', 0.003231763619575254), ('4', 0.0018467220683287165), ('-7', 0.0013850415512465374), ('8', 0.0009233610341643582), ('5', 0.0009233610341643582), ('9', 0.0004616805170821791), ('12', 0.0004616805170821791), ('7', 0.0004616805170821791), ('-10', 0.0004616805170821791), ('-9', 0.0004616805170821791)]


