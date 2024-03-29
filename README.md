# Credit Risk ML Model Explainability
Investigating Machine Learning explainability and interpretability in credit risk models by utilising LIME and DiCE methods.
___

This project explores the realm of Machine Learning explainability and interpretability with credit risk ML models, utilizing the [Freddie Mac dataset](https://www.freddiemac.com/research/datasets/sf-loanlevel-dataset). It focuses on preprocessing and analyzing credit risk data for default and non-default loans, employing machine learning classifiers to understand classification performance in an imbalanced scenario. The core of the project explores model explainability through the application of [LIME (Local Interpretable Model-agnostic Explanations)](https://arxiv.org/abs/1602.04938) and [DiCE (Diverse Counterfactual Explanations)](https://arxiv.org/abs/1905.07697) methods. It is an exploration of AI explainability in credit risk models, demonstrating the application of interpretability tools to provide transparency and accountability in ML financial modeling.

More precisely, the project involves training simple ML classifiers such as Logistic Regression, Decision Trees, and Gradient Boosting, with a Random Forest model serving as a baseline, to explore the LIME and DiCE methods.

Through LIME, the analysis showcases how each feature influences the final decision, illustrated by a case study where a candidate with a high credit score is analyzed to uncover underlying risk factors. 

DiCE complements this by proposing hypothetical scenarios that could change the model's decision, offering 'what-if' narratives that highlight potential paths to different outcomes without changing the trained model.

This was a team project, under the guidance of creditors from Credit Suisse.

## Project Resources

### Jupyter Notebook Analysis

For a view of the project's methodology, including data preprocessing and detailed code, please refer to the Jupyter Notebook. The notebook is extensive, it has plots from the LIME and DiCE analyses and is organized into sections for easier navigation.  [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1gi1D5-H4thwDnxvRcyL5vh0pgSK0Be0N)
You can also download the .ipynb file through a zip file from this repository.

### Project Presentation

The project's findings were also combined into a presentation. Specifically, the second section of the presentation delves into the LIME and DiCE analysis, by using a real-life example to illustrate them better. Additionally, the appendix provides mathematical formulations derived from the relevant papers.
