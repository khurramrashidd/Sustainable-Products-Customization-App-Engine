# Sustainable Products Customization App Engine

A Python-based data application designed to explore, visualize, and recommend eco-friendly products. Built with Streamlit and FastAPI, this engine allows users to interactively analyze sustainable product datasets and receive customized recommendations.

**Live Demo:** [https://sustainable-customization-app-engine.streamlit.app/](https://sustainable-customization-app-engine.streamlit.app/)

## ⚙️ Features & Functionality
* **Interactive Dashboard (`home.py` & `main.py`):** A Streamlit frontend that provides users with an intuitive interface to navigate eco-friendly product categories.
* **Data Visualization (`data_Visual.py`):** Generates dynamic charts and graphs to illustrate product sustainability metrics, pricing, and environmental impact based on the included dataset.
* **Product Customization & Recommendation (`product_refine.py`):** Implements logic to filter, refine, and recommend products tailored to user preferences and sustainability criteria.
* **API Integration (`fast.py`):** Includes a FastAPI backend structure to handle data requests and serve recommendation endpoints.

## 🛠 Tech Stack
* **Language:** Python
* **Frontend/UI:** Streamlit (`main.py`, `home.py`)[cite: 4]
* **Backend/API:** FastAPI (`fast.py`)[cite: 4]
* **Data Handling:** Pandas (processing `eco_friendly_product5.csv` and `eco_friendly_product_recommendation_data_consistent_names.csv`)[cite: 4]

## 🚀 Getting Started
1. Clone the repository.
2. Install the required dependencies: `pip install -r requirements.txt` (or `req.txt`)[cite: 4].
3. Run the setup script if necessary: `sh setup.sh`[cite: 4].
4. Start the Streamlit app locally: `streamlit run main.py`[cite: 4].
