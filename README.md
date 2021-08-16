# ALBRT
Cellular Composition Prediction in Routine Histology Images

Cellular composition prediction, i.e., predicting the presence and counts of different types of cells in the tumor microenvironment from a digitized image of a Hematoxylin and Eosin (H&E) stained tissue section can be used for various tasks in computational pathology such as the analysis of cellular topology and interactions, subtype prediction, survival analysis, etc. In this work, we propose an image-based cellular composition predictor ALBRT which can accurately predict the presence and counts of different types of cells in a given image patch. ALBRT, by its contrastive-learning inspired design, learns a compact and rotation-invariant feature representation that is then used for cellular composition prediction of different cell types. It offers significant improvement over existing state-of-the-art approaches for cell classification and counting. The patch-level feature representation learned by ALBRT is transferrable for cellular composition analysis over novel datasets and can also be utilized for downstream prediction tasks in CPath as well.

# Dataset
For model training and validation <a href = "https://jgamper.github.io/PanNukeDataset/"> PanNuke </a> dataset was used.

For assessing model generalization, <a href = "https://drive.google.com/drive/folders/1eGlF9Dgu3WMEik4fqj0wJ13LKVufsfZ0?usp=sharing" >NuCLS dataset </a> consisting of 1, 744 field of views (FOVs) partitioned into 5 pre-defined train and validation folds was used.

# Proposed Model for cellular composition prediction

<img src="Block Diagram.png" alt="Block Diagram"/>
