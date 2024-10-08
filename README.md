# SynthMoCap Datasets

This repo accompanies the paper [Look Ma, no markers: holistic performance capture without the hassle](https://aka.ms/SynthMoCap) which appeared in ACM Transaction on Graphics and was presented at SIGGRAPH Asia 2024.
The repo includes download instructions for the synthetic datasets used in the paper. For detailed information about the dataset contents and download instructions see [DATASETS.md](DATASETS.md).

## SynthBody Dataset

![body_data](docs/img/body-data.jpg)

The SynthBody dataset includes the following:

- RGB body images
- 2D and 3D skeletal landmarks
- Segmentation masks
- SMPL-H pose parameters
- SMPL-H shape parameters
- Camera parameters

## SynthFace Dataset

![face_data](docs/img/face-data.jpg)

The SynthFace dataset includes the following:

- RGB face images
- Sparse 2D landmarks
- Segmentation masks
- Camera parameters
- Head pose
- Eye gaze

## SynthHand Dataset

![hand_data](docs/img/hand-data.jpg)

The SynthHand dataset includes the following:

- RGB hand images (left hand only)
- 2D and 3D skeletal landmarks
- SMPL-H pose parameters
- SMPL-H shape parameters
- Camera parameters

## Citation

If you use any of the datasets in your research, please cite the following [paper](https://aka.ms/SynthMoCap):

```bibtex
@article{hewitt2024look,
  title={Look Ma, no markers: holistic performance capture without the hassle},
  author={Hewitt, Charlie and Saleh, Fatemeh and Aliakbarian, Sadegh and Petikam, Lohit and Rezaeifar, Shideh and Florentin, Louis and Hosenie, Zafiirah and Cashman, Thomas J and Valentin, Julien and Cosker, Darren and Baltru\v{s}aitis, Tadas},
  journal={ACM Transactions on Graphics (TOG)},
  volume={36},
  number={6},
  year={2024},
  publisher={ACM New York, NY, USA},
  articleno={235},
  numpages={12},
}
```
