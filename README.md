# MindSpore Vision Models

## Introduction

**MS_Vision** is an open source repository, which focus on the computer vision models based on MindSpore. MS_Vision is a collection of CV models, layers, utilities, optimizers, schedulers, data-loaders / augmentations, and reference training / validation scripts that aim to pull together a wide variety of SOTA models. All source material is acknowledged via links to github, arxiv papers, etc in the README. Please let me know if I missed anything.

The main branch works with **MindSpore 1.3.0+**.

### Major features

- Various backbones and pretrained models
- Large-scale training configs

## Model zoo

<details open>
<summary>Supported models</summary>

- [x] [CTSDG](https://github.com/kingcong/ms_vision/tree/main/CTSDG-MS) 
  - [Paper](https://arxiv.org/pdf/2108.09760.pdf): Image Inpainting via Conditional Texture and Structure Dual Generation 
- [x] [Fat-DeepFFM](https://github.com/kingcong/ms_vision/tree/main/Fat-DeepFFM-MS)
  - [Paper](https://arxiv.org/abs/1905.06336): FAT-DeepFFM: Field Attentive Deep Field-aware Factorization Machine
- [x] [HiFaceGAN](https://github.com/kingcong/ms_vision/tree/main/HiFaceGAN-MS)
  - [Paper](https://arxiv.org/pdf/2005.05005.pdf): HiFaceGAN: Face Renovation via Collaborative Suppression and Replenishment
- [x] [IndexNet](https://github.com/kingcong/ms_vision/tree/main/IndexNet-MS)
  - [Paper](https://openaccess.thecvf.com/content_ICCV_2019/papers/Lu_Indices_Matter_Learning_to_Index_for_Deep_Image_Matting_ICCV_2019_paper.pdf):  Indices Matter: Learning to Index for Deep Image Matting
- [x] [flownet2](https://github.com/kingcong/ms_vision/tree/main/flownet2-MS)
  - [Paper](https://arxiv.org/abs/1612.01925 ): FlowNet 2.0: Evolution of Optical Flow Estimation with Deep Networks
- [x] [ktnet](https://github.com/kingcong/ms_vision/tree/main/ktnet-MS)
  - [Paper](https://www.aclweb.org/anthology/P19-1226/): Enhancing Pre-Trained Language Representations with Rich Knowledge for Machine Reading Comprehension
- [x] [nnUNet](https://github.com/kingcong/ms_vision/tree/main/nnUNet-MS)
  - [Paper](https://arxiv.org/abs/1904.08128v2): nnU-Net: a self-configuring method for deep learning-based biomedical image segmentation
- [x] [slowfast](https://github.com/kingcong/ms_vision/tree/main/slowfast-MS)
  - [Paper](https://arxiv.org/abs/1812.03982): SlowFast Networks for Video Recognition
- [x] [snn_mlp](https://github.com/kingcong/ms_vision/tree/main/snn_mlp-MS)
  - [Paper](https://arxiv.org/pdf/2203.14679.pdf): Brain-inspired Multilayer Perceptron with Spiking Neurons
- [x] [trn](https://github.com/kingcong/ms_vision/tree/main/trn-MS)
  - [Paper](https://arxiv.org/pdf/1711.08496v2.pdf): Temporal Relational Reasoning in Videos

</details>

## Citation

If you find this project useful in your research, please consider cite:

```BibTeX
@misc{2022ms_vision,
    title={MindSpore Vision Models},
    author={MS_Vision Contributors},
    howpublished = {\url{https://github.com/kingcong/ms_vision}},
    year={2022}
}
```

## License

This project is released under the [Apache 2.0 license](LICENSE).
