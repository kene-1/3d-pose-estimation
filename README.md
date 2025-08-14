# 3d-pose-estimation
# 3D Human Pose Estimation using GRU on ITOP Dataset

This project implements a GRU-based deep learning model to estimate 3D human joint positions from depth images using the **ITOP Side View Dataset**. The goal is to accurately predict 3D joint coordinates and evaluate performance using standard pose estimation metrics.

---

## 📌 Features
- **Custom PoseNet Architecture** for depth-based pose estimation.
- **Iterative Refinement** using GRUs to improve prediction accuracy.
- **Data Preprocessing**: Normalization, filtering valid samples, and data augmentation.
- **Evaluation Metrics**: MPJPE (Mean Per Joint Position Error) and PCK (Percentage of Correct Keypoints).
- **Depth Image Visualization** and 3D pose rendering for predictions vs ground truth.

---

## 🛠 Tech Stack
- **Language**: Python
- **Deep Learning Framework**: PyTorch
- **Other Libraries**: NumPy, Matplotlib, OpenCV, scikit-learn
- **Dataset**: ITOP Side View (Indoor Training and Outdoor Testing Dataset)

---

---

## ​ Dataset
The **ITOP (Indoor Training and Outdoor Testing) Dataset** contains depth images and 3D ground truth joint positions for multiple subjects from a side view.

📥 **Download Link**: [Zenodo – ITOP Dataset](https://zenodo.org/records/3932973)

> ⚠️ The dataset is not included in this repository due to GitHub file size limits.

---

## ​ How to Run
1. **Clone this repository**
```bash
git clone https://github.com/YOUR_USERNAME/3D-Pose-Estimation-GRU.git
cd 3D-Pose-Estimation-GRU

## 📂 Project Structure
│
├── 3d_pose_estimation.ipynb # Main Jupyter Notebook
├── requirements.txt # Python dependencies
