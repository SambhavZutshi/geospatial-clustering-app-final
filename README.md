# PROJECT–1  
## Attribute-Based Geospatial Clustering of San Diego Census Tracts  
### Using GeoPandas and K-Means (Streamlit Application)

---

## 📌 Project Overview
This project implements **attribute-based geospatial clustering** on census tract data of **San Diego** using **GeoPandas** and **K-Means clustering**.  
The goal is to identify census tracts with similar socio-economic characteristics and visualize the results through a **Streamlit web application**.

Unlike proximity-based clustering, this project focuses purely on **attribute similarity**, making it suitable for urban analysis, planning, and policy studies.

---

## 🎯 Objectives
- Perform attribute-based clustering on geospatial census data  
- Identify spatial patterns in socio-economic indicators  
- Visualize clustered census tracts on a map  
- Build an interactive and reproducible Streamlit application  

---

## 🗂️ Dataset
- **File Name:** `sandiego_tracts.gpkg`  
- **Format:** GeoPackage (.gpkg)  
- **Spatial Unit:** Census Tracts  
- **Geometry Type:** Polygon  

Each record represents a census tract along with multiple numerical attributes.

---

## 🛠️ Technologies Used
- Python  
- Streamlit  
- GeoPandas  
- Pandas  
- NumPy  
- Scikit-learn (K-Means)  
- Matplotlib  

---

## ⚙️ Methodology
1. Load geospatial census tract data using GeoPandas  
2. Select numerical attributes for clustering  
3. Handle missing values and standardize attributes  
4. Apply K-Means clustering algorithm  
5. Assign cluster labels to census tracts  
6. Visualize clustering results on a geospatial map  

---

## 🚀 How to Run the Application Locally

### 1️⃣ Install Dependencies
```bash
pip install -r requirements.txt
```

### 2️⃣ Run the Streamlit App
```bash
streamlit run app.py
```

The application will open in your browser at:
```
http://localhost:8501
```

---

## ☁️ Deployment
This application can be deployed using **Streamlit Cloud** via GitHub integration.

Required repository files:
- `app.py`
- `requirements.txt`
- `sandiego_tracts.gpkg`
- `README.md`

---

## 📊 Output
- Clustered census tract map  
- Cluster-wise summary statistics  
- Interactive selection of attributes and cluster count  

---

## ⚠️ Limitations
- K-Means requires pre-defining the number of clusters (K)  
- Spatial proximity is not explicitly considered  
- Results depend on selected attributes  

---

## 🔮 Future Enhancements
- Elbow Method for optimal K selection  
- Density-based clustering (DBSCAN / HDBSCAN)  
- Spatial weights integration  
- Interactive map visualizations  

---

## 🧠 Academic Use
This project is suitable for:
- Academic mini or major projects  
- Final-year submissions  
- Data science and GIS portfolios  

---

## 👤 Author
Developed as part of a **Geospatial Data Science project using Machine Learning**.
