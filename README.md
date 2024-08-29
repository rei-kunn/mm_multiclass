# mm_multiclass

## Overview
This repository contains the code for downloading the images using <code>bing-image-downloader</code> api.

The dataset is a sample data collection for multiclassification task for burmese language containing only 30 images as of August 29th 2024. The images are relating to Myanmar Landmark and Cultures.

The dataset is uploaded on [HuggingFace](https://huggingface.co/datasets/AggaMin/mm_multiclass_dataset).

The status of this project is <code>on-going</code>.

## Usage

```python
from datasets import load_dataset

dataset = load_dataset("AggaMin/mm_multiclass_dataset")
```

## Dataset Details
```
dataset_info:
  features:
  - name: image
    dtype: image
  - name: label
    dtype:
      class_label:
        names:
          '0': အထင်ကရနေရာများ
          '1': ရိုးရာအဝတ်အစားမျး
          '2': မြန်မာ့ အားကစား
```
