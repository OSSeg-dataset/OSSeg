# OSS-Seg

OSS-Seg is an Occluded Ship Segmentation dataset containing **5,504 high-resolution images** and **14,191 pixel-level annotated ship instances**. It focuses on challenging scenarios such as densely berthed ships in ports and ships sailing side by side, supporting research on instance segmentation under mutual occlusion, ambiguous boundaries, and large target-scale differences.

## Dataset Introduction

The dataset covers six categories: cargo boat, engineering ship, fishing boat, passenger ship, sailboat, and boat. The boat category includes ships that cannot be clearly identified or classified into the other five categories. All images are annotated using the ISAT tool.

OSS-Seg consists of **4,702 real-world images** and **802 occlusion-augmented images**. The training, validation, and test sets follow a **7:1:2 split**, with Copy-Paste augmented images used only in the training set.

## Dataset Download

The complete OSS-Seg dataset is available in the [GitHub Releases](https://github.com/OSSeg-dataset/OSSeg/releases) section.

The dataset is provided in two ZIP files:

- **images.zip**: Contains the ship images.
- **labels.zip**: Contains the corresponding instance segmentation annotations.

Download and extract both files while preserving their original directory structures.
