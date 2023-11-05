# **Effectiveness of the Boundary Shrink Method (Unlearn Model)**

![7211160284_9d0e54fb90_o.jpg](https://realkm.com/wp-content/uploads/2021/09/7211160284_9d0e54fb90_o.jpg)


**Author: Muhammad Umair Ali**

**Date: 26/10/2023**
## Introduction:
In the era of advancing machine learning applications, the deployment of models, trained on sensitive data such as medical records etc, raises concerns about privacy. The potential vulnerabilities exposed by model inversion attacks underscore the risks to individual privacy.
Addressing such concerns necessitates the implementation of efficient machine unlearning techniques, enabling models to selectively forget specific training data and adhere to privacy regulations.



## Objective:

**1. Maintaining Utility**

**2. Ensuring Privacy**

To fulfill the utility guarantee, the unlearned model should exhibit reduced generalization on forgotten data while retaining predictive performance on the remaining data. Simultaneously, to uphold privacy, the unlearned model must refrain from disclosing any information about the forgotten data.

## Methodology:

Our Methodology, named **"Boundary Shrink"** is inspired by recent advances in adversarial attacks. It uses a neighbor-searching method to quickly find and shift decision boundaries of the trained model. By predicting cross samples on the trained model and changing labels, our method effectively reduces the boundary of the forgetting class.
