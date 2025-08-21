# Missing-Data-Cleaner
Missing Data Cleaner is a simple Python tool to handle missing values in datasets. It detects gaps and fills them using methods like mean, median, or mode, ensuring your data is clean and ready for analysis.

✨Features

✔ Detects missing values in any dataset
✔ Fills gaps using Mean, Median, or Mode
✔ Outputs a cleaned dataset for analysis

🛠️ Technologies

Python

Pandas

NumPy

📂 Installation
# Clone the repository
git clone https://github.com/your-username/missing-data-cleaner.git

# Go to the folder
cd missing-data-cleaner

# Install dependencies
pip install pandas numpy

🚀 How to Use

Place your CSV file in the folder.

Run the script:

python missing_data_cleaner.py


Select the method to fill missing values (mean, median, or mode).

Get your cleaned dataset saved in the output file.

✅ Example
import pandas as pd
from missing_data_cleaner import clean_missing_data

df = pd.read_csv('clean dataset')
clean_df = clean_missing_data(df, method='mean')
print(clean_df.head())
