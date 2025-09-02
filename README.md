# Maji Ndogo Water Project 💧

##  Project Overview
The **Maji Ndogo Water Project** focuses on assessing the **integrity and accuracy of water services data** collected by surveyors compared to an independent auditor’s report.  
The goal is to identify inconsistencies, biases, and potential errors in the dataset to ensure reliable information for **decision-making, governance, and resource allocation**.

This project combines **SQL-based data analysis** with **Python-driven exploration** to validate data quality and uncover insights.

---

##  Key Objectives
- Assess the **accuracy of field data** collected by surveyors.  
- Compare **auditor reports** against raw survey data.  
- Identify **biases, inconsistencies, and anomalies** in the dataset.  
- Provide a framework for **transparent monitoring** of water services.  

---


##  Project Structure
    ``` bash

  ├── Mcq3.ipynb      
  ├── data/            
  ├── README.md

--- 

##  Setup & Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/your-username/maji-ndogo-water-project.git
   cd maji-ndogo-water-project
   
2. Create a virtual environment
    ```bash

   conda create -- name environment_name
   conda activate environment_name
   pip install -r requirements.txt
    
3. To add the environment to jupyter notebook
    ```bash
    conda install -c anaconda ipykernel
    python -m ipykernel install --user--name = environment_name

4. Database setup
Ensure you have MySQL running and update the connection string in the notebook:

        %sql "mysql+pymysql://<username>:<password>@localhost:3306/md_water_services"

---

## Results & Insights

Identified systematic differences between auditor and surveyor scores.

Highlighted potential areas of bias in reporting.

Developed a reproducible workflow for future audits.







