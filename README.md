# 🧑‍💼 Age Estimation with ResNet50

This project aims to help **Good Seed**, a supermarket chain, ensure compliance with alcohol sales laws by estimating the age of customers via computer vision. Using a pre-trained convolutional neural network (ResNet50), we predict the age of individuals based on facial photos.

---

## 📌 Objective

Develop a deep learning model that estimates a person's age from their photograph to determine if they are legally eligible to purchase alcohol.

---

## 🧪 Dataset Description

- **Images:** Facial photos of customers  
- **Labels:** Corresponding age of individuals (`real_age`)  
- **Files:**
  - `labels.csv`: metadata file with image names and real ages  
  - `final_files/`: folder containing the image data  

---

## 🧠 Model Architecture

- **Base Model:** ResNet50 pre-trained on ImageNet  
- **Top Layers:**
  - Global Average Pooling  
  - Dense Layer (ReLU)  
- **Loss Function:** Mean Squared Error (MSE)  
- **Metric:** Mean Absolute Error (MAE)  
- **Optimizer:** Adam (lr=0.0005)  

---

## 🧪 Evaluation Result

The model achieves a **MAE < 8** on the test set, which is considered an effective result for age regression tasks.

---

## 🔍 Insights & Next Steps

- Vision AI can effectively assist in verifying age at point-of-sale terminals.  
- Potential applications:
  - Restricting access to age-sensitive services  
  - Personalized advertising  
  - Age demographic analytics  

---

## 📁 Project Structure

```
age-estimation-cnn/
│
├── Proyecto_final_sprint16_j.ipynb
├── README.md
└── requirements.txt
```

---

## 🛠️ Tools & Libraries

- Python  
- TensorFlow / Keras  
- ResNet50 (ImageNet weights)  
- pandas  

---

## ✅ Status

✔️ Completed as part of the **TripleTen Bootcamp** – Sprint: *Computer Vision & CNN Regression*

---

## 📌 Author

David Villanueva  
[LinkedIn](https://www.linkedin.com/in/david-villanueva-59659727)  
[GitHub](https://github.com/lolapaul)
