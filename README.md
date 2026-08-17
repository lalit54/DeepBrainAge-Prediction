
# DeepBrainAge - Brain Age Prediction System

## Overview

DeepBrainAge is an AI-powered brain age prediction system designed to estimate a person's biological brain age using MRI brain scans. The system leverages Deep Learning techniques, including a 3D Convolutional Neural Network (3D-CNN) based on the ResNet-50 architecture, to analyze neuroimaging data and provide accurate brain age estimation.

The project aims to assist researchers and healthcare professionals in understanding cognitive aging patterns and exploring the relationship between brain structure and biological age.

---

## Problem Statement

Traditional age estimation methods rely primarily on chronological age and manual analysis of MRI scans. These approaches can be time-consuming and may not accurately reflect the actual biological condition of the brain.

This project addresses the challenge by utilizing Artificial Intelligence and Deep Learning to automatically analyze MRI images and predict the estimated biological brain age.

---

## Objectives

- Develop an automated Brain Age Prediction System.
- Analyze MRI brain scans using Deep Learning.
- Estimate biological age with high accuracy.
- Provide an interactive web interface for prediction.
- Support neuroimaging research and cognitive health assessment.

---

## Key Features

- MRI Scan Upload and Processing
- Automated Brain Age Prediction
- Deep Learning-Based Analysis
- FastAPI REST API Backend
- Interactive Web Dashboard
- Prediction Confidence Score
- Real-Time Inference Visualization
- Responsive User Interface
- Prediction History Management

---

## System Architecture

### 1. Frontend Layer

The frontend provides an interactive user interface that allows users to upload MRI scans, initiate predictions, and visualize results.

**Technologies Used:**
- React.js (TypeScript)
- Tailwind CSS
- Framer Motion
- Axios
- Lucide React Icons

### 2. Backend Layer

The backend handles MRI preprocessing, model inference, validation, and response generation. It serves as the communication bridge between the frontend and the deep learning model.

**Technologies Used:**
- Python
- FastAPI
- Pydantic
- NumPy
- OpenCV

### 3. Deep Learning Layer

The core prediction engine is based on a 3D Convolutional Neural Network built upon the ResNet-50 architecture. The model processes MRI scans and predicts the estimated biological age of the brain.

**Frameworks Used:**
- PyTorch
- ResNet-50
- 3D CNN

---

## Technology Stack

| Category | Technologies |
|-----------|-------------|
| Frontend | React.js, TypeScript, Tailwind CSS |
| Backend | FastAPI, Python, Pydantic |
| Deep Learning | PyTorch, ResNet-50, 3D CNN |
| Image Processing | OpenCV, NumPy |
| Database | Supabase |
| API Communication | Axios |

---

## Model Information

| Parameter | Value |
|------------|---------|
| Model Type | 3D CNN based on ResNet-50 |
| Framework | PyTorch |
| Input | MRI Brain Scans |
| Output | Predicted Brain Age |
| Optimizer | Adam |
| Loss Function | Mean Absolute Error (MAE) |
| Evaluation Metrics | MAE, R² Score, Confidence Score |

---

## Project Structure

```text
DeepBrainAge-Prediction/
│
├── app/
├── src/
├── models/
├── data/
├── supabase/
├── package.json
├── package-lock.json
├── index.html
└── README.md
```

---

## Dataset

The model was trained using MRI brain scan datasets collected for neuroimaging research and brain age estimation tasks.

Dataset Link:

[https://drive.google.com/](https://drive.google.com/file/d/1M-isVkdWSuBEwhfp2Oto8-2UxGD4DLV-/view?usp=drive_link)

> Note: Large model files are not included in this repository due to GitHub file size limitations.

---

## Installation

### Frontend Setup

```bash
npm install
npm run dev
```

### Backend Setup

```bash
pip install -r requirements.txt
python main.py
```

---

## Workflow

1. User uploads an MRI brain scan.
2. The image is preprocessed and normalized.
3. The trained ResNet-50 based 3D CNN model performs inference.
4. Predicted brain age is generated.
5. Results and confidence metrics are displayed through the web interface.

---

## Applications

- Cognitive Age Assessment
- Brain Health Monitoring
- Neurological Research
- Neuroimaging Analysis
- Medical AI Research
- Early Detection of Brain Aging Patterns

---

## Future Enhancements

- Improved Prediction Accuracy
- Multi-Modal MRI Support
- Cloud Deployment
- Advanced Analytics Dashboard
- Clinical Integration
- Explainable AI Visualizations

---

## Team Members

- Lalit Dattatray Kasavkar
- Tulsi Charudatta Shirsat
- Tanmaya Sandeep Hodawadekar
- Sanjeet Indrajeet Ingavale 

---

## License

This project was developed for academic, educational, and research purposes.

---

## Acknowledgements

Special thanks to the project mentors, faculty members, and contributors who supported the development and evaluation of this Brain Age Prediction System.
