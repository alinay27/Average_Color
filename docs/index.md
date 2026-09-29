# Streamlit Average Color Analyzer

Use Streamlit to upload an image and find its average RGB color!

## Features
* **Upload:** Supports standard web formats: `.png`, `.jpg`, and `.jpeg`
* **Color Extraction:** Ues `KMeans` algorithm (set to 1 cluster) to find the exact average color
* **Display:** Shows the uploaded image next to a solid color patch showing the computed average
* **Output:** Provides both standard RGB values with HEX values too. 

## Setup

### 1. Ensure you have streamlit streamlit and other libraries installed:
```bash
pip install streamlit opencv-python-headless numpy scikit-learn matplotlib
```

### 2. Run the Code
```bash
streamlit run app.py
```
![Example Screenshot](indexMDscreenshot)