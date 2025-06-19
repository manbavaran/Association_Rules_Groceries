# Association Rule Mining on Groceries Dataset

This project demonstrates association rule mining on the [Kaggle Groceries Dataset](https://www.kaggle.com/datasets/heeraldedhia/groceries-dataset) using Python. The main goal is to extract frequent itemsets and generate interpretable association rules from supermarket transaction data. The notebook also covers feature engineering steps such as extracting month, weekday, season, and holiday information, and discusses the practical implications of the resulting rules in retail analytics.

## Features

- Data preprocessing and cleaning
- Feature engineering (extracting month, weekday, season, and holiday columns)
- Grouping transactions by customer and date
- Applying the Apriori algorithm to find frequent itemsets
- Generating and interpreting association rules
- Example use-cases for business insight and recommendation

## Project Structure

Association_Rules_Groceries/
├── Association_Rules_Groceries.ipynb # Main Jupyter notebook with code and analysis
├── LICENSE # GPL v2 License
└── README.md # Project description and usage


## How to Use

1. **Clone this repository**  

git clone https://github.com/manbavaran/Association_Rules_Groceries.git
cd Association_Rules_Groceries

2. **(Optional) Set up a Python virtual environment**  

python -m venv venv
source venv/bin/activate # On Windows: venv\Scripts\activate
pip install -r requirements.txt

*(A requirements.txt file is recommended for reproducibility, e.g., pandas, mlxtend, holidays, etc.)*

3. **Open the notebook**  
You can run the notebook in [Google Colab](https://colab.research.google.com/) or locally with Jupyter Notebook:

jupyter notebook Association_Rules_Groceries.ipynb


4. **Upload the dataset**  
Download the `Groceries_dataset.csv` from [Kaggle](https://www.kaggle.com/datasets/heeraldedhia/groceries-dataset) and place it in the project directory.

5. **Follow the notebook**  
The notebook walks through data cleaning, feature engineering, association rule mining, and business interpretation.

## Requirements

- Python 3.7+
- pandas
- mlxtend
- holidays

Install required packages with:

pip install pandas mlxtend holidays


## Data Source

- **Groceries Dataset**  
  [Kaggle - Groceries Dataset](https://www.kaggle.com/datasets/heeraldedhia/groceries-dataset)  
  Provided under the GNU General Public License v2.0 (GPL-2.0)

## License

This project is licensed under the GNU General Public License v2.0.  
See [LICENSE](LICENSE) for more details.

---

**Acknowledgements:**  
Original dataset by Heeral Dedhia, available on [Kaggle](https://www.kaggle.com/datasets/heeraldedhia/groceries-dataset).

