# 🧠 Deep Learning Basics with Python Libraries

## 📌 Project Overview
This project introduces the fundamentals of **deep learning** using Python libraries such as TensorFlow/Keras, NumPy, and Matplotlib.  
The focus is on building, training, evaluating, and visualizing a neural network for **handwritten digit classification (MNIST dataset)**.

---

## ⚙️ Workflow

1. **Data Preparation**
   - Load and preprocess the MNIST dataset.
   - Normalize input images and one‑hot encode labels.

2. **Model Building**
   - Define a sequential neural network with Dense, Dropout, and activation layers.
   - Compile the model with loss function, optimizer, and metrics.

3. **Training**
   - Train the model using `model.fit` with training and validation data.
   - Monitor accuracy and loss across epochs.

4. **Model Summary**
   - Use `model.summary()` to inspect architecture, output shapes, and parameter counts.

5. **Performance Evaluation**
   - Evaluate the model on test data using `model.evaluate`.
   - Print test loss and accuracy for quantitative assessment.

6. **Visualization**
   - Plot training vs. validation accuracy (`history.history['accuracy']`).  
   - Plot training vs. validation loss (`history.history['loss']`).  
   - Visualize correctly and incorrectly classified digits.

7. **Predictions**
   - Generate predictions with `model.predict`.
   - Compare predicted classes with true labels.
   - Identify correct and incorrect indices for error analysis.

8. **Model Saving**
   - Save the trained model in `.h5` format for reuse.
   - Reload the model using `load_model`.

---

## 📂 Outputs
- **Accuracy and Loss Plots** → Track learning progress.  
- **Correct vs. Incorrect Predictions** → Visual inspection of model strengths and weaknesses.  
- **Saved Model (`.h5`)** → Portable file containing architecture, weights, and training configuration.  

---

## ✅ Key Takeaways
- Neural networks can effectively classify handwritten digits.  
- Visualization helps detect overfitting and generalization issues.  
- Saving models in `.h5` format ensures reproducibility and portability.  
- Error analysis (misclassified digits) is crucial for improving performance.
