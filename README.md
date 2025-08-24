# Dogs vs Cats Classifier 🐶🐱

This project implements a **Convolutional Neural Network (CNN)** using **TensorFlow/Keras** to classify images of dogs and cats.  
The dataset is sourced from [Kaggle’s Dogs vs Cats dataset](https://www.kaggle.com/datasets/salader/dogs-vs-cats).  

---

## 📌 Project Overview
- Downloads and extracts the **Dogs vs Cats** dataset from Kaggle.  
- Preprocesses images (resizing, normalization, and batching).  
- Builds a **CNN model** with multiple convolution, pooling, and dense layers.  
- Trains the model using **binary cross-entropy loss** and **Adam optimizer**.  
- Evaluates accuracy on the validation dataset.  
- Tests the model on custom images (`dog img.jpg`, `cat img.jpg`).  

---

## 🚀 Technologies Used
- Python 3  
- TensorFlow / Keras  
- NumPy  
- OpenCV (for test image preprocessing)  
- Matplotlib (for training visualization)  

---

## 📂 Project Structure
```
dogs_vs_cats/
│── dogs_vs_cat_.ipynb     # Main Jupyter Notebook
│── README.md              # Project Documentation
│── dataset/               # Dogs vs Cats dataset (after extraction)
│── saved_model/           # Trained CNN model (optional)
```

---

## ⚙️ How to Run
1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/dogs-vs-cats.git
   cd dogs-vs-cats
   ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Make sure you have your **Kaggle API key** set up:
   ```bash
   mkdir ~/.kaggle
   cp kaggle.json ~/.kaggle/
   chmod 600 ~/.kaggle/kaggle.json
   ```

4. Open the notebook and run:
   ```bash
   jupyter notebook dogs_vs_cat_.ipynb
   ```

---

## 📊 Results
- Training accuracy: ~XX% (replace with your achieved accuracy)  
- Validation accuracy: ~XX%  
- Example predictions:
  - Cat image → Classified as **Cat** 🐱  
  - Dog image → Classified as **Dog** 🐶  

---

## 🔮 Future Improvements
- Use **data augmentation** to reduce overfitting.  
- Experiment with **transfer learning** (e.g., VGG16, ResNet).  
- Deploy the model as a **Flask/Django web app**.  

---

## 🤝 Contributing
Feel free to fork this project, open issues, or submit pull requests to improve it.  

---

## 📜 License
This project is licensed under the **MIT License**.  
