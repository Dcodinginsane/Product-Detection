## Introduction

A state of art detector for densely packed scenes dataset SKU-110K.



## Installation

1. To clone this project to your own device.

   ```
   git clone https://github.com/Media-Smart/SKU110K-DenseDet.git
   ```

2. Please refer to [INSTALL.md](docs/INSTALL.md) for installation and dataset preparation.

3. Click [here](https://drive.google.com/file/d/1XM8OzRdcbDbSrvlcMgJsFX76lBmdN2Td/view?usp=sharing) to download the weights. 


### Test

```shell
python tools/test.py configs/SKU_fusion_bfp_x101_32x4d.py \
    ${YOUR_WEIGHT_PATH} \
    --show
```

### Train

```shell
python tools/train.py configs/SKU_fusion_bfp_x101_32x4d.py
```

## Performance

The performance applied on SKU-110k of our best solution.

|            | mAP   | AP@50  | AP@75 |
| ---------- | ----  | -----  | ----- |
| Val Set    | 58.0% | 92.0%  | 66.5% |
| Test Set 1 | 58.7% | 92.9%  | 67.3% |









