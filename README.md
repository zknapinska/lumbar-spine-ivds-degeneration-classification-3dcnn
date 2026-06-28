# IVD Degeneration 3D CNN

PyTorch implementation of a multi-task 3D convolutional neural network for automated classification of lumbar intervertebral disc degeneration and associated degenerative changes from MRI.

## Overview

This repository contains the code used to develop and evaluate a multi-task deep learning model for the automated assessment of lumbar spine degeneration on sagittal MRI. The model predicts:

* Pfirrmann grade (ordinal classification)
* Modic changes
* Endplate changes
* Disc herniation
* Disc bulging
* Disc narrowing
* Spondylolisthesis

The network is based on a 3D ResNet architecture and was trained using regions of interest extracted from the SPIDER lumbar spine MRI dataset.

## Repository contents

* `IVDs-research-project_classification.ipynb` – complete notebook containing data preparation, preprocessing, model training, evaluation, and Grad-CAM visualization.
* `requirements.txt` – Python package requirements.

## Dataset

This repository does **not** include the MRI data.

The experiments were performed using the **SPIDER** lumbar spine MRI dataset. Please obtain the dataset from the original authors in accordance with their distribution policy.

## Installation

Clone the repository:

```bash
git clone https://github.com/zknapinska/lumbar-spine-ivds-degeneration-classification-3dcnn.git
cd lumbar-spine-ivds-degeneration-classification-3dcnn
```

Install the required packages:

```bash
pip install -r requirements.txt
```

## Running the project

Open the notebook:

```text
IVDs-research-project_classification.ipynb
```

and execute the cells sequentially.

## Citation

If you use this code in your research, please cite our publication:

> *Citation will be added after publication.*

## License

This project is released under the MIT License.

