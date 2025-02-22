# Glassdoor Data Science Job Analysis

## Project Overview
This project analyzes Glassdoor job listings to uncover trends and factors influencing data science salaries. We address data quality issues, handle class imbalance, and visualize key insights. The goal is to predict average salary estimates based on job-related attributes.

## Team Members
- Akash Pathak
- Medha Singh

## Dataset
The dataset contains 956 job listings primarily related to Data Science roles from Glassdoor, covering key job details like:
- Job Title
- Salary Estimate
- Job Description
- Company Information (Name, Size, Industry, Sector, Revenue)
- Location and Headquarters
- Glassdoor Rating

## Project Steps
1. **Data Cleaning:**
   - Handled missing values
   - Removed duplicates
   - Converted salary estimates into numeric values
2. **Exploratory Data Analysis:**
   - Visualized salary distributions and job trends
   - Created pair plots, heatmaps, and 3D visualizations
3. **Feature Engineering:**
   - Encoded categorical variables
   - Created new columns like "Founded Category"
4. **Handling Imbalanced Data:**
   - Applied SMOTE to balance salary categories
5. **Modeling:**
   - Split data into training and test sets
   - Trained models like Linear Regression and Random Forest
6. **Insights:**
   - Identified top factors affecting salaries
   - Analyzed company ratings and industry trends

## Visualizations
- Pair Plots
- Correlation Heatmaps
- 3D Salary vs. Rating vs. Size Plots
- Distribution of Salaries Before and After Balancing

## Technologies Used
- Python (Pandas, NumPy, Scikit-learn, TensorFlow)
- Visualization Libraries (Matplotlib, Seaborn)
- Data Balancing Techniques (SMOTE)
- Jupyter Notebook

## How to Run
1. Clone the repository:
   ```bash
   git clone <repo-url>
   ```
2. Navigate to the project directory:
   ```bash
   cd glassdoor-salary-analysis
   ```
3. Install required libraries:
   ```bash
   pip install -r requirements.txt
   ```
4. Open Jupyter Notebook and run the analysis:
   ```bash
   jupyter notebook
   ```

## Results
- Improved salary prediction accuracy
- Balanced dataset for fair model training
- Detailed insights into job market trends and factors influencing salaries

## Future Work
- Apply advanced machine learning models
- Include more job attributes for deeper analysis
- Deploy the model for real-time salary prediction

## Contact
- Akash Pathak: akash.pathak0123@gmail.com
- LinkedIn: [Akash Pathak](www.linkedin.com/in/akash-pathak-44a082212)
- Medha Singh: medhasinghdav017@gmail.com
- LinkedIn: https://www.linkedin.com/in/medha-singh-439a87212/

