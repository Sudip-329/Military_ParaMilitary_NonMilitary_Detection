# Military_ParaMilitary_NonMilitary_Detection

## Overview

This repository contains code and resources for detecting and classifying images into Military, Paramilitary, and Non-Military categories. The project leverages deep learning and computer vision techniques to build an automated classification system suitable for security and defense applications.

![Detection Output](detected.png)

---
## Features

- Deep learning model implementations using YOLO variants (YOLOv5 Nano, YOLO8 Nano, etc.)
- Dataset preprocessing and augmentation pipelines
- Training and evaluation notebooks
- Scripts for model inference and deployment preparation
- ---

## Repository Structure

- `Final_YOLO5_NANO_MODEL_IMPLEMENTATION.ipynb` - Notebook with YOLOv5 Nano model implementation and training
- `YOLO11_NANO_MODEL_IMPLEMENTATION.ipynb` - Implementation of a YOLO variant model
- `YOLO11_SMALL_MODEL_IMPLEMENTATION.ipynb` - Smaller variant of YOLO11 model
- `YOLO8_NANO_MODEL_IMPLEMENTATION.ipynb` - YOLOv8 Nano implementation
- `YOLO8_SMALL_MODEL_IMPLEMENTATION.ipynb` - Smaller YOLOv8 model implementation
- `.gitattributes` - Git attributes configuration file
- `README.md` - This file

---
## Installation

To set up the environment for running this project, install necessary Python packages as required by the notebooks (check individual notebooks for dependencies).

Example installation command (adjust according to requirements):




Ensure you have a GPU-enabled setup for faster training and inference.
---
## Usage

1. Prepare your dataset with images labeled into Military, Paramilitary, and Non-Military classes.
2. Use the provided notebooks to preprocess data, train models, and evaluate their performance.
3. Run inference on new images using model checkpoints produced after training.
4. Adjust model parameters, augmentations, and architectures as needed to improve accuracy.
---
## Dataset

The dataset consists of images categorized into three classes representing Military, Paramilitary, and Non-Military entities. Details regarding dataset collection and labeling should be referred to inside the notebooks.

-**Dataset Link:** [**Click Here**](https://www.kaggle.com/datasets/sudipchakrabarty/trinet/data)
---

## 📄 Citation
If you find our work useful for your research, please consider citing our paper.

-**Paper Link:** [**Click Here**](https://ieeexplore.ieee.org/document/11136231)

-**Tracking Video Output Link:** [**Click Here**](https://youtube.com/shorts/8tXOiiy-Zkg?si=Esk4H2l0KG2gTvEI)

### BibTeX
```bibtex
@INPROCEEDINGS{11136231,
  author={Chakrabarty, Sudip and Bishwas, Pappu and Chakraborty, Sorup and Sarker, Ovijit},
  booktitle={2025 International Conference on Intelligent Computing and Knowledge Extraction (ICICKE)}, 
  title={Advancing Defense and Security with Deep Learning-Based Detection and Tracking}, 
  year={2025},
  volume={},
  number={},
  pages={1-6},
  keywords={YOLO;Training;Accuracy;Surveillance;Computational modeling;Weapons;Real-time systems;Personnel;Security;Meteorology;Real-time Object Detection;YOLO Architecture;Multi-object Tracking;Surveillance Systems;TriNet Dataset;Deep Learning},
  doi={10.1109/ICICKE65317.2025.11136231}}

```
## Contributing
---
Contributions are welcome! Please fork this repository and open a pull request with your proposed changes or enhancements.

## License

This project is open source and available under the MIT License.


