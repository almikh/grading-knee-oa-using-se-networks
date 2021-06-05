# Using Squeeze-and-Excitation blocks to improve an accuracy of automatic knee osteoarthritis severity grading using convolutional neural networks

First, download and unpack oai224.zip/oai224_4.zip to dataset/ directory.

Dataset for 5 OA grades: https://drive.google.com/file/d/1TyuTBKSjnhcJK4a4DW7Hfs-6sbwXypV5/view?usp=sharing
Dataset for 4 OA grades: https://drive.google.com/file/d/1bL5GO6UCj84M9_LwPhAcb97ZEC0rpZ9F/view?usp=sharing

## Training (see train.ipynb)
Customize parameters in block `Changeable parameters` and run.

## Testing (see test.ipynb)
Customize parameters in block `Choose architecture and model checkpoint` and run.
You can download all trained models for all used architectures and random seeds by the links:
- classification for 5 OA grades: https://disk.yandex.ru/d/F5feQKmxwHPVxw
- classification for 4 OA grades: https://disk.yandex.ru/d/bIp34P1dD9FMuw

## Test ensembles (see test_ensemble.ipynb)
Customize parameters in block `Prepare ensemble parts` and run.