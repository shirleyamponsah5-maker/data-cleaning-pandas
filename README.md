# data-cleaning-pandas
Shark Attack Risk Analysis

This project explores historical shark attack data to identify patterns related to location, time, victim demographics, activities, and attack outcomes.

The work is divided into three main stages: understanding the dataset, cleaning the data, and performing exploratory analysis to uncover trends and potential risk factors.

Project Structure

├── structure.ipynb
├── cleaning.ipynb
├── shark_analysis.ipynb
├── sharks_df.csv
├── clean_shark_df.csv
├── Shark Attack Risk Analysis.pptx
└── README.md

Notebooks

*structure.ipynb*

This notebook is used to explore the raw dataset and understand its structure. It includes:

- Initial inspection of the data
- Dataset dimensions and column information
- Data type analysis
- Missing value assessment
- General data quality checks

*cleaning.ipynb*

This notebook contains the data cleaning process. Tasks include:

- Handling missing values
- Standardising inconsistent entries
- Cleaning the Age column
- Fixing formatting issues
- Removing unnecessary information where appropriate

The output of this step is:

- clean_shark_df.csv

- shark_analysis.ipynb

This notebook focuses on exploratory data analysis and insight generation.

Additional variables are created to support the analysis:

- case_count – counts each incident as a single case
- is_fatal – binary indicator for fatal and non-fatal incidents
- age_buckets – grouped age ranges for demographic analysis

The notebook explores:

- Trends over time
- Geographic distribution of attacks
- Victim demographics
- Activities associated with attacks
- Fatality patterns
- Shark species information where available

Dataset

The original dataset contains 7,090 shark attack records across 23 columns.

Some of the key variables include:

Column	Description
Date	Date of the incident
Year	Year of the incident
Country	Country where the incident occurred
Location	Specific location
Activity	Activity being performed at the time
Sex	Victim sex
Age	Victim age
Injury	Description of injuries
Fatal Y/N	Whether the incident was fatal
Species	Shark species involved (when identified)

Workflow

sharks_df.csv
      ↓
structure.ipynb
      ↓
cleaning.ipynb
      ↓
clean_shark_df.csv
      ↓
shark_analysis.ipynb
      ↓
Findings and presentation

Tools Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

Running the Project

Install the required libraries:

pip install pandas numpy matplotlib seaborn jupyter

Launch Jupyter Notebook:

jupyter notebook

Run the notebooks in the following order:

1. structure.ipynb
2. cleaning.ipynb
3. shark_analysis.ipynb

Project Presentation:

A pptx has been prepared to present the project. It can be found at the following link: https://docs.google.com/presentation/d/11mlr9fDjG3kvB9oTUlHLKAdmyKNFDGN4/edit

Project Output

The project produces:

- A cleaned dataset (clean_shark_df.csv)
- Exploratory analysis and visualisations
- Insights into shark attack patterns and risk factors
- A presentation summarising the main findings

Notes

- clean_shark_df.csv is generated during the cleaning process.
- Some variables in the original dataset contain missing or inconsistent values.
- Age groups are created during the analysis stage to simplify demographic comparisons.
- The PowerPoint presentation contains a summary of the key findings and visualisations.