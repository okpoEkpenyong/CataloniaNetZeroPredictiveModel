
---

# **Catalonia Net Zero Prediction Project**  

This project aims to analyze and predict building energy performance in **Catalonia**, focusing on **cost-effective renovation strategies** to support net-zero goals. The workflow includes **exploratory data analysis (EDA), feature engineering, machine learning modeling, and strategic recommendations** based on energy savings and financial viability.

---

## **Project Structure**  

```
19_net_zero_buildings_prediction
├── .env                                     # Environment variables (not included in the repo)
├── .gitignore                               # Files and directories to exclude from version control
├── LICENSE                                  # License file
├── README.md                                # Project overview
├── requirements.txt                         # Project dependencies
├── configs                                  # Configuration files
│   └── config.yaml                          # Paths and settings
├── datasets                                 # Raw and processed data (excluded from the repo)
│   ├── raw                                  # Raw datasets
│   └── processed                            # Cleaned and prepared datasets
├── docs                                     # Documentation
│   ├── reports                              # Reports and analysis outputs
│   │   ├── figures
│   │   └── final_reports.md
│   ├── high_level_architecture.md
│   ├── api_reference.md
│   └── workflow.md                          # Workflow details
├── models                                   # Model artifacts and checkpoints
│   ├── checkpoints
│   └── final
├── notebooks                                # Jupyter notebooks for EDA, modeling, and analysis
│   ├── 01_load_process_init(ireland).ipynb
│   ├── 02_load_process_init(catalonia).ipynb
│   ├── 03_model_evaluate_tune_interpret.ipynb
```

---

## **Getting Started**  

### **1. Clone the Repository and Set Up the Virtual Environment**  

```bash
git clone https://github.com/okpoEkpenyong/CataloniaNetZeroPredictiveModel
cd 19_net_zero_buildings_prediction
```

Create and activate a virtual environment:  

```bash
python3 -m venv net_zero_env
source net_zero_env/bin/activate  # On Windows, use `net_zero_env\Scripts\activate`
```

---

### **2. Configure Paths and Project Files**  

Ensure that the datasets are placed in the following directory:  

```
datasets/
├── raw/         # Contains the original data files
└── processed/   # Contains cleaned and feature-engineered data
```

---

### **3. Install Dependencies**  

Install the required Python packages:  

```bash
pip install -r requirements.txt
```

Install additional modules if needed.

---

### **4. Run Jupyter Notebooks**  

Navigate to the `notebooks/` directory and execute the notebooks **in sequence**:  

- `01_load_process_init(ireland).ipynb`
- `02_load_process_init(catalonia).ipynb`
- `03_model_evaluate_tune_interpret.ipynb`

To start Jupyter Notebook:  

```bash
jupyter notebook
```

---

## **Key Features**  

- **Exploratory Data Analysis (EDA):** Understand building energy efficiency patterns across Catalonia.  
- **Machine Learning Models:** Predict energy consumption and assess renovation effectiveness.  
- **Cost-Effectiveness Analysis:** Evaluate the return on investment (ROI) for different renovation types.  
- **Geospatial Analysis:** Map energy efficiency trends across regions and climate zones.  
- **Policy Recommendations:** Identify strategic measures to accelerate net-zero building renovations.  

---

## **License**  

This project is licensed under the **MIT License**. See the `LICENSE` file for details.

---

## **Contributing**  

We welcome contributions! Please **fork the repository**, create a new branch, and submit a **pull request** for review.

---

## **Contact**  

For questions or collaboration, reach out to:  

📧 **okpo.ekpenyong@gmail.com**


---

