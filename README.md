# mm_multiclass

## Overview
This repository contains the code for downloading the images using <code>bing-image-downloader</code> api.

The dataset is a sample data collection for multiclassification task for burmese language containing only 419 images as of August 29th 2024. The images are relating to Myanmar Landmark and Cultures.

The dataset is uploaded on [HuggingFace](https://huggingface.co/datasets/AggaMin/mm_multiclassification_dataset).

The status of this project is <code>on-going</code>.

## Usage

```python
from datasets import load_dataset

dataset = load_dataset("AggaMin/mm_multiclassification_dataset")
```

## Dataset Details
```shell
dataset_info:
  features:
  - name: image
    dtype: image
  - name: label
    dtype:
        class_label:
          names:
            '0': ရိုးရာအဝတ်အစားများ
            '1': လက်ဝှေ့
            '2': အာနန္ဒာဘုရား
            '3': မုန့်ဟင်းခါး
```
