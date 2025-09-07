# pneumoniadetectionsystem

# 🩺 Pneumonia Detection using Deep Learning  

This project uses **MobileNetV2** and **Transfer Learning** to detect **Pneumonia** from chest X-ray images.  
It also includes a **Gradio interface** for easy predictions.  

---

## 🚀 Features  
- Detects **Normal** vs **Pneumonia** from X-rays  
- Provides prediction **confidence score**  
- Estimates **severity** of pneumonia (basic brightness metric)  
- Easy-to-use **Gradio web app**  

---

## 🛠️ Tech Stack  
- Python 3.10+  
- TensorFlow / Keras  
- OpenCV  
- NumPy  
- Matplotlib  
- Gradio  

---
## 📂 Dataset

The project uses the **Chest X-ray Dataset** from Kaggle:

🔗 [Chest X-ray Pneumonia Dataset](https://www.kaggle.com/datasets/paultimothymooney/chest-xray-pneumonia?resource=download)

After downloading, place the dataset inside your project folder:



## ⚙️ Installation  
```bash
# Clone the repo
git clone https://github.com/your-username/pneumonia-detection.git
cd pneumonia-detection

# Install dependencies
pip install -r requirements.txt

# Run the app
python app.py
