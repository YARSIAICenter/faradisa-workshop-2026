# 🧠 FARADISA Workshop 2026 - Day 1: AI Fundamentals

This folder contains the hands-on session materials for **Day 1** of the FARADISA Workshop 2026, focusing on **AI Fundamentals** and image classification.

## 📋 Overview

In this session, you will learn:
- Basic concepts of Artificial Intelligence and Deep Learning
- How to build an image classification model using PyTorch
- Transfer Learning with EfficientNet-B0
- Model training, validation, and evaluation
- Understanding metrics for medical image classification

**Case Study:** Skin Lesion Classification (Normal vs Abnormal)

## 📁 Files

| File | Description |
|------|-------------|
| `ai-fundamentals.ipynb` | Main notebook for hands-on session |
| `requirements.txt` | Python dependencies (for local setup) |

## 🚀 How to Run

### Step 1: Download the Notebook
Download the file `ai-fundamentals.ipynb` from this folder.

### Step 2: Open Google Colab
Go to [https://colab.research.google.com](https://colab.research.google.com)

### Step 3: Upload the Notebook
- Click **File** → **Upload notebook**
- Select the downloaded `ai-fundamentals.ipynb` file

### Step 4: Run the Notebook
- Run each cell sequentially from top to bottom
- Use **Shift + Enter** to run a cell and move to the next one
- Or click **Runtime** → **Run all** to run all cells

## ⚠️ Notes

- **GPU is optional** but recommended for faster training
- To enable GPU in Colab: **Runtime** → **Change runtime type** → **GPU**
- Dataset will be automatically downloaded from GitHub when you run the notebook
- Make sure to run cells in order, as later cells depend on earlier ones

## 📊 Expected Output

After completing this notebook, you will have:
- Trained a Deep Learning model for skin lesion classification
- Visualizations of training progress (loss & accuracy curves)
- Confusion matrix and classification metrics
- A saved model file (`best_model.pth`)

---

**Happy Learning! 🎉**
