# light_data_clean
I lightly clean data before uploading it to S3 AWS cloud for my extensive project. 
# Initial Data Cleaning for Insurance Dataset

## Overview
This Jupyter Notebook documents the initial steps taken to clean the insurance dataset obtained from Kaggle. The dataset is part of a larger project aimed at developing a Compliance Analytics Dashboard for the insurance industry, focusing on data related to individual demographics and insurance charges.

## Dataset Description
The dataset contains the following attributes for each policyholder:
- `age`: The age of the primary beneficiary
- `sex`: The gender of the primary beneficiary (male or female)
- `bmi`: Body mass index, providing an understanding of body weights that are relatively high or low relative to height
- `children`: The number of children/dependents covered by the insurance plan
- `smoker`: Smoking status of the beneficiary
- `region`: The beneficiary's area of residence in the US, divided into four geographic regions
- `charges`: Individual medical costs billed to health insurance

## Data Cleaning Steps
The following steps were executed for data cleaning:
1. **Loading the Data**: Importing the dataset into a Pandas DataFrame.
2. **Inspecting Data Types**: Verifying and correcting the data types of the dataset columns as necessary.
3. **Missing Values**: Checking for and addressing any missing data points.
4. **Duplicate Entries**: Identifying and removing any duplicate records to ensure the uniqueness of the dataset.
5. **Categorical Encoding**: Transforming categorical variables like `sex`, `smoker`, and `region` into a numerical format suitable for analytical models.

## Usage
To interact with the notebook:
1. Clone or download this repository to your local machine.
2. Open the notebook in Jupyter or an equivalent environment like Google Colab.
3. Install any necessary Python libraries such as Pandas, Matplotlib, and Seaborn.
4. Run the notebook cells in order to replicate the data cleaning process.

## Requirements
- Python 3.x
- Jupyter Notebook or Google Colab
- Pandas
- Matplotlib
- Seaborn

## Contributing
Contributions, issues, and feature requests are welcome.

## License
This project is available under the MIT License. See the license.md file for more details.

## Contact
If you have any questions or comments, please contact 42diyapatel@gmail.com.

## Acknowledgments
- Kaggle for providing the dataset used in this project.
- This notebook is part of a larger effort to develop a data-driven approach to compliance and risk management in the insurance sector.

## Project Status
The current state of the project is: _completed_ 
