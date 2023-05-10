This is the official PyTorch implementation of three papers for pose-guided person image generation.

## Papers
- Region Semantics-Assisted GAN for Pose-Guided Person Image Generation (Accepted to CAAI)
- Mutually activated residual linear modeling GAN for pose-guided person image generation (Accepted to **Neurocomputing**)
- Precise Correspondence Enhanced GAN for Person Image Generation (Accepted to Neural Processing Letters)


## Requirements
- Python 3.7
- Pytorch 1.5+
- opencv
- tqdm
- lpips
- numpy
- scipy
- scikit-image
- pillow
- pandas
- tqdm
- dominate


## Datasets Preparation

Please follow [SelectionGAN](https://github.com/Ha0Tang/SelectionGAN/blob/master/person_transfer/README.md) to directly download both Market-1501 and DeepFashion datasets.


## Evaluation
We adopt SSIM, mask-SSIM, IS, mask-IS, and PCKh for evaluation of Market-1501. SSIM, IS, PCKh for DeepFashion. Please refer to [Pose-Transfer](https://github.com/tengteng95/Pose-Transfer) for more details.


## Training & Testing

We are organizing the code base. Code will be released soon...
