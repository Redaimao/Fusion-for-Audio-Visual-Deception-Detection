# Fusion-for-Audio-Visual-Deception-Detection

This is the Plug-in Audio-Visual Fusion (PAVF) code for paper [Audio-Visual Deception Detection: DOLOS Dataset and Parameter-Efficient
Crossmodal Learning](https://arxiv.org/abs/2303.12745) published at ICCV 2023.

This repo is for further exploration for better fusion method for deception detection tasks.

## DOLOS Dataset

**DOLOS** is a gameshow based deception dataset. The DOLOS dataset can be downloaded from [ROSE Lab, NTU](https://rose1.ntu.edu.sg/dataset/DOLOS/). 

Please refer to [DOLOS and Code](https://github.com/NMS05/Audio-Visual-Deception-Detection-DOLOS-Dataset-and-Parameter-Efficient-Crossmodal-Learning/tree/main) to understand the full training process.

## Testing the fusion module
```bash
python fusion_model.py
```
## Please cite the paper if you find it useful
```
@inproceedings{guo2023audio,
  title={Audio-visual deception detection: Dolos dataset and parameter-efficient crossmodal learning},
  author={Guo, Xiaobao and Selvaraj, Nithish Muthuchamy and Yu, Zitong and Kong, Adams Wai-Kin and Shen, Bingquan and Kot, Alex},
  booktitle={Proceedings of the IEEE/CVF International Conference on Computer Vision},
  pages={22135--22145},
  year={2023}
}
```

