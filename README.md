# AgriML - Smart Agriculture Decision Support System

[![GitHub Repository](https://img.shields.io/badge/GitHub-agri--ml--fullstack-blue?logo=github)](https://github.com/preyaah/agri-ml-fullstack)
[![React](https://img.shields.io/badge/Frontend-React-61DAFB?logo=react)](https://reactjs.org/)
[![FastAPI](https://img.shields.io/badge/Backend-FastAPI-009688?logo=fastapi)](https://fastapi.tiangolo.com/)
[![TensorFlow](https://img.shields.io/badge/ML-TensorFlow-FF6F00?logo=tensorflow)](https://www.tensorflow.org/)

AgriML is a **full-stack web application** that empowers farmers with AI-driven insights for smarter agricultural decisions. Built with **React** and **FastAPI**, it integrates three specialized machine learning models to detect plant diseases, assess soil tilling requirements, and classify pest infestations.

## 🚀 Features

### Core Functionality
- **🌱 Plant Disease Detection** - Advanced CNN-based classification to identify crop diseases from leaf images
- **🚜 Soil Tilling Assessment** - ML model to determine optimal soil preparation needs
- **🐛 Pest Infestation Classification** - Automated pest identification for timely intervention
- **📊 Interactive Dashboard** - React-powered interface for seamless user experience
- **⚡ Real-time Predictions** - FastAPI backend delivering instant AI-powered recommendations

### Technical Highlights
- **80%+ Model Accuracy** achieved across all three models
- **CNN & MobileNetV2** architectures for efficient image processing
- **Custom Data Pipeline** with preprocessing and augmentation techniques
- **Model Optimization** for deployment-ready performance
- **RESTful API** architecture for scalable integration

## 🛠️ Tech Stack

| Component | Technology |
|-----------|------------|
| **Frontend** | React, HTML5, CSS3, JavaScript |
| **Backend** | FastAPI, Python 3.8+ |
| **Machine Learning** | TensorFlow/Keras, CNN, MobileNetV2 |
| **Data Processing** | NumPy, Pandas, OpenCV |

## 🚀 Quick Start

### Prerequisites
- Python 3.8+
- Node.js 16+
- npm or yarn

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/preyaah/agri-ml-fullstack.git
   cd agri-ml-fullstack
   ```

2. **Backend Setup**
   ```bash
   cd backend
   python -m venv venv
   
   # Activate virtual environment
   # Windows:
   venv\Scripts\activate
   # macOS/Linux:
   source venv/bin/activate
   
   pip install -r requirements.txt
   ```

3. **Frontend Setup**
   ```bash
   cd frontend
   npm install
   ```

### Running the Application

1. **Start Backend Server**
   ```bash
   cd backend
   uvicorn app.main:app --reload --host 0.0.0.0 --port 8000
   ```

2. **Start Frontend Development Server**
   ```bash
   cd frontend
   npm start
   ```


## 🔬 Model Information

### Performance Metrics
| Model | Accuracy | Architecture | Dataset Size |
|-------|----------|-------------|--------------|
| Disease Detection | 85.2% | CNN + Transfer Learning | 10,000+ images |
| Soil Tilling | 82.7% | MobileNetV2 | 8,500+ images |
| Pest Classification | 83.4% | Custom CNN | 12,000+ images |

### Model Features
- **Data Augmentation**: Rotation, flip, zoom, brightness adjustment
- **Preprocessing**: Image normalization, resizing, noise reduction
- **Optimization**: Model quantization for faster inference
- **Validation**: K-fold cross-validation and holdout testing



## 🌟 Future Enhancements

- [ ] **Mobile Application** - React Native implementation
- [ ] **IoT Integration** - Real-time sensor data processing
- [ ] **Weather API** - Environmental factor consideration
- [ ] **GPS Integration** - Location-based recommendations
- [ ] **Multi-language Support** - Localization for global farmers
- [ ] **Offline Mode** - Edge computing capabilities



**Made with ❤️ for sustainable agriculture and smart farming practices**
