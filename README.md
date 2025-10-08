# 🌊 Flood Mapping using Sentinel-1 SAR Data (Google Earth Engine)

This Jupyter Notebook (`Flood_MappingV2.ipynb`) performs **flood mapping and water body detection** using **Sentinel-1 SAR imagery** processed through **Google Earth Engine (GEE)**.  
It leverages the **Normalized Difference Water Index (NDWI)** to delineate flooded or water-covered areas within a user-defined **Area of Interest (AOI)**.

---

## 🚀 Features

- 🔍 Interactive AOI selection on an embedded map  
- 📅 Custom date range filtering for Sentinel-1 data  
- 🛰️ Automatic preprocessing (orbit, polarization, and speckle filtering)  
- 🌊 NDWI computation and thresholding for water detection  
- 🗺️ Interactive visualization using **geemap** and **folium**  
- 💾 Optional export of processed layers to **Google Drive**

---

## 🧰 Requirements

Make sure you have the following Python libraries installed:

```bash
pip install geemap ee folium ipywidgets matplotlib pandas
```

> 💡 You will also need an active **Google Earth Engine account**:  
> [https://earthengine.google.com/signup/](https://earthengine.google.com/signup/)

---

## ⚙️ How to Use

### 1. Open the Notebook
- Launch **Jupyter Notebook** or **Google Colab**.  
- Upload the file: `Flood_MappingV2.ipynb`.

### 2. Install Dependencies
- Run the first cell to install all required packages.

### 3. Authenticate Google Earth Engine
- Follow the link shown in the output.  
- Log in with your Google account.  
- Copy and paste the authentication code back into the notebook.

### 4. Define Area of Interest (AOI)
- Use the drawing tools on the interactive map to select your study region.

### 5. Set Date Range
- Input your desired **start date** and **end date** for Sentinel-1 imagery.

### 6. Run Analysis
- Execute the remaining cells to compute NDWI and visualize the water body detection results.

### 7. View Results
- Water bodies will appear as highlighted regions on the interactive map.  
- Optionally, export the processed NDWI raster to your **Google Drive**.

---

## 📦 Libraries Used

| Library | Purpose |
|----------|----------|
| `geemap` | Interactive visualization and GEE integration |
| `ee` | Access to Google Earth Engine API |
| `folium` | Map rendering and interaction |
| `ipywidgets` | User interface controls |
| `matplotlib`, `pandas` | Charting and data handling |

---

## 🧠 Notes & Tips

- If maps fail to display, restart the kernel and re-run all cells.  
- Use smaller AOIs and shorter date ranges for faster processing.  
- Ensure your Google Earth Engine account is authenticated and active.  
- Results can vary based on orbit direction and polarization selection.

---

## 📁 Output

- **Interactive Map:** Displays Sentinel-1 NDWI layer highlighting flooded regions.  
- **Optional Export:** NDWI raster to Google Drive in GeoTIFF format.

---

## 👩‍💻 Author

Developed for **flood detection and water resource mapping** using open-source satellite data and cloud-based processing tools.

---

## 📜 License

This notebook is released under the [MIT License](https://opensource.org/licenses/MIT).
