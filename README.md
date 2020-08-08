## Semi-Supervised Deep Learning For Melanoma Detection

### Dataset:

- [dataset.tar.gz](./dataset.tar.gz) contains the melanocytic nevus image dataset separated into three folders: `labeled`, `unlabeled` and `test`.
- The images are a pre-processed subset of color `32x32` pixel JPG files, taken from a dataset available through the Dataverse project.
- The naming convention for images in the `labeled` and `test` folders is as follows: each filename ends with either `*_0.jpg` or `*_1.jpg`, corresponding to a melanoma-negative or melanoma-positive image respectively.

The number of files is as follows:
```
Labeled: 200 (evenly split between melanoma positive and negative)
Test: 600 (also evenly split between melanoma positive and negative)
Unlabeled: 7018 (class distribution unknown)
```
