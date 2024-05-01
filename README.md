# Balancing Utility with Privacy in Generated Synthetic Datasets
Julia L. Wang | [Linkedin](https://www.linkedin.com/in/julia-long-wang/) | [My Website](https://www.julia-wang.dev) | <wang.julia08@gmail.com>

Hello World! Welcome to my thesis, here I detail the structure of this directory. 

## Abstract
> This thesis investigates the privacy-preserving properties of synthetic financial datasets generated by advanced generative AI models. In the age of big data, where financial institutions increasingly rely on machine learning for decision-making, protecting personal information is a significant consideration. This work assesses four prominent generative models: CTGAN, TVAE, DoppelGANger, and Banksformer. The research methodology includes comprehensive privacy evaluation metrics, such as re-identification risk, attribute disclosure risk, and susceptibility to membership inference attacks. The results reveal the strengths and limitations of each model in terms of privacy protection and demonstrate that while some models maintain higher fidelity to the original data distributions, others offer stronger privacy guarantees by deviating more significantly from the real datasets. Notably, Banksformer and DoppelGANger reveal the best performance concerning utility, however, there are higher risks of privacy breaches. Concluding that the current generative models exhibit varying levels of privacy preservation, the thesis advocates for future research to establish a quantifiable balance between data utility and privacy.

## 01. Reports
Here you can find the executive summary of my thesis at 'UtilityVsPrivacy_thesis_4Pager.pdf', the thesis presentation slide deck at 'UtilityVsPrivacy_deck.pdf', and my full thesis 'UtiityVsPrivacy_thesis_full.pdf'.

## 02. Data
This folder consists of all the generated synthetic datasets as well as resulting csvs from the evaluation portions. 

## 03. Code
This folder contains all the code for both the generation of synthetic data and privacy evaluation of the selected models. 

Each generative model investigated is given its own subdirectory which contains a README with further instructions for running. The final models utilized in the thesis were: CTGAN, TVAE, Banksformer, DoppelGANger. 

The privacy evaluation analysis can all be found in 'PrivacyEvaluation.ipynb'.