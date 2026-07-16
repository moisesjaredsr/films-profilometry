# Thin Film Profilometry Analyzer 🔬

[![Streamlit App](https://static.streamlit.io/badges/streamlit_badge_black_white.svg)](https://film-profilometry.streamlit.app/)

![App Screenshot]
<img width="1770" height="872" alt="image" src="https://github.com/user-attachments/assets/b25ce0c8-6f6c-4a63-885a-ff557cf160ef" />


## 📌 Overview
This Streamlit-based web application is engineered to automate the visualization and processing of surface topography data extracted from mechanical or optical profilometers. Designed for thin-film characterization in materials science, it seamlessly parses XML-structured `.txt` output files to generate interactive comparative dashboards and export publication-ready data.

## 🔬 Scientific Features
* **Custom XML Data Parsing:** Utilizes `xml.etree.ElementTree` to reliably extract exact **X** (Distance) and **Z** (Height) coordinates from proprietary equipment data structures.
* **Topological Axis Control:** Features global and local axis-inversion capabilities, a critical function for correcting orientation mismatches often produced by raw profilometer exports.
* **Interactive Comparative Dashboards:** Superimposes multiple sample profiles using Plotly, allowing for direct visual comparison of film thickness and surface topography across different experimental batches.
* **Advanced Data Export:** Generates `.xlsx` reports complete with raw data matrices and **natively editable Excel scatter charts** (injected via `xlsxwriter`), eliminating the need for manual plotting in external software.

## 🛠️ Tech Stack
* **Language:** Python 3.13
* **Framework:** Streamlit
* **Data Processing:** Pandas, XML ElementTree
* **Visualization:** Plotly (Interactive Web), XlsxWriter (Native Excel Charts)

## 🚀 Usage
Upload raw XML-structured `.txt` or `.xml` measurement files. Use the global settings to label your axes or invert them for proper orientation. Expand the specific details panel to isolate individual measurements and download single-sample `.xlsx` reports.
