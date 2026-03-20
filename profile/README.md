# RT-DETRs: A Family of Real-time End-to-End Detectors

Welcome to the official community tracker for the **RT-DETR (Real-Time DEtection TRansformer)** family! This repository is dedicated to curating the exciting advancements and follow-up works based on the original RT-DETR, the first real-time end-to-end detector based on the Transformer architecture.

## 🚀 What is RT-DETR?

RT-DETR is a groundbreaking object detection model that, for the **first time, brings real-time performance to DETR**.

Traditionally, DETR (DEtection TRansformer) models were known for their high accuracy and elegant, non-NMS (Non-Maximum Suppression) pipeline, but they suffered from slow inference speeds. RT-DETR successfully bridges this gap, establishing itself as the **first real-time end-to-end Transformer detector**, providing a powerful and efficient solution that rivals the performance of top-tier YOLO models.

### Architecture

The core architecture of RT-DETR features a hybrid encoder and a query selection mechanism, enabling it to process multi-scale features efficiently while maintaining the end-to-end simplicity of DETR.

![RT-DETR Architecture](../assets/rtdetr.png)


## 🌳 The RT-DETR Family

Since the release of the original paper, the research community has enthusiastically embraced and built upon the RT-DETR framework. Thanks to these collective efforts, the RT-DETR family is rapidly growing, with numerous works enhancing its speed, accuracy, and capabilities.

This repository aims to track these valuable contributions. The evolving family includes:

> [**DETRs Beat YOLOs on Real-time Object Detection**](https://arxiv.org/abs/2304.08069) (The foundational RT-DETR paper) [CVPR 2024] <br>
> Yian Zhao<sup>* </sup>, Wenyu Lv<sup>* </sup>, Shangliang Xu, Jinman Wei, Guanzhong Wang, Qingqing Dang, Yi Liu, Jie Chen <br>
[![github](https://img.shields.io/badge/-Github-black?logo=github)](https://github.com/lyuwenyu/RT-DETR)  [![arXiv](https://img.shields.io/badge/Arxiv-2304.08069-b31b1b.svg?logo=arXiv)](https://arxiv.org/abs/2304.08069) <br>

> [**RT-DETRv2: Improved Baseline with Bag-of-Freebies for Real-Time Detection Transformer**](https://arxiv.org/abs/2407.17140) <br>
> Wenyu Lv, Yian Zhao, Qinyao Chang, Kui Huang, Guanzhong Wang, Yi Liu <br>
[![github](https://img.shields.io/badge/-Github-black?logo=github)](https://github.com/lyuwenyu/RT-DETR)  [![arXiv](https://img.shields.io/badge/Arxiv-2407.17140-b31b1b.svg?logo=arXiv)](https://arxiv.org/abs/2407.17140) <br>

> [**RT-DETRv3: Real-time End-to-End Object Detection with Hierarchical Dense Positive Supervision**](https://arxiv.org/abs/2409.08475) [WACV 2025 Oral] <br>
> Shuo Wang<sup>* </sup>, Chunlong Xia<sup>* </sup>, Feng Lv, Yifeng Shi <br>
[![github](https://img.shields.io/badge/-Github-black?logo=github)](https://github.com/clxia12/RT-DETRv3)  [![arXiv](https://img.shields.io/badge/Arxiv-2409.08475-b31b1b.svg?logo=arXiv)](https://arxiv.org/abs/2409.08475) <br>

> [**D-FINE: Redefine Regression Task of DETRs as Fine-grained Distribution Refinement**](https://arxiv.org/abs/2410.13842) [ICLR 2025 Spotlight] <br>
> Yansong Peng, Hebei Li, Peixi Wu, Yueyi Zhang, Xiaoyan Sun, Feng Wu <br>
[![github](https://img.shields.io/badge/-Github-black?logo=github)](https://github.com/Peterande/D-FINE)  [![arXiv](https://img.shields.io/badge/Arxiv-2410.13842-b31b1b.svg?logo=arXiv)](https://arxiv.org/abs/2410.13842) <br>


> [**DEIM: DETR with Improved Matching for Fast Convergence**](https://arxiv.org/abs/2412.04234) [CVPR 2025] <br>
> Shihua Huang, Zhichao Lu, Xiaodong Cun, Yongjun Yu, Xiao Zhou, Xi Shen <br>
[![github](https://img.shields.io/badge/-Github-black?logo=github)](https://github.com/Intellindust-AI-Lab/DEIM)  [![arXiv](https://img.shields.io/badge/Arxiv-2412.04234-b31b1b.svg?logo=arXiv)](https://arxiv.org/abs/2412.04234) <br>

> [**Real-Time Object Detection Meets DINOv3**](https://arxiv.org/abs/2509.20787) <br>
> Shihua Huang, Yongjie Hou, Longfei Liu, Xuanlong Yu, Xi Shen <br>
[![github](https://img.shields.io/badge/-Github-black?logo=github)](https://github.com/Intellindust-AI-Lab/DEIMv2)  [![arXiv](https://img.shields.io/badge/Arxiv-2509.20787-b31b1b.svg?logo=arXiv)](https://arxiv.org/abs/2509.20787) <br>


> [**RT-DETRv4: Painlessly Furthering Real-Time Object Detection with Vision Foundation Models**](https://arxiv.org/abs/2510.25257) <br>
> Zijun Liao<sup>* </sup>, Yian Zhao<sup>* </sup>, Xin Shan, Yu Yan, Chang Liu, Lei Lu, Xiangyang Ji, Jie Chen <br>
[![github](https://img.shields.io/badge/-Github-black?logo=github)](https://github.com/RT-DETRs/RT-DETRv4)  [![arXiv](https://img.shields.io/badge/Arxiv-2510.25257-b31b1b.svg?logo=arXiv)](https://arxiv.org/abs/2510.25257) <br>


> [**EdgeCrafter: Compact ViTs for Edge Dense Prediction via Task-Specialized Distillation**](https://arxiv.org/abs/2603.18739) <br>
> Longfei Liu<sup>* </sup>, Yongjie Hou<sup>* </sup>, Yang Li<sup>* </sup>, Qirui Wang<sup>* </sup>, Youyang Sha, Yongjun Yu, Yinzhi Wang, Peizhe Ru, Xuanlong Yu, Xi Shen <br>
[![github](https://img.shields.io/badge/-Github-black?logo=github)](https://github.com/Intellindust-AI-Lab/EdgeCrafter)  [![arXiv](https://img.shields.io/badge/Arxiv-2603.18739-b31b1b.svg?logo=arXiv)](https://arxiv.org/abs/2603.18739) <br>


*(We will update this list as new contributions are published. If you have a work that belongs here, please open a pull request!)*

## 🔮 Future Outlook

The journey of real-time, end-to-end object detection is still in its exciting early stages. The success of the RT-DETR family proves that Transformer-based detectors are a dominant force in the making.

We look forward to seeing more innovations from the community. Let's work together to push the boundaries of real-time detection and build the next generation of intelligent systems!

---

*Contributions are welcome! Feel free to submit issues or pull requests to help keep this repository up-to-date.*
