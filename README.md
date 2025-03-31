# EDSRPlus

A simple PyTorch library for super-resolution, built on top of the EDSR model with enhanced residual blocks.

## Overview

`EDSRPlus` is a lightweight extension of the EDSR (Enhanced Deep Super-Resolution) model. It adds simple yet effective improvements like attention and multi-scale residual blocks to boost image upscaling quality.

## Installation

1. Clone the repo:
   ```bash
   git clone https://github.com/NQTUS/EDSRPlus.git
   cd EDSRPlus
   ```

2. Install requirements:
   ```bash
   pip install torch torchvision torchsr numpy pillow
   ```

## Requirements
- Python 3.8+
- PyTorch
- Torchvision
- TorchSR (for EDSR)
- NumPy, PIL

## Structure
```
EDSRPlus/
├── EDSR_plus_attention.ipynb  
├── model_weights.pth          # Pre-trained weights
├── Images/
│   ├── output_1.png          
│   ├── output_2.png          
│   └── output_3.png          
└── README.md                  
```

## Results

Here are some example outputs. Each image contains three columns: the low-resolution input (100x150), the high-resolution target (400x600), and the predicted high-resolution image (400x600):

### Example Output
| Example Image                                      |
|----------------------------------------------------|
| ![Example 1](Images/output_1.png)                 |
| ![Example 2](Images/output_2.png)                 |
| ![Example 3](Images/output_3.png)                 |

These images are generated using the plotting code in `EDSR_plus_attention.ipynb`.

## Credits
Based on the [EDSR model](https://arxiv.org/abs/1707.02921) by Lim et al.
```

