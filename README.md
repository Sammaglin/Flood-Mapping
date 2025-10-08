# 🛰️ Sentinel-1 SAR Data Analysis using Google Earth Engine  

This project demonstrates how to use **Google Earth Engine (GEE)** and **Sentinel-1 SAR data** to analyze water bodies using the **Normalized Difference Water Index (NDWI)**.  
It allows users to interactively select their **Area of Interest (AOI)**, define a **date range**, and visualize the results directly in **Google Colab**.

---

## 🚀 Features  

- 🌍 Interactive AOI selection using map tools  
- 🗓️ Custom date range filter for Sentinel-1 data  
- 🧮 NDWI computation for water body detection  
- 📈 NDWI time-series visualization  
- 🗺️ Export processed results (optional) to Google Drive  
- 🔑 Earth Engine authentication handled directly in Colab  

---

## 🧠 How It Works  

1. **Authenticate** your Earth Engine account when prompted.  
2. **Draw AOI** on the interactive map to select your region.  
3. **Set date range** to filter Sentinel-1 imagery.  
4. **Run analysis** to compute NDWI and visualize water distribution.  
5. (Optional) **Export** the final NDWI map clipped to your AOI.  

---

## 🧩 Libraries Used  

- [Google Earth Engine (ee)](https://developers.google.com/earth-engine)  
- [Geemap](https://geemap.org/)  
- [Folium](https://python-visualization.github.io/folium/)  
- [Matplotlib](https://matplotlib.org/)  
- [Pandas](https://pandas.pydata.org/)  

---

## 📦 Installation  

You can run this notebook directly in **Google Colab** — no setup required.  
Simply click the button below 👇  

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1IeVrm8pZ8-W8oq2KhrGB7x3LymdQCX85#scrollTo=Dv8hH7BGZX_Q)


---

## 📊 Example Output  

- NDWI map showing water bodies in the selected AOI  
- NDWI variation graph over time  
- Exported image clipped to AOI (optional)

---

## 🧭 Project Objective  

To create a simple, beginner-friendly **GIS data processing workflow** using **Sentinel-1 SAR data** for environmental monitoring and surface water detection.

---

## 🧑‍💻 Author  

**Ansh Upadhyay**  
M.Sc. Geo-Information & Remote Sensing  
Amity Institute of Geoinformatics and Remote Sensing  

---

## 🪪 License  

This project is licensed under the **MIT License** – feel free to use and modify with credit.

---
