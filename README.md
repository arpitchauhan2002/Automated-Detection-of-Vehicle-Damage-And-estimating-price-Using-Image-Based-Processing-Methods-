# 🚗 Automated Vehicle Damage Detection and Repair Cost Estimation

A deep learning project using **Detectron2 + Mask R-CNN** for automated damage detection on vehicles and cost prediction for insurance claims and repair optimization.

![Detected Damage](3c6e2031-b631-4d17-90d4-64acaaba02a5.png)
## 📌 Problem Statement

Filing car insurance claims traditionally involves manual inspections, paperwork, and delays. This project automates damage detection and repair cost estimation using image data—speeding up the claims process and reducing fraud.

---

## 🧠 Model & Methodology

- **Model Used:** Mask R-CNN (via Facebook AI’s Detectron2)
- **Dataset:** Car Damage Detection (CarDD)
- **Training Data:** 2819 images across 6 damage types:
  - Dent
  - Scratch
  - Crack
  - Glass Shatter
  - Lamp Broken
  - Tire Flat
- **Evaluation Metrics:**
  - mAP (Mean Average Precision)
  - IoU (Intersection over Union)
- **Cost Estimation:** Based on IoU using Linear Regression

---

## ⚙️ How it Works

1. **Upload a vehicle image**
2. **Model detects damages** using instance segmentation
3. **IoU is calculated** against ground truth
4. **Cost prediction** via linear regression model

---

## 🗂️ File Structure

| File | Description |
|------|-------------|
| `final.ipynb` | Complete training + inference notebook |
| `research_paper.pdf` | Full research methodology & results |
| `output/` | Annotated sample image(s) |
| `requirements.txt` | Dependencies and setup instructions |

---

## 🔧 Installation

```bash
git clone https://github.com/yourusername/car-damage-detection-cost-estimation.git
cd car-damage-detection-cost-estimation
pip install -r requirements.txt
