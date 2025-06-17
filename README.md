🛰️ Deforestation Tracking using Google Earth Engine

This notebook utilizes Google Earth Engine (GEE) to analyze and visualize deforestation over time using satellite data. It is part of an academic research initiative under the NNDL (Natural and Nature-Derived Learning) theme.

🌍 Key Features

- NDVI-based vegetation loss detection  
- Uses cloud-based processing (GEE)  
- Reproducible analysis with minimal local setup  
- Works with any region on the map by modifying coordinates  

⚙️ Getting Started

1. Sign up at [earthengine.google.com](https://earthengine.google.com)  
2. Install dependencies:  
   pip install earthengine-api geemap
3. Authenticate Earth Engine:  
   earthengine authenticate  
4. Open the Jupyter notebook and run the cells  

🧱 Folder Structure

Deforestation-Tracking-GEE/
├── notebooks/
│   └── Deforestation_Tracking_NNDL.ipynb
├── README.md
└── requirements.txt


🚀 Future Plans

- Add visual map outputs to `assets/screenshots/`  
- Deploy to a simple Streamlit app  
- Allow dynamic region selection and historical time sliders  

