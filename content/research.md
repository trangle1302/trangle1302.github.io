+++
title = "Projects"
date = "2021-06-24"
aliases = ["about-us","about-hugo","contact"]
[ author ]
  name = "Trang Le"
+++



# Mapping the spatial proteins patterns in single cell 
Human bodies are complex systems of biological molecules and their interactions. These molecules are collectively quantified and studied in different omics layers, which communicate with each other in healthy and disease. To understand more, sometimes we need to start with less. This motivate me to focus on the actors of all biological mechanisms: the proteins. More specifically, the proteome of a healthy human cell, with which we can benchmark against disease state. 

For centuries, human have made use of microscopy to observe the dissection of life down to nano-scale level. We know that cells are the building blocks of life, and proteins are functional components of the cells. Usually, different proteins come to a specific location to perform a task, and the exact outcome depends on which and how many proteins are present. These dynamics are captured in fluorescent microscopy images at a very large scale in the Human Protein Atlas. Now, advances in image processing techniques and artificial intelligence (AI) allow us to harvest more information about spatial patterns of proteins in each single cell from these images, while software development facilitate domain experts centered AI system.

My thesis can be sectioned as follow: <br>
**Influence on subcellular patterns**	 <br>
Just as every person is unique, even monozygotic twins, differences can be observed between the genetically identical human cells. Therefore, profiling the spatial proteome of typical human cells are challenging. Fundamental aspects like which and how much proteins vary according to the cell-cycle progression (Mahdessian *et al.*, 2021) have to be taken into account. Deep neural networks trained on cell morphology can be used to predict corresponding cell cycle markers localization and intensity (unpublished), just like looking at a human picture to predict the person’s age, gender etc.

**Subcellular feature map powered by weak-supervised models from citizen science competition** <br>
 Main challenges in investigating single-cell protein localization in fluorescent images includes protein’s multi-localization, class imbalance and, in many case, weak-labels, as image-level labels are abundant while single-cell labels are expensive. These problems motivated a citizen science competition on [Kaggle](https://www.kaggle.com/c/hpa-single-cell-image-classification) to crowdsource solutions for using Human Protein Atlas dataset annotated with coarse image-level labels in a weakly-supervised setting to generate precise protein localization labels on single cells. In the span of 3 months, nearly 1000 Kagglers have engaged in image processing and innovative model development. We are now analyzing these single cell pattern classification models, which provide high-quality organelle feature maps, and enable the study of localization heterogeneity in single cells. This will also facilitate the discovery of new subtle, rare or transient patterns that cannot reliably be observed across entire cell populations.

**Where do they lie in the cell?** <br>
The next step is viewing the proteins in the context of a cell. Precise control of the distribution of specific proteins is essential for many biological processes, hence the cell shapes should play a vital role. However, the relationship between cell shapes and protein patterns are surprisingly not well characterized. With advanced mathematical computation and dimensionality reduction techniques, we aim to create a mean cell organization with the natural range of cell-to-cell variation to study the relationships of proteins and organelles in relation to cell’s shape (unpublished).

The insights contributes to a new layer of spatial proteomics towards an integrated cell model, where high parametric measurement of cells can be predicted, eliminating the need for invasive experimentation, and with which profiles of diseased cells can be compared. These works take us one step closer to the paradigm shift of whole cell modelling – the ‘holy grail’ of system biology, where multi-omics measurements can provide a comprehensive understanding of cells as the dynamic and complex systems they are.



# Tool development projects
Stem from the need in my projects and collaborators', I build web-based tools to facilitate the simultaneous annotation of multiple experts and downstream analysis. Examples:

## Interactive biomedical segmentation tool powered by deep learning and ImJoy
Interactive annotation and training tool published here https://f1000research.com/articles/10-142

Repo: https://github.com/imjoy-team/imjoy-interactive-segmentation

## Spatiotemporal mapping of SARS-CoV2 interacting host proteins (unpublished)
annotation tool used to annotate spatial patterns of healthy and COVID-19 infected cells


## Kaggle HPA Singe Cell Image Classification 
annotation tool used to generate all ground-truth single cell labels for this competition
Competition site: https://www.kaggle.com/c/hpa-single-cell-image-classification