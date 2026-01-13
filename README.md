# Deep Leaning

## Authors
- Viktória Dobišová
- Nang Cherry Naw
- Deren Ozen

## Project Overview
In this project, we use transfer learning to classify images of natural scenes, using the Intel Image Classification dataset. Our main goal is to fine-tune a pretrained vision model, compare it to a basic CNN built from scratch, and use Grad-CAM visualizations to explain how the models make decisions.

## Setup
All the cells in Jupyter notebook are already ran and the results can be seen directly. However, if the project needs to be rerun, the dataset needs to be downloaded seperately under the right folder as it is not part of this repository for size concerns.

The dataset is Intel Image Classification dataset and can be downloaded on this website: https://www.kaggle.com/datasets/puneet6060/intel-image-classification
Here is the correct structure of the project: 
├─ dataset/
│ ├─ seg_train/
│ ├─ seg_test/
│ └─ seg_pred/
├─ saved_models/
├─ Reporting.ipynb
├─ README.md
├─ .gitignore

All the design choices are justified inside of the Reporting Notebook in the markdown cells.
