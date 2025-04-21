<p align="center">
  <img src="white_shirt.jpeg" alt="Alireza Kanani Banner" style="max-width:100%; border-radius: 10px; width="550" height="450" " />
</p>

### 🔍 Computer Vision Tasks Workflow
flowchart TB
    RawImages([Raw Images]):::input
    subgraph Object_Detection direction LR
        DINO([Zero-Shot Grounding DINO]):::zero_shot
        DetOut([Images and Labels]):::output
        FTDet([Fine-Tune Model - e.g. YOLO]):::processing
        Deploy([Deployment]):::deployment
        OpenVINO([OpenVINO - CPU base]):::deployment
        TensorRT([TensorRT - GPU base]):::deployment
        RawImages --> DINO --> DetOut --> FTDet --> Deploy
        Deploy --> OpenVINO
        Deploy --> TensorRT
    end
    
    subgraph Classification direction LR
        CLIP([Zero-Shot CLIP]):::zero_shot
        ClassOut([Images and Class IDs]):::output
        FTClass([Fine-Tune Classifier - e.g. ResNet-18]):::processing
        RawImages --> CLIP --> ClassOut --> FTClass
    end
    
    subgraph Segmentation direction LR
        SAM([Zero-Shot SAM]):::zero_shot
        SegOut([Images and Ground Truth]):::output
        FTSeg([Fine-Tune Segmentation Network]):::processing
        RawImages --> SAM --> SegOut --> FTSeg
    end

    classDef input fill:#e0f7fa,stroke:#004d40,stroke-width:2px;
    classDef processing fill:#e8f5e9,stroke:#2e7d32,stroke-width:2px;
    classDef zero_shot fill:#fffde7,stroke:#f9a825,stroke-width:2px,stroke-dasharray: 5 5;
    classDef output fill:#fce4ec,stroke:#880e4f,stroke-width:2px;
    classDef deployment fill:#f3e5f5,stroke:#6a1b9a,stroke-width:2px;








<h1 align="center">👋 Hi, I’m Alireza Kanani</h1>

<p align="center">
  <img src="https://readme-typing-svg.herokuapp.com?font=Fira%20Code&size=24&pause=1000&color=4AF626&center=true&width=500&lines=AI+Engineer;Computer+Vision+Specialist;Deep+Learning+Enthusiast;Jetson+Developer" alt="Typing SVG">
</p>

<p align="center">
  🎓 MSc in Electrical & Communication Engineering • 📍 Tehran, Iran
</p>

---

### 🔭 I’m currently working on

- 🤖 Deploying real‐time vision pipelines on NVIDIA Jetson (Nano, Xavier, Orin)
- 🤖 Developing and deploying trading bot pipeline.

---

- **Machine Learning Frameworks & Libraries**  TensorFlow, Keras, PyTorch, CUDA (GPU Programming),
ONNX, TensorRT, OpenVINO, YOLO, GroundingDINO,
Huggingface, GStreamer, DeepStream, GST-shark,
OpenCV, Scikit-learn, SciPy, Mediapipe,
Vision Transformer(ViT)
- **Embedded Systems**: Jetson Nano, Jetson Xavier NX, Jetson Orin Nano
### 🌱 My Passions
- **Computer Vision**: Object detection & tracking, Unsupervised learning, Human robot interaction
 

---

### 💼 Experience Highlights
| Company / Project                         | Role & Technologies                                 |
|-------------------------------------------|-----------------------------------------------------|
| **Syna Company** (Oct 2023 – Mar 2025)     | ML deployment on Jetson (C++/Python, DeepStream)    |
| **Persian Handwriting OCR** (2022)        | OCR pipeline with CNN & deep learning               |
| **Remote Sensing Tracker** (2022)         | Optical‑flow tracking on embedded Raspberry Pi      |
| **3D Face Reconstruction** (2023)         | PRNet & HRN for texture‑based expression mapping    |
| **Defect Detection** (Master’s Thesis)    | CNN‑based industrial defect segmentation            |

---

### 🛠️ Tech Stack
<div align="center">
  <img src="https://img.shields.io/badge/Python-3670A0?logo=python&logoColor=FFE873" alt="">
  <img src="https://img.shields.io/badge/C++-00599C?logo=c%2B%2B&logoColor=white" alt="">
  <img src="https://img.shields.io/badge/PyTorch-F1502F?logo=pytorch&logoColor=white" alt="">
  <img src="https://img.shields.io/badge/TensorFlow-FF6F00?logo=tensorflow&logoColor=white" alt="">
  <img src="https://img.shields.io/badge/OpenCV-5C3EE8?logo=opencv&logoColor=white" alt="">
  <img src="https://img.shields.io/badge/YOLOv8-000000?logo=yolo&logoColor=white" alt="">
  <img src="https://img.shields.io/badge/Jetson-76B900?logo=nvidia&logoColor=white" alt="">
  <img src="https://img.shields.io/badge/GStreamer-4298BE?logo=gstreamer&logoColor=white" alt="">
</div>

---

### 📊 GitHub Stats
<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=Alirezanltv&show_icons=true&theme=tokyonight" alt="GitHub Stats" />
  &nbsp;&nbsp;
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=Alirezanltv&theme=tokyonight" alt="Streak Stats" />
</p>

---

### 📫 Let’s Connect
- ✉️ alirezakanani.project@gmail.com   
- 🔗 [LinkedIn](https://www.linkedin.com/in/alireza-kanani-b7323b1bb)  
- 🚀 Open to collaborations in AI, CV & embedded systems!

---

<div align="center">
  <sub>Built with ❤️ and ☕ by Alireza Kanani</sub>
</div>
