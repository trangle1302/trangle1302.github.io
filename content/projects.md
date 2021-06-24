+++
title = "Projects"
date = "2021-06-24"
aliases = ["about-us","about-hugo","contact"]
[ author ]
  name = "Trang Le"
+++



# Current projects 

## Analysis of the Human Protein Atlas Weakly-Supervised Single Cell Classification Competition 
Main challenges in investigating single-cell protein localization in fluorescent images includes protein’s multi-localization, class imbalance and, in many case, weak-labels, especially in large image database like Human Protein Atlas where precise single-cell labels are expensive and laborious to generate, while image-level labels are abundantly present. This motivated a competition to crowdsource solutions for using our dataset annotated with coarse image-level labels in a weakly-supervised setting to generate precise single cell level protein localization labels. The successful development of single cell pattern classification models will provide higher-quality organelle feature maps, and enable the study of localization heterogeneity in single cells and facilitate the discovery of new subtle, rare or transient patterns that cannot reliably be observed across entire cell populations.

Competition site: https://www.kaggle.com/c/hpa-single-cell-image-classification


## Modelling the spatial cell cycle with deep learning 
The cell-division cycle is a vital and highly regulated process in which different proteins are synthesized and accumulated in different phases. Deviation from the cell cycle often results in diseases, notably cancers, and phases of the cell determine whether a cell can respond to certain stimuli, e.g. a given drug. Therefore, predicting and quantifying the cell cycle state, through visualization in large datasets of fluorescent images, is critical in studying many biological processes. Deep learning algorithms have proven to be effective at analyzing information-rich datasets like images. In this project, a deep learning architecture is used to predict the expression pattern of classical cell cycle dependent proteins like CDT1, Geminin and Cyclinb1 based on 2D visualization of U2OS cells. We found that the intensity and morphology of the cell hold enough information to these proteins’ levels and localization, from which the cell cycle state can be derived. This approach acts as the first step towards an integrated cell model, where high parametric measurement of cells can be predicted, eliminating the need for invasive experimentation.



## Cellular shape space 
Protein functions are closely linked to its location. However, the relationship between intracellular organization, protein expression and phenotype is not well understood. Using the large collection of 2D images from the Human Protein Atlas where each organelle is represented with multiple proteins, we aim to create a mean cell organization with the natural range of cell-to-cell variation to study the relationships of proteins and organelles in relation to cell’s shape.


# Other projects

## Interactive biomedical segmentation tool powered by deep learning and ImJoy **
https://f1000research.com/articles/10-142

Repo: https://github.com/imjoy-team/imjoy-interactive-segmentation

