# SWIR-HDR Code

# SWIR-HDR Dataset

This repository is the official release page for the SWIR-HDR dataset proposed in the paper:

**Learning SWIR HDR from Multi-Exposure Sequences: A Real-World Dataset and End-to-End Reconstruction Network**

The complete dataset will be publicly released upon acceptance of the paper.

## Dataset Description

The SWIR-HDR dataset is designed for short-wave infrared (SWIR) high dynamic range reconstruction from multi-exposure image sequences. The dataset was captured using an InGaAs SWIR camera under indoor and outdoor real-world scenes.

Each released training/testing sample will contain:

- five SWIR input images captured with different exposure times;
- one corresponding HDR ground truth image;
- exposure-time metadata;
- the official training/testing split used in the paper.

## Dataset Split

The dataset contains 529 multi-exposure image sequences in total:

- 436 sequences for training;
- 93 sequences for testing.

## Release Plan

The dataset is currently being organized and checked for public release. The complete data, metadata, and split files will be uploaded to this repository upon acceptance of the paper.

## Citation

If you use this dataset, please cite our paper:

```bibtex
@article{swirhdr2026,
  title={Learning SWIR HDR from Multi-Exposure Sequences: A Real-World Dataset and End-to-End Reconstruction Network},
  author={Huang, Tengda and others},
  journal={Infrared Physics and Technology},
  year={2026}
}
