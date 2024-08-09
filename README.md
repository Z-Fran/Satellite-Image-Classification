# Satellite-Image-Classification

## Introduction

Train AI models on satellite image dataset to classify different types of land.

## How to run
Run [`train.ipynb`](./train.ipynb) to train models on satellite image dataset.

## Dataset

Segment satellite imagery into small blocks, and annotate type labels of blocks.

### Demo dataset

We provide a small [dataset](./dataset.zip) in the repository. You can directly unzip it and see the following folder structure.

```
Satellite-Image-Classification/
├── dataset
|   ├── industry
|   |   ├── xxx.jpg
|   |   └── ...
|   ├── agriculture
|   └── residence
```

### Create your own dataset

1. Get a satellite imagery in `.tiff` format.
2. Use [Global Mapper](https://www.bluemarblegeo.com/global-mapper/) to split the `tiff` file into small blocks in `.jpg` format.
3. Manually classify these images and create a folder structure like above.

## Models

Models are listed in the folder `models`, which is imported from [pytorch-cifar
](https://github.com/kuangliu/pytorch-cifar).

## References

- [pytorch-cifar
](https://github.com/kuangliu/pytorch-cifar)
