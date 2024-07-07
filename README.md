# Placement Data Analysis Project

This project analyzes student placement data to predict placement status and salary using machine learning techniques.

## Author
- **Name:** Chirag Sindhwani
- **Branch:** Electrical Engineering
- **Roll No:** 23085130

## Table of Contents
- [Project Overview](#project-overview)
- [Installation](#installation)
- [Usage](#usage)
- [Data Description](#data-description)
- [Analysis Performed](#analysis-performed)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)

## Project Overview
This project uses a dataset containing student information and placement data to perform exploratory data analysis (EDA) and build predictive models. The main goals are to predict placement status and salary based on various student attributes.

## Installation

### Prerequisites
- Python 3.7+
- pip

### Clone the repository
```bash
git clone https://github.com/your-username/placement-data-analysis.git
cd placement-data-analysis
```

### Set up a virtual environment (optional but recommended)
```bash
python -m venv venv
source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
```

### Install required packages
```bash
pip install -r requirements.txt
```

## Usage
1. Ensure you have the dataset file `Placement_Data_Full_Class.csv` in the project directory.
2. Run the Jupyter notebook:
   ```bash
   jupyter notebook Placement_Data_Analysis.ipynb
   ```
3. Follow the notebook cells to perform the analysis and see the results.

## Data Description
The dataset `Placement_Data_Full_Class.csv` contains the following features:
- sl_no: Serial Number
- gender: Gender of the student
- ssc_p: Secondary Education percentage (10th Grade)
- ssc_b: Board of Education (Central/ Others)
- hsc_p: Higher Secondary Education percentage (12th Grade)
- hsc_b: Board of Education (Central/ Others)
- hsc_s: Specialization in Higher Secondary Education
- degree_p: Degree Percentage
- degree_t: Undergraduate Degree (Comm&Mgmt/ Sci&Tech/ Others)
- workex: Work Experience (Yes/ No)
- etest_p: Employability test percentage
- specialisation: Post Graduation Specialization (Mkt&Fin/ Mkt&HR)
- mba_p: MBA percentage
- status: Placement Status (Placed/ Not Placed)
- salary: Salary offered by corporate (if placed)

## Analysis Performed
1. Data Preprocessing
2. Exploratory Data Analysis (EDA)
3. Logistic Regression for predicting placement status
4. Linear Regression for predicting salary

## Results
- Logistic Regression Accuracy: 0.84
- Linear Regression R-squared: -0.17 (Note: The negative R-squared value suggests that the model needs improvement)

## Contributing
Contributions are welcome! Please feel free to submit a Pull Request.

## License
This project is open source and available under the [MIT License](LICENSE).
