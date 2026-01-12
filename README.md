# 🛒 Shoplifting Detection System using Deep Learning

## 📌 Project Overview
Shoplifting is a major challenge in retail environments, leading to significant financial losses. Traditional CCTV surveillance relies on manual monitoring, which is inefficient and error-prone. This project presents an **AI-based Shoplifting Detection System** that automatically analyzes surveillance videos and detects shoplifting activities using deep learning techniques.

The system uses a **frame-based classification approach** combined with **probability aggregation** to provide reliable video-level predictions with confidence scores.

---

## 🎯 Objectives
- Automate shoplifting detection from CCTV surveillance videos  
- Reduce dependence on manual monitoring  
- Accurately classify activities as **Normal** or **Shoplifting**  
- Provide prediction results with confidence values  

---

## 🧠 Technologies Used
- **Programming Language:** Python  
- **Deep Learning Framework:** TensorFlow, Keras  
- **Model Architecture:** ResNet50 (Transfer Learning)  
- **Computer Vision:** OpenCV  
- **Platform:** Google Colab  
- **Libraries:** NumPy, Matplotlib, scikit-learn  

---

## ⚙️ Methodology
1. Upload CCTV video as input  
2. Convert video into frames at fixed intervals  
3. Resize and normalize frames  
4. Classify each frame using ResNet50 CNN  
5. Aggregate frame-level predictions using mean and max values  
6. Apply threshold-based decision making  
7. Display output with prediction confidence  

Fig 1: Architecture Diagram:

<img width="406" height="553" alt="image" src="https://github.com/user-attachments/assets/5f07ed9d-89e6-440d-9e8e-16b97f27c051" />

---

## 🧩 Algorithms Used
- Convolutional Neural Network (CNN – ResNet50)  
- Transfer Learning  
- Probability Aggregation (Mean & Max)  
- Threshold-based Classification  

---

## 📊 Output
- **Prediction Result:** Normal Activity / Shoplifting Detected  
- **Prediction Confidence:** Displayed as a percentage

<img width="406" height="380" alt="image" src="https://github.com/user-attachments/assets/1e34f022-60e0-4b52-9710-a5236348e6b8" />
 
<img width="405" height="382" alt="image" src="https://github.com/user-attachments/assets/88a5bc4b-4cc5-4430-af6e-c17e78d34c28" />

## 🚀 Future Enhancements
- Integration of temporal models (LSTM / Transformers)  
- Multi-camera surveillance support  
- Real-time edge deployment  
- Larger and diverse datasets  
- Explainable AI techniques  
