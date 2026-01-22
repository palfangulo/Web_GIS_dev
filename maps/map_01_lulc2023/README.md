# 🌍 WebGIS Portfolio Project

This project presents an interactive **WebGIS map** built using **Python (GeoPandas + Folium)** and deployed as a static website with **GitHub Pages**.

👉 **Live Map**  
🔗 https://palfangulo.github.io/WebGIS_dev/

---

## 🧭 Workflow (Short)

- Prepare spatial data in **Python**
  - Reproject to **EPSG:4326**
  - Simplify geometries to reduce file size
- Create an interactive map using **Folium (`gdf.explore()`)**
- Export the map to HTML
- Embed and deploy the WebGIS using **GitHub Pages**

---

## 📂 Repository

- Source code and data:  
  🔗 https://github.com/palfangulo/WebGIS_dev

---

## 🧠 Notes

- GitHub Pages has a **25 MB file size limit**
- Web maps require **WGS84 (EPSG:4326)**
- Folium maps are embedded using an **iframe** to avoid JavaScript conflicts
- For larger datasets, consider **TopoJSON + pure Leaflet**

---

## 🏷️ Tags

`Portfolio` `WebGIS` `GIS` `Python` `GeoPandas` `Folium` `GitHubPages`
