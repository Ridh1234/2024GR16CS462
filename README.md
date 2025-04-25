# 5G Network Slice Classification Using CNN

This project demonstrates the use of **Convolutional Neural Networks (CNNs)** to classify 5G network slices based on simulated data. It represents a practical application of deep learning in the domain of next-generation wireless networks.

## Slice Categories
The classification focuses on three core 5G functionalities:
- **eMBB** – Enhanced Mobile Broadband  
- **mMTC** – Massive Machine-Type Communications  
- **URLLC** – Ultra-Reliable Low-Latency Communications

##  Features

### 🔬 Synthetic Data Simulation
- Simulates 5G network metrics such as latency, throughput, signal strength, jitter, etc.
- Each sample is labeled with a slice category based on these metrics.

###  CNN Model
- A custom-built CNN model is trained to classify slices based on the synthetic data.
- Optimized for performance using TensorFlow/Keras.

###  Performance Visualization
- **Training Accuracy & Loss Curves**  
- **Confusion Matrix** for classification breakdown  
- **ROC Curves** with class-wise AUC scores  
- **Pair Plot with KDE** for feature distribution analysis  
- **Simulated Heatmap** showing resource utilization trends across slices

## 🛠️ Technologies Used
- **Programming Language:** Python  
- **Libraries:**  
  - TensorFlow / Keras  
  - Matplotlib  
  - Seaborn  
  - Scikit-learn  

## 📁 File Structure
- `5G_Slice_Classification.ipynb` – Google Colab notebook containing:
  - Synthetic data generation
  - CNN model definition and training
  - Visual evaluation of the results

##  How to Run

1. **Download or Clone** this repository.
2. **Open the Notebook** (`5G_Slice_Classification.ipynb`) in [Google Colab](https://colab.research.google.com).
3. **Run all cells** sequentially to:
   - Generate synthetic dataset
   - Train the CNN
   - Visualize model outputs

## 📈 Visual Outputs
- **Training Accuracy and Loss**: Understand how the model learns over time.
- **Confusion Matrix**: Evaluate classification performance across eMBB, mMTC, URLLC.
- **ROC Curves**: Measure true-positive vs. false-positive rate for each class.
- **Pair Plot with KDE**: Visualize feature relationships and distributions.
- **Simulated Heatmap**: Display 5G slice resource usage trends.

## 👥 Contributors
This project was collaboratively developed by:

- **Harshit Soni**  
- **Hridyansh Sharma**  
- **Shreyas Makwana**  
- **Daksh Mehta**

We worked together to conceptualize, develop, and present this project, combining our unique skills to build an end-to-end deep learning pipeline for 5G slice classification.

---

📌 **Note:** This project is built on simulated data and intended for academic demonstration purposes only.
