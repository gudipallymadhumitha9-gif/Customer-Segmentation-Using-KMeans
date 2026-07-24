# Customer Segmentation Using K-Means Clustering

## Project Overview
This project performs customer segmentation using Unsupervised Learning techniques. It analyzes customer transaction data and groups customers with similar purchasing behavior using K-Means clustering.

## Objectives
- Clean and preprocess the dataset.
- Convert categorical variables into numerical format.
- Standardize the data.
- Reduce dimensionality using Principal Component Analysis (PCA).
- Determine the optimal number of clusters using the Elbow Method and Silhouette Score.
- Apply K-Means clustering.
- Visualize and analyze customer segments.

## Technologies Used
- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- OpenPyXL

## Dataset
The project uses a retail customer transaction dataset containing:
- Product
- Quantity
- Unit Price
- Payment Method
- Order Status
- Items in Cart
- Coupon Code
- Referral Source
- Total Price
- Year
- Month
- Day

## Project Workflow
1. Import libraries
2. Load the dataset
3. Data preprocessing
4. Handle missing values
5. Encode categorical features
6. Standardize the data
7. Apply PCA
8. Find the optimal number of clusters using the Elbow Method
9. Evaluate clusters using the Silhouette Score
10. Perform K-Means clustering
11. Visualize customer segments
12. Save the clustered dataset

## Files
- `Customer Segmentation.ipynb` – Jupyter Notebook containing the complete implementation.
- `Dataset for Data Analytics.xlsx` – Input dataset.
- `Customer_Segmentation_Output.xlsx` – Output dataset with assigned clusters.

## Results
The project successfully segments customers into different groups based on purchasing behavior. These segments can be used for targeted marketing, customer analysis, and business decision-making.

## Author
Madhumitha Gudipally