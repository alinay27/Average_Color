# Image Color Analyzer 

Interactive Streamlit web app that analyzes an uploaded image (PNG, JPG, JPEG) and calculates its average color/

* **Image Upload:** Supports `.png`, `.jpg`, and `.jpeg` formats
* **Color Extraction:** Utilizes K-Means clustering to find the precise average color of the image
* **Visual Feedback:** Displays the original image next to a solid color block showing the average color
* **Color Codes:** Output values are provided in both RGB and HEX formats
  
## To run the application:
### 1. Ensure you have streamlit streamlit and other libraries installed:
```bash
pip install streamlit opencv-python-headless numpy scikit-learn matplotlib
```

### 2. Run the Code
```bash
streamlit run app.py
```
