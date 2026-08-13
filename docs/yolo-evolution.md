<div align="center">

<!-- ===== HEADER BANNER ===== -->
<img src="https://capsule-render.vercel.app/api?type=waving&color=0:2563eb,50:7c3aed,100:00CCBB&height=200&section=header&text=Evolution%20of%20the%20YOLO%20Algorithm&fontSize=34&fontColor=ffffff&fontAlignY=42&desc=From%20YOLOv1%20to%20YOLO26%20%E2%80%A2%20A%20Technical%20and%20Bibliometric%20Review&descSize=16&descAlignY=64&animation=fadeIn" width="100%" alt="YOLO Evolution banner" />

# An Overview of the Evolution of the YOLO Algorithm

**Frédéric Mirindi** &nbsp;&middot;&nbsp; **Derrick Mirindi** &nbsp;&middot;&nbsp; **David Sinkhonde**

<p>
  <img src="https://img.shields.io/badge/Venue-IEEE%20DLCV%202026-2563eb?style=for-the-badge" alt="venue" />
  <img src="https://img.shields.io/badge/Publisher-IEEE-00629B?style=for-the-badge&logo=ieee&logoColor=white" alt="publisher" />
  <img src="https://img.shields.io/badge/Field-Computer%20Vision-7c3aed?style=for-the-badge" alt="field" />
  <img src="https://img.shields.io/badge/Topic-Object%20Detection-00CCBB?style=for-the-badge" alt="topic" />
</p>

[**&#8592; Back to Profile**](../README.md)

</div>

---

## 📄 Abstract

> Object detection is a central task in artificial intelligence, and You Only Look Once (YOLO) remains one of its most influential one-stage detection frameworks. This paper reviews the evolution of YOLO from YOLOv1 through YOLO26. It emphasizes the technical mechanisms that distinguish successive versions, such as backbone design, neck-based feature fusion, detection-head formulation, anchor-based and anchor-free prediction, label assignment, loss functions, postprocess design, and deployment optimization. It also summarizes key mathematical concepts used in YOLO detection. These concepts cover bounding-box prediction, confidence scores, intersection-over-union metrics, non-maximum suppression, and class-imbalance treatment. In addition, the paper presents a bibliometric assessment based on Dimensions.ai and VOSviewer. This assessment identifies growth across major research fields, institutional collaboration networks, and country-level publication patterns. Overall, the review highlights how YOLO methods have expanded from single-task object detection toward segmentation, pose estimation, oriented bounding boxes, tracking, and edge inference.

---

## 🧩 Figure 1 &mdash; Detection Pipeline

<div align="center">
  <img src="./images/yolo_architecture.png" width="85%" alt="YOLO detection pipeline: feature extraction, multi-scale fusion, dense prediction, decoding and NMS" />
</div>

<p align="center"><em>Fig. 1. (a) Feature extraction and multi-scale feature fusion via backbone (Conv, CSP/C2f, SPPF) and FPN + PAN neck producing P3/P4/P5 feature maps. (b) Dense prediction, decoding, non-maximum suppression (NMS), and final detections.</em></p>

---

## 🗓️ Figure 2 &mdash; Model Evolution Timeline

<div align="center">
  <img src="./images/yolo_evolution_timeline.png" width="90%" alt="Timeline of YOLO model evolution from YOLOv1 (2015) toward edge-optimized, deployment-ready versions (2026)" />
</div>

<p align="center"><em>Fig. 2. Overview of YOLO model evolution from early single-stage detection toward more efficient and deployment-ready versions.</em></p>

---

## 📌 Key Themes

| Theme | Description |
| :--- | :--- |
| 🏗️ **Backbone design** | Feature extractors from Darknet to CSP/C2f blocks |
| 🔗 **Neck / feature fusion** | FPN + PAN multi-scale aggregation |
| 🎯 **Detection head** | Anchor-based vs. anchor-free prediction |
| 🧠 **Label assignment** | Static and dynamic matching strategies |
| 📉 **Loss functions** | Box regression, objectness, and classification objectives |
| ⚡ **Deployment** | NMS-free, edge-optimized, and CPU-efficient inference |

---

## 📚 Citation

> F. Mirindi, D. Mirindi, and D. Sinkhonde, *"An Overview of the Evolution of the YOLO Algorithm,"* in **2026 IEEE 3rd International Conference on Computer Vision and Deep Learning (DLCV)**, IEEE, 2026.

<div align="center">

[**&#8592; Back to Profile**](../README.md)

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:00CCBB,50:7c3aed,100:2563eb&height=100&section=footer" width="100%" alt="footer" />

</div>
