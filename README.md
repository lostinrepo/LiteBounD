# LiteBounD
Sharpening Lightweight Models for Generalized Polyp Segmentation: A Boundary Guided Distillation from Foundation Models
<p align="center">
  <img src="figures/IJCNN-Model.pdf" width="90%">
</p>

This repository contains the official implementation of our IJCNN/WCCI accepted paper:

### 🔍 Overview
Automated polyp segmentation plays a crucial role in early colorectal cancer detection. However, it remains challenging due to weak boundaries, large appearance variations, and limited annotated data.

While lightweight models (e.g., U-Net, U-Net++, PraNet) are efficient for clinical deployment, they often fail to capture rich semantic and structural information. On the other hand, Vision Foundation Models (VFMs) such as SAM, OneFormer, Mask2Former, and DINOv2 provide strong generalization but suffer from domain mismatch and high computational cost.

### 💡 Our Approach: LiteBounD
We propose **LiteBounD**, a novel framework that bridges this gap by distilling complementary knowledge from multiple VFMs into lightweight segmentation models.

### 📊 Results
LiteBounD demonstrates strong performance across multiple benchmarks:
- **Seen datasets**: Kvasir-SEG, CVC-ClinicDB


## Qualitative Results
Comparison of our method with state-of-the-art approaches on multiple polyp segmentation datasets.

<p align="center">
  <img src="figures/IJCNN_Seen.pdf" width="90%">
</p>
- 
- **Unseen datasets**: ColonDB, CVC-300, ETIS  
<p align="center">
  <img src="figures/IJCNN_Unseen.pdf" width="90%">
</p>

✅ Consistently outperforms lightweight baselines  
✅ Competitive with state-of-the-art methods  
✅ Maintains efficiency for real-time clinical deployment  

### 🚀 Highlights
- Efficient yet powerful segmentation framework  
- Effective knowledge transfer from large foundation models  
- Robust generalization across datasets  

### 📎 Citation
If you find this work useful, please consider citing:

