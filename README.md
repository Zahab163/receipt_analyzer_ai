# Receipt Analyzer

A Python-based tool for analyzing receipts, categorizing expenses, and generating budgeting insights.  
This project demonstrates a workflow from OCR → Expense Categorization → Analysis → AI-style Guidance (simulated).

## Features
- **Receipt Input**: Accepts receipt data in CSV format (`item, price, quantity`).
- **Expense Categorization**: Automatically groups items into categories (dairy, bakery, meat, snacks, other).
- **Spending Breakdown**: Calculates totals per category and overall spending.
- **AI-Style Guidance (Simulated)**: Provides budgeting advice based on spending distribution without requiring an API key.
- **Visualization Ready**: Outputs structured data suitable for charts and tables.

## Installation
Clone the repository and install dependencies:
```bash
git clone https://github.com/yourusername/receipt-analyzer.git
cd receipt-analyzer
pip install -r requirements.txt

Usage
Run the analyzer script:
python analyzer.py

python analyzer.py

Example receipt data (receipt.csv):
item,price,quantity
milk,2.5,1
bread,3.6,1
chicken,6.0,1
chips,9.0,1

AI-Powered Financial Guidance (Simulated):
You spent the most on snacks ($9.00), which is 42.7% of your total spending.
Consider reducing snacks purchases to balance your budget.
Try setting a weekly budget for discretionary categories like snacks.

Requirements
- Python 3.8+
- pandas
- matplotlib (optional, for visualization)
License
MIT License

