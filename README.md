# Electricity Waste Detection System ⚡🌱

An advanced, multi-model computer vision system designed to audit, detect, and report electricity waste in real-time. The system features a fully interactive web interface built with Gradio, providing detailed energy analysis reports and actionable recommendations.

## 📸 Screenshots
<p align="center">
<img width="1898" height="872" alt="image" src="https://github.com/user-attachments/assets/4e110a84-3e3e-4d11-a32e-54adbbac1a21" />
<img width="1868" height="912" alt="image" src="https://github.com/user-attachments/assets/0d1846fc-01f9-4fce-a365-cbbb8f96f381" />

  
</p>

## 🚀 Key Features
* **Multi-Model Analysis:** Evaluates images using **5 Deep Learning Architectures**, including **ResNet50** and **Vision Transformer (ViT)** for maximum classification accuracy.
* **Automated Energy Auditing:** Generates a comprehensive *Energy Waste Analysis Report* capturing Location Type, Lighting Status, and Time Conditions.
* **Smart Image Analytics:** Computes advanced frame statistics such as Average Brightness and Contrast Ratio to back up model decisions.
* **Intelligent Recommendations:** Provides automated suggestions (e.g., "Turn off artificial lights — natural light is sufficient") based on environmental analysis.
* **Interactive Web UI:** Deployed with a clean, user-friendly **Gradio** interface supporting single-model and comparative multi-model execution.

## 🛠️ Tech Stack & Tools
* **Core Language:** Python
* **Deep Learning Frameworks:** TensorFlow / PyTorch (ResNet50, Vision Transformer)
* **Computer Vision & Processing:** OpenCV
* **Web Interface & Deployment:** Gradio

## 📊 System Overview & UI
### 1. Image Ingestion & Multi-Model Execution
Users can upload any environment image. The system triggers parallel testing across the integrated architectures to output classification results and confidence scores.

### 2. Automated Report Generation
The system evaluates environmental attributes to structure a dynamic layout text report, highlighting waste scores and concrete actions to optimize power consumption.

## 💻 How to Run Locally

1. Clone the repository:
   ```bash
   git clone [https://github.com/merriamessam/Smart_Energy_Audit.git](https://github.com/merriamessam/Smart_Energy_Audit.git)
   
