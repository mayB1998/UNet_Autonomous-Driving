 **# Unet for Autonomous Driving**

**## Overview**

This repository contains the code and resources for implementing a Unet architecture for autonomous driving tasks. The goal is to leverage Unet's capabilities in semantic segmentation to enhance the perception and decision-making abilities of a self-driving vehicle.


**## Architecture**
![](https://lmb.informatik.uni-freiburg.de/people/ronneber/u-net/u-net-architecture.png)

**## Key Features**

* Implementation of Unet architecture in PyTorch
* Training and evaluation on autonomous driving - Cityscapes Dataset
* Exploration of real-time inference for on-board deployment

**## Setup**

1. Clone the repository:

   ```bash
   git clone https://github.com/mayB1998/UNet_Autonomous-Driving.git
   ```

2. Install dependencies:

   ```bash
   pip install -r requirements.txt
   ```

**## Usage**

1. Download dataset: 
2. Train the model: (Provide example training command)
3. Evaluate performance: (Provide example evaluation command)
4. Visualize results: (Provide instructions on visualizing segmentation outputs)

**## Project Structure**

```
unet-autonomous-driving/
├── README.md                        <-- This file
├── requirements.txt                 <-- List of dependencies
├── data/                            <-- Datasets
│   ├── cityscapes/                  <-- Example dataset
│   └── kitti/                       <-- Example dataset
├── models/                          <-- Unet model architecture
│   └── unet.py                      <-- Main Unet model file
├── training/                        <-- Training scripts
│   ├── train.py                     <-- Training script
│   └── evaluate.py                  <-- Evaluation script
├── utils/                           <-- Utility functions
│   ├── data_loader.py               <-- Data loading functions
│   └── visualization.py             <-- Visualization functions
└── results/                         <-- Experiment results
```

**## results**

![Drivable_area-output](images/Drivable_area-output.png)
The image above shows the image and the corresponding label for the Drivable area

![output_compare](images/output.png)
The above image shows the output achieved and the corresponding label, along with the image for the segemantation task performed with the Unet architecture

![validation_training_curve](images/validation_training_curve.png)

Validation and Training curve for the model trained

**## Additional Information**

* Datasets used:  
* Framework:
* Hardware requirements:         
* Expected performance metrics:
* Future work:                   
