# **🧬 CFTR Clinical Mutation Analysis & Structural Visualization**

This project explores the **CFTR gene**—a gene implicated in cystic fibrosis—through a dual-lens approach of **clinical mutation analysis** and **protein domain visualization**. It integrates mutation data from [ClinVar](https://www.ncbi.nlm.nih.gov/clinvar/) and structural mapping using **Chimera**, with interactive dashboards built using **Power BI** and analytical preprocessing done in **Python**.

## **📌 Project Objective**

To **identify and visualize pathogenic mutations** in the CFTR gene, map them to structural domains using 3D visualization tools, and build a domain-wise **interactive dashboard** to support clinical research and mutation impact interpretation.

## 🧪 Tools & Technologies

- Python (`pandas`, `openpyxl`) | Data preprocessing, cleaning, and formatting 
- UCSF Chimera | 3D protein structure visualization of CFTR (PDB: `6MSM`) 
- Power BI | Interactive dashboard creation (mutations vs. domain, clinical significance, hover tooltips, image scroll) 

## 📖 **Data Source**

**ClinVar** – [https://www.ncbi.nlm.nih.gov/clinvar/](https://www.ncbi.nlm.nih.gov/clinvar/)

**CFTR Protein (PDB: 6MSM)** – [https://www.rcsb.org/structure/6MSM](https://www.rcsb.org/structure/6MSM)

## 🖼️ **Project Screenshots**

 📊 Interactive Dashboard View
![Power BI Dashboard Screenshot](./preview.png)

 🔴 Chimera-Based Mutation Render (Residue F508)
![Chimera Mutation Example](./chimera-images/F508.png)

## **🚀 How to Run the Project**

- Clone or download this repository
- Open CFTR Clinical Mutation Data.ipynb in Jupyter or VS Code to explore the data transformation.
- View protein domain images in /images (extracted via UCSF Chimera).
- Open CFTR_Clinical_Dashboard.pbix in Power BI Desktop to explore the interactive visualizations.

## **⚠️ Note**

- Due to Power BI restrictions, direct online hosting is unavailable. You can:
- [🔽 Download the Power BI File (.pbix)](https://drive.google.com/file/d/18bHaCOpzD3-H3Q6vKnTc269fQlquQqmY/view)
- Open locally using [Power BI Desktop](https://powerbi.microsoft.com/en-us/desktop/)




