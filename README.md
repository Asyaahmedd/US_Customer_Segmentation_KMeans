# Customer Segmentation in the US using KMeans

In today's business landscape, understanding our customers and tailoring our strategies to their unique preferences is essential for success.
Our project employs K-means clustering, a cutting-edge machine learning technique, to group customers with similar characteristics, enabling us to:

- **Personalize Marketing**: Target our audience with precision, leading to higher engagement and conversion rates.
- **Optimize Products and Services**: Tailor offerings to meet specific customer demands, boosting satisfaction and loyalty.
- **Enhance Customer Experience**: Provide better service and improve user experiences by understanding customer preferences.
- **Maximize Profitability**: Allocate resources efficiently by focusing on high-value customer segments.
- **Discover Market Opportunities**: Identify new customer segments for business expansion.

## Notebooks

This project is organized into three notebooks:
1. **Data_exploration.ipynb:** This notebook focuses on exploring and understanding the dataset. It includes data cleaning, preprocessing, and visualization.

2. **Clustering_using_two_features.ipynb:**This notebook focuses on performing KMeans clustering using two features from the dataset. It includes data preprocessing, model training, and visualization of the clusters.

3. **Multivariate_Clustering_in_CFS_Analysis.ipynb:** This notebook applies multivariate clustering in the analysis of the Consumer Finances Survey data. It includes advanced techniques for dimensionality reduction and visualization.

## Dataset

The dataset used in this project is from the 2019 Survey of Consumer Finances (SCF). The SCF is a triennial survey conducted by the Federal Reserve Board that collects information about family incomes, net worth, credit use, and other financial outcomes. A new dataset is released every three years. You can access the dataset from the 
[Federal Reserve Board's website](https://www.federalreserve.gov/econres/scfindex.htm).

## Results

The performance of the clustering was evaluated using both silhouette and Inertia scores. The elbow method was utilized to ascertain the most suitable number of clusters.

Our analysis revealed that customers can be effectively segmented into distinct groups. This was particularly evident for households that had previously been denied credit or those that expressed concerns about potential credit rejection. These specific clusters could signify a range of financial behaviours among households dealing with credit-related issues.

A scatter plot was used to visually depict our findings, clearly demonstrating the division of customers into various distinct groups.
## Usage

To run the notebooks and perform customer segmentation on your own, follow these steps:

1. Clone this repository to your local machine:

   `https://github.com/Asyaahmedd/US_Customer_Segmentation_KMeans.git`


2. Install the required dependencies (see the [Dependencies](#dependencies) section).

3. Open and run the notebooks using Jupyter Notebook or any other compatible environment.

4. Follow the instructions and comments within each notebook to perform the segmentation analysis.

5. Experiment with different features or parameters to refine the segmentation results according to your specific business needs.

## Dependencies

Make sure you have the following Python packages installed:

- NumPy
- pandas
- scikit-learn
- matplotlib
- seaborn
- Jupyter Notebook

You can install these packages using pip:

```bash
pip install numpy pandas scikit-learn matplotlib seaborn jupyter


