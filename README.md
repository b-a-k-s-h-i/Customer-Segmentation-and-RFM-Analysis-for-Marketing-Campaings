# Customer Segmentation & RFM Analysis

This project performs Customer Segmentation and RFM (Recency, Frequency, Monetary) Analysis for Marketing Campaigns using an Online Retail dataset. It is primarily built with Python (Jupyter Notebooks) and integrated with Power BI.

## Project Structure
- `Python code/` - Contains the Jupyter Notebook with the data cleaning, feature engineering, and KMeans clustering logic.
- `Datasets/` - Contains the raw dataset `Online Retail.xlsx` and the output clustered data `segmented_customer_data.csv`. (Note: Due to size constraints, datasets are not committed to Git).
- `Power Bi/` - Contains the Power BI dashboard (`.pbix` file) for visualizing the RFM segments.

## Setup Instructions

1. **Install Dependencies**
   It's recommended to create a virtual environment, then install the necessary packages using:
   ```bash
   pip install -r requirements.txt
   ```

2. **Dataset Paths**
   Before running the `Customer_Segmentation_RFM_Analysis.ipynb` notebook, ensure you update the paths for loading the dataset and saving the output CSV. Currently, they might be using absolute paths that need to be pointed to your local `Datasets/` folder.

3. **Run the Notebook**
   Open Jupyter Notebook or JupyterLab and execute the notebook cells sequentially to process the data and assign RFM segments to customers.

4. **Power BI Dashboard**
   Open the `.pbix` file in Power BI Desktop to view the visual insights. Ensure the data source points to the freshly generated `segmented_customer_data.csv`.
