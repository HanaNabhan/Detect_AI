# AI-based Image Authenticity Detection
Project Overview
This project focuses on detecting whether images are real or AI-generated as part of a competition dataset containing 800 images.

## Key Features
✔ Dataset: 800 real & fake images (competition dataset)
✔ Models Used:

- Xception (highest accuracy: 84%)
- MobileNetV2 & V3Small
- EfficientNet-B0 & EfficientNetV2-B0
✔ Augmentation: Applied to improve model generalization
✔ Analysis: Performance comparison across different architectures
## 📊 Results and Insights
### Top-Performing Model: Xception (84% Accuracy)
Best suited for image authenticity classification
High performance due to deep feature extraction
Other Models & Their Performance
Model
### Other Models 
MobileNetV2
MobileNetV3-Small
EfficientNet-B0
EfficientNetV2-B0


## ⚙️ Technical Implementation
Data Preparation & Augmentation
✔ Random rotations, flips, brightness adjustments
✔ Balanced training batches to prevent overfitting

Model Training
✔ Transfer Learning: Fine-tuning pre-trained models
✔ Optimizer: Adam with learning rate scheduling

## 📸 Example Detection Results
![Alt text](https://github.com/HanaNabhan/Detect_AI/blob/main/result.png)

## Get A copy 
git clone https://github.com/your-username/ai-image-detection.git  

## 📈 Future Improvements
✅ Use larger datasets (e.g., FFHQ, Deepfake datasets)
✅ Experiment with Vision Transformers (ViTs)
✅ Deploy as cloud API for real-time detection

🌟 Contributions welcome!

