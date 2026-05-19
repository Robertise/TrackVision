# TrackVision

> **Real-Time Multi-Object Tracking with Re-Identification**
>
> Computer Vision pipeline for detection, tracking, and re-identification in video streams.

![Python](https://img.shields.io/badge/Python-3.10+-blue?logo=python)
![PyTorch](https://img.shields.io/badge/PyTorch-2.0+-red?logo=pytorch)
![License](https://img.shields.io/badge/License-MIT-green)
![Status](https://img.shields.io/badge/Status-In%20Development-yellow)

---

## Overview

TrackVision is an end-to-end Computer Vision pipeline that combines multiple components to solve multi-object tracking and re-identification challenges in video data.

### Project Components

- **Detection Module** — Object localization in video frames
- **Tracking Module** — Maintaining consistent identities across frames
- **Re-ID Module** — Re-identifying objects after occlusion or interruption
- **Evaluation Framework** — Benchmarking against MOT standards
- **Demo Interface** — Interactive visualization and testing

---


## Technology Stack

| Component | Technology | Purpose |
|-----------|-----------|---------|
| Deep Learning | PyTorch | Computation framework |
| Detection | YOLOv8 (Ultralytics) | Object detection |
| Tracking | ByteTrack | Multi-object association |
| Re-ID | OSNet (torchreid) | Appearance matching |
| CV | OpenCV | Video I/O & visualization |
| Evaluation | TrackEval | MOT metrics |
| Web Demo | Gradio | Interactive interface |
| Environment | Conda/venv | Python environment |

---

## Benchmark Metrics

Standard MOT Challenge metrics used for evaluation:

| Metric | Meaning | Value Type |
|--------|---------|-----------|
| **MOTA** | Multi-Object Tracking Accuracy | Higher is better |
| **HOTA** | Higher-Order Tracking Accuracy | Higher is better |
| **IDF1** | ID F1 Score | Higher is better |
| **FPS** | Frames Per Second | Higher is better |
| **ID Sw.** | Identity Switches | Lower is better |

---

## License

MIT License — See [LICENSE](LICENSE) file

---

*TrackVision — Computer Vision Pipelines for Object Tracking*
