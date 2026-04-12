# LiteBounD
LiteBounD: Lightweight Boundary-Guided Distillation for Polyp Segmentation using Vision Foundation Models

## LiteBounD: Lightweight Boundary-Guided Distillation for Polyp Segmentation

This repository contains the official implementation of our IJCNN/WCCI accepted paper:

**"LiteBounD: A Lightweight Boundary-Guided Distillation Framework for Polyp Segmentation"**

### 🔍 Overview
Automated polyp segmentation plays a crucial role in early colorectal cancer detection. However, it remains challenging due to weak boundaries, large appearance variations, and limited annotated data.

While lightweight models (e.g., U-Net, U-Net++, PraNet) are efficient for clinical deployment, they often fail to capture rich semantic and structural information. On the other hand, Vision Foundation Models (VFMs) such as SAM, OneFormer, Mask2Former, and DINOv2 provide strong generalization but suffer from domain mismatch and high computational cost.

### 💡 Our Approach: LiteBounD
We propose **LiteBounD**, a novel framework that bridges this gap by distilling complementary knowledge from multiple VFMs into lightweight segmentation models.

Key contributions:
- 🔹 **Dual-Path Distillation**: Separates semantic and boundary-aware feature learning
- 🔹 **Frequency-Aware Alignment**: Supervises low-frequency (global semantics) and high-frequency (boundary details) components independently
- 🔹 **Boundary-Aware Decoder**: Enhances multi-scale feature fusion with structurally rich boundary priors

### 📊 Results
LiteBounD demonstrates strong performance across multiple benchmarks:
- **Seen datasets**: Kvasir-SEG, CVC-ClinicDB  
- **Unseen datasets**: ColonDB, CVC-300, ETIS  

✅ Consistently outperforms lightweight baselines  
✅ Competitive with state-of-the-art methods  
✅ Maintains efficiency for real-time clinical deployment  

### 🚀 Highlights
- Efficient yet powerful segmentation framework  
- Effective knowledge transfer from large foundation models  
- Robust generalization across datasets  

### 📌 Keywords
Polyp Segmentation, Knowledge Distillation, Foundation Models, Boundary Learning, Frequency Decomposition

---

### 📎 Citation
If you find this work useful, please consider citing:

