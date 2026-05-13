# Potato Leaf Disease Detection 🌿

### Project Overview
This project focuses on identifying diseases in potato crops using Deep Learning. We implemented a robust pipeline that classifies potato leaves into three categories: **Early Blight**, **Late Blight**, and **Healthy**.

### Key Features
* **Multi-Stage Workflow:** Includes baseline training, data preprocessing, and model ensembling.
* **Data Augmentation:** Applied techniques like rotation, zoom, and flip to reduce overfitting and improve generalization.
* **Transfer Learning:** Leveraged **MobileNetV2** for high-accuracy feature extraction.
* **Ensemble Learning:** Used **Soft Voting** to combine CNN and MobileNetV2 for stable predictions.

### Performance
* **Final Accuracy:** 96.88%
* **Comparison:** Successfully analyzed the performance gap between raw data and augmented data models.
