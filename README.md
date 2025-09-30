# Deepvision-cifar10: Convolutional Neural Networks on CIFAR-10

## 📌 Objective  
The objective of this assignment is to gain **hands-on experience with Convolutional Neural Networks (CNNs)** by applying them to the **CIFAR-10 dataset**, evaluating model performance, and analyzing results under different architectural and training configurations.

---

## 📂 Project Overview  
This project builds on prior assignments by exploring **deeper CNN architectures** and advanced training strategies for image classification. Using the **CIFAR-10 dataset**, multiple configurations of CNNs are designed, trained, and evaluated.  

The project emphasizes:  
- Data preprocessing and augmentation  
- Implementation of CNN architectures  
- Comparative evaluation of models  
- Performance visualization and interpretation  

---

## 🗂 Dataset: CIFAR-10
- **Classes (10):** airplane, automobile, bird, cat, deer, dog, frog, horse, ship, truck  
- **Training Samples:** 50,000 images  
- **Testing Samples:** 10,000 images  
- **Image Size:** 32x32 pixels, RGB  

---

## ⚙️ Methodology

### 1. Data Preprocessing  
- Normalized pixel values to range `[0, 1]`.  
- One-hot encoded labels.  
- Applied **data augmentation** (rotation, flipping, zoom, shift) for better generalization.  

### 2. Model Development (CNN Architectures)  
- Stacked convolutional and pooling layers.  
- Used **ReLU activation** in hidden layers and **Softmax** in output.  
- Applied **Dropout layers** to reduce overfitting.  

### 3. Training & Validation  
- Models trained with **Adam optimizer** and categorical cross-entropy loss.  
- Early stopping used to prevent overfitting.  
- Training evaluated using validation split.  

### 4. Evaluation Metrics  
- Accuracy and loss curves.  
- Classification report with precision, recall, and F1-score.  
- Confusion matrix to visualize class-wise performance.  

---

## 📊 Results & Insights
- CNN models achieved **significantly better performance** compared to shallow baselines.  
- **Data augmentation** improved robustness and generalization.  
- Dropout reduced overfitting in deeper architectures.  
- Certain configurations showed trade-offs between accuracy and training time.  

---

## 🛠️ Tech Stack
- **Language:** Python  
- **Libraries & Frameworks:**  
  - TensorFlow / Keras  
  - NumPy  
  - Matplotlib, Seaborn  
  - scikit-learn  

---

## 📦 Installation & Setup  

1. Clone this repository:  
   ```bash
   git clone https://github.com/your-username/cifar10-cnn-lab3.git
   cd cifar10-cnn-lab3
