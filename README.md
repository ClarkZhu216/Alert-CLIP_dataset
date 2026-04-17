# Alert-CLIP_dataset
Annotations and metadata for the Video Anomaly Dataset with Grounded Text Annotations (VAGTA).

# VAGTA

**VAGTA** (Video Anomaly Dataset with Grounded Text Annotations) is a multi-granularity video anomaly dataset for training and evaluating vision-language models for video anomaly detection (VAD).

This repository provides the annotations and metadata of VAGTA, which is constructed by re-annotating videos from the official splits of **UCF-Crime** and **MSAD**.

## Overview

VAGTA contains **4,212 curated clips** in total, including:

- **3,726 training clips**
- **486 test clips**

The training split contains:

- **2,585 segmented normal clips**
- **1,141 abnormal clips**

Each clip is equipped with multi-granularity annotations, including:

- **Global captions**
- **Region-level captions**
- **Bounding boxes for abnormal regions**
- **Hard-negative captions**

These annotations are designed to support multi-level vision-language alignment for video anomaly detection.

## Important Note

This repository currently provides:

- annotation files
- caption files
- split files
- metadata / index files
- documentation

**Raw videos are not redistributed in this repository.**  
Please obtain the original videos from the official sources of **UCF-Crime** and **MSAD**, and use the provided metadata to align them with VAGTA annotations.


