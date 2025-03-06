# **Breast Cancer Diagnosis Predictor**  

## **Overview**  
The **Breast Cancer Diagnosis Predictor** is a machine learning-powered web application designed to assist in diagnosing breast cancer. Given a set of medical measurements, the app predicts whether a breast mass is **benign** or **malignant**. It provides:  

- A **radar chart** visualization of input data.  
- A **probability score** of malignancy.  
- Support for **manual input** or **data integration** from a cytology lab (lab connection not included in the app).  

This project is developed for **educational purposes** using the **Breast Cancer Wisconsin (Diagnostic) Dataset**. It is **not intended for professional medical use**.  

A **live demo** is available on **Streamlit Community Cloud**.  

## **Installation**  
To set up the app, it's recommended to use a **virtual environment** for managing dependencies.  

### **Step 1: Create a Virtual Environment**  
Using **Conda**, create and activate an environment:  
```sh
conda create -n breast-cancer-diagnosis python=3.10  
conda activate breast-cancer-diagnosis  
```  

### **Step 2: Install Dependencies**  
Install all required Python packages using:  
```sh
pip install -r requirements.txt  
```  
This will install **Streamlit, OpenCV, scikit-image**, and other necessary dependencies.  

## **Usage**  
To launch the app, run:  
```sh
streamlit run app/main.py  
```  
This will open the app in your **default web browser**.  

- Upload an image of cell samples.  
- Adjust settings for analysis.  
- View the predicted **diagnosis** and **probability**.  
- Export results to a CSV file for further study.  

## **License**  
This project is for **educational purposes only** and should not be used for clinical diagnosis.  

---

Let me know if you need any modifications! 🚀
