# DiversifyAnalysis
## Overview
This repo reproduces the experiments from paper "[OUT-OF-DISTRIBUTION REPRESENTATION LEARNING FOR TIME SERIES CLASSIFICATION](https://openreview.net/pdf?id=gUZWOE42l6Q)"

## How-to
### 1. preprocess
Download and prepare your datasets by:
``` python 
python prepare_dataset.py --data_dir ./data/ --dataset EMG
```
if executed successfully, dataset EMG will be saved to ./data/emg

### 2. train

### 3. evaluate

## References
```
@inproceedings{lu2022out,
  title={Out-of-distribution Representation Learning for Time Series Classification},
  author={Lu, Wang and Wang, Jindong and Sun, Xinwei and Chen, Yiqiang and Xie, Xing},
  booktitle={International Conference on Learning Representations},
  year={2023}
}
```
