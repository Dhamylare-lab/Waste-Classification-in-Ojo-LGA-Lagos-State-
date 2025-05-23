## 🧠 Waste Classification in Ojo LGA – AI-Powered Image Recognition

**By Sulyman Tajudeen Amori**  
**3MTT Cohort 3 | Fellow ID: FE/23/65765739**

This project leverages computer vision and machine learning to classify waste images into categories such as plastic, metal, paper, glass, and organic. The goal is to support smart waste management and recycling in Ojo Local Government Area, Lagos State.

---

### 📂 Project Structure

- **Notebook:** [`ojo-lg-waste-vision.ipynb`](https://colab.research.google.com/gist/Dhamylare-lab/e8863c2a2934679d39837c8fc9eff2d2/ojo-lg-waste-vision.ipynb)
- **Dataset:** Images of various waste types (plastic, metal, paper, glass, organic)
- **Model:** Convolutional Neural Network (CNN) using TensorFlow/Keras
- **Deployment:** Google Colab for interactive exploration

---

### 🛠️ Key Steps

1. **Data Loading & Preprocessing**
   - Images are loaded from directories corresponding to each waste category.
   - Data augmentation techniques such as rotation, flipping, and zooming are applied to enhance model generalization.

2. **Model Architecture**
   - A CNN is constructed with multiple convolutional and pooling layers.
   - The model is compiled with appropriate loss functions and optimizers.

3. **Training & Evaluation**
   - The model is trained on the preprocessed dataset.
   - Evaluation metrics include accuracy and loss, visualized using plots.

4. **Prediction**
   - The trained model is used to predict the category of new waste images.
   - Predictions are displayed alongside the input images for verification.

---

### 📊 Results

- **Training Accuracy:** Achieved high accuracy on the training dataset.
- **Validation Accuracy:** Maintained strong performance on unseen data, indicating good generalization.
- **Confusion Matrix:** Demonstrated effective classification across all waste categories.

---

### 🚀 Try It Yourself

Run the notebook in Google Colab to explore the model and test it with your own images:

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/gist/Dhamylare-lab/e8863c2a2934679d39837c8fc9eff2d2/ojo-lg-waste-vision.ipynb)

---

*Built as part of the 3MTT Knowledge Showcase*  
#3MTT #AIforGood #WasteManagement #MachineLearning #ComputerVision #NigeriaTech #OjoLGA
