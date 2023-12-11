# Interactive SIM-Sync

[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://drive.google.com/file/d/13hYAlxOaywlPRbwMc5NLIQFd351Fowt9)


This repository contains a Python implementation of SIM-Sync: From Certifiably Optimal Synchronization over the 3D Similarity Group to Scene Reconstruction with Learned Depth, as described in the paper:

###  [Paper](https://arxiv.org/abs/2309.05184)

We introduce an noval approach for estimating camera trajectories and 3D scene structures from multiview image keypoints by utilizing a pretrained depth prediction network. The approach is validated through experiments on the TUM dataset.

![bundle_adjustment](https://drive.google.com/uc?export=view&id=10VHFFIzCttl6t5LkRXRZZ0uXv3dI9G1D)


## Installation

Please refer to the colab notebook for how to install the dependencies.

## Demo

Please refer to the colab notebook for how to run the demo.

## Folder Structure

```bash
SIM-Sync/
    utils/
    TEASER-plusplus/
    SimSyncRegularized.py
    pose_optimization.py
    TEASER_SIM_Sync.py
    pose_optimizer_tum_v2.py
    Dataset/
    visualization_results/

```

## Citation
If you find our work useful in your research, please consider citing:
```BibTeX
@article{yu2023sim,
  title={SIM-Sync: From Certifiably Optimal Synchronization over the 3D Similarity Group to Scene Reconstruction with Learned Depth},
  author={Yu, Xihang and Yang, Heng},
  journal={arXiv preprint arXiv:2309.05184},
  year={2023}
}
```

## Acknowledgements
We also thank the authors for releasing [robust-cvd](https://robust-cvd.github.io/), [PyTorch](https://github.com/erikwijmans/Pointnet2_PyTorch), [MOSEK](https://www.mosek.com/), [open3d](http://www.open3d.org/), [TEASER++](https://github.com/MIT-SPARK/TEASER-plusplus).
