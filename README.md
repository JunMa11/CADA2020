# CADA2020
2nd place solution to the MICCAI CADA 2020 Segmentation Challenge.

## How to infer the testing set?

- Install the [nnU-Net](https://github.com/MIC-DKFZ/nnUNet)

- Download the trained models ([pw: rct8](https://pan.baidu.com/s/17pwM6Xt7S_5aRrbj7ePAqA)) and put them in `CADA2020/nnUNet-CADA/nnunet/TrainedModels/nnUNet/3d_fullres`

- Run

```python
nnUNet_predict -i INPUT_FOLDER -o OUTPUT_FOLDER -t Task201_CADA32G -m 3d_fullres
```



## Citation

