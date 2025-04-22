**Enhance.ai** — AI-Powered Data Quality Enhancer

Enhance.ai is a powerful AI-driven web-based tool that improves the quality of datasets by detecting and correcting issues such as missing values, anomalies, bias, and duplicate records. It helps **AI Engineers** and **Data Engineers** ensure their datasets are clean, balanced, and ready for robust machine learning model training.


**Table of Contents**

- Features
- Tech Stack
- Installation
- Usage
- How It Works

**Features**

(1) Missing Value Detection & Imputation  
(2) Anomaly Detection using IQR technique  
(3) Bias Detection through categorical and numerical distribution analysis  
(4) Duplicate Record Removal  
(5) Clean CSV Download Option  
(6) Drag-and-Drop Upload Interface  
(7) Interactive and Responsive UI (HTML/CSS/JS)

**Tech Stack**

**Frontend:**
- HTML, CSS, JavaScript

**Backend:**
- Python (Flask)
- Pandas, NumPy
- CORS + File Upload APIs
- ngrok (for public testing)

**AI/ML:**
- Custom scripts for:
  - Missing Value Handling
  - Anomaly Detection (IQR)
  - Bias Detection
  - Data Cleaning Pipeline

**Installation**

1. Clone the Repository

git clone https://github.com/kartikbatla/Enhance.ai.git
cd enhance-ai


**Usage**

Go to the Upload Section of the site.
Upload a .csv dataset file.

The backend processes:

Missing values
Anomalies
Duplicates
Bias analysis

A cleaned CSV file is auto-downloaded after processing.

**How It Works**

Upload: Users upload a CSV file through the frontend.

Preprocessing: Flask backend receives the file and applies:

Imputation for missing values
IQR-based anomaly removal
Duplicate removal

Bias Report: Bias is flagged based on value distributions.

Download: The cleaned CSV is sent back to the user.
