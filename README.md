 # 🚀 Real-Time Image Classification with Inference Latency Analysis Using Pretrained Deep Learning Models

## 📌 Project Overview

This project demonstrates a **real-time image classification system** with a strong emphasis on **neural network inferencing performance**. A user uploads an image through a web interface, the system classifies the image using a **pretrained deep learning model**, and displays both the **predicted class** and the **time taken (latency)** to generate the prediction.

The core objective of this project is **not model training**, but **efficient inference and performance evaluation**, which is a critical requirement in real-world AI systems.

---

## 🎯 Key Objectives

* Perform **image classification** using a pretrained deep learning model
* Measure **real-time inference latency** in milliseconds
* Demonstrate **optimized inferencing concepts** used in production AI systems
* Provide a **clean, app-like user interface** for interaction
* Bridge the gap between **AI theory and AI engineering**

---

## 🧠 System Workflow

1. User uploads an image via the web interface
2. Image is preprocessed (resize, normalization)
3. Pretrained **ResNet-50** model performs inference
4. The system predicts the object class from **ImageNet (1000 classes)**
5. Inference time (latency) is calculated
6. Result is displayed with:

   * Uploaded image preview
   * Predicted class
   * Confidence score
   * Inference latency

---

## ⚡ Role of Optimization Technologies

Although inference is demonstrated locally using PyTorch, this project is conceptually designed around **industry-grade optimization tools**:

* **TensorRT** – Optimizes trained neural networks for high-speed inference on GPUs
* **Triton Inference Server** – Enables scalable and efficient deployment of optimized models

These technologies significantly reduce inference latency in production environments and are widely used in real-time AI applications.

---

## 🛠️ Tech Stack

* **Programming Language:** Python
* **Deep Learning Framework:** PyTorch
* **Model:** ResNet-50 (ImageNet pretrained)
* **Web Framework:** Flask
* **Frontend:** HTML, CSS
* **Image Processing:** Pillow / Torchvision

---

## 📊 Sample Results

* **Predicted Class:** Egyptian Cat / Beagle (ImageNet classes)
* **Confidence:** ~65–80%
* **Inference Latency:** ~150–450 ms (CPU-based inference)

> ⚠️ Latency is higher on CPU. With GPU + TensorRT optimization, latency can reduce to **single-digit milliseconds**.

---

## 🖼️ Application Screenshots

### 🔹 Home Screen

<img width="1366" height="768" alt="Screenshot (106)" src="https://github.com/user-attachments/assets/147ccb85-9d4e-41f2-a25b-c0f26f149d32" />

### 🔹 Image Classification Result 

<img width="1366" height="768" alt="Screenshot (107)" src="https://github.com/user-attachments/assets/39f8c0bd-569b-4488-a41e-4776add38f92" />

### 🔹 Image Classification Result

<img width="1366" height="768" alt="Screenshot (108)" src="https://github.com/user-attachments/assets/6d868c86-01f6-469c-8295-3cea122bcdf8" />

---

## 🎓 Academic Significance

This project highlights:

* Difference between **training and inference**
* Importance of **latency in real-world AI systems**
* Practical understanding of **AI deployment and optimization**
* Engineering-oriented thinking beyond basic ML models

Such concepts are highly valued in **research-focused and industry-aligned AI programs**.

---

## 🏁 Conclusion

The project successfully demonstrates an **optimized image classification pipeline** with real-time latency analysis. It emphasizes the role of inference optimization in scalable AI systems and provides hands-on exposure to performance-aware AI engineering.

---

## 📌 Future Enhancements

* GPU-based TensorRT optimization
* Triton Inference Server deployment
* Top-5 prediction visualization
* Batch inference performance analysis

---

## 👤 Author

**M V Karthikeya**

---

📜 License

This project is released under the MIT License and is intended strictly for academic and educational purposes.

---

> *This project focuses on AI system performance and inference optimization rather than model training or dataset creation.*
