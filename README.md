# TensorFlow-Image-Models

This is a port of 
[PyTorch Image Models](https://github.com/rwightman/pytorch-image-models) to Tensorflow.

Work in progress...

## To do before 0.1.0

- [ ] Create git repo and upload to github
- [ ] Convert all other resnet models from timm
- [ ] pyproj.toml + python environment
- [ ] Unit tests
- [ ] Refactor resnet.py code
- [ ] Refactor utils/timm.py file
- [ ] Remove num_batches_tracked variables warning from conversion
- [ ] Black formatting
- [ ] Pre-commit hooks for black, flake8, etc. (see transformers repo)
- [ ] Complete README file
- [ ] Run unit tests on Github CI
- [ ] Publish package on PyPi

### ResNet model tracker

| Name | Total | Converted | Documented |
|---|---|---|---|
|ecaresnet | 6 + 2 pruned | 
|ig_resnext | 4 |
|resnet | 14 | 4 |
|resnet_blur | 1 |
|resnetrs | 7 |
|resnext | 3 |
|seresne{x}t | 5 |
|ssl_resne{x}t | 6 |
|swsl_resne{x}t | 6 |
|tv_resne{x}t | 5 |
|wide_resnet | 2 |



## Optional

- [ ] Run validation on imagenet to measure accuracy of converted models
- [ ] Ability to alter number of input channels
- [ ] Host converted models on google drive + download functionality
- [ ] Apply weight decay (either during build process or afterwards)