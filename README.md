# 🧠 COVID-19 Detection Using Deep Learning (VGG19)

## 📌 About the Project
This project is based on detecting **COVID-19 from CT scan images** using **Deep Learning**. I used a **pretrained VGG19 model** and applied **transfer learning** to classify CT scans as **COVID-positive or Non-COVID**.  
The main goal of this project is to understand how AI can be used in real-world healthcare problems.

## 🧠 Problem Statement
COVID-19 diagnosis using traditional testing methods can take time and requires medical resources. An automated system using medical images can help doctors by providing **quick and reliable predictions**.

## 💡 What I Built
I trained a deep learning model using **VGG19**, where the pretrained layers were frozen and custom layers were added for classification.  
The model learns important features from CT scan images and predicts whether the patient is infected or not.

## 🛠️ Technologies Used
- Python  
- TensorFlow & Keras  
- VGG19 (Transfer Learning)  
- Google Colab  
- NumPy, Matplotlib, OpenCV  

## 📊 Key Features
- Used transfer learning for better accuracy
- Image augmentation to reduce overfitting
- Binary classification (COVID / Non-COVID)
- Training and validation performance visualization
- Model saved for future deployment

## ⚙️ How the Project Works
1. Collected and organized the CT scan dataset  
2. Preprocessed images and applied data augmentation  
3. Split data into training and testing sets (80:20)  
4. Built and trained the VGG19-based model  
5. Evaluated model performance  
6. Saved the trained model for deployment

## 📈 Results & Learning
The model achieved good accuracy on test data and showed stable training behavior.  
Through this project, I learned:
- How transfer learning works in practice
- How to handle image datasets
- Model evaluation and performance analysis
- Real-world application of deep learning in healthcare

## 🚀 Future Scope
- Train on a larger and more diverse dataset
- Compare results with CNN and Xception models
- Deploy the model using a web interface
- Add explainable AI techniques like Grad-CAM

## 👨‍💻 Author
**Subhash Mehta**  
CSE Student | KIIT  
📧 subhashmehta3232@gmail.com  
Interested in AI, Deep Learning & Web Development


