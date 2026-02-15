

# 📊 Smart Receipt Spending Analyzer  

A Python-based tool for analyzing receipts, categorizing expenses, and generating budgeting insights.  
This project demonstrates a workflow from **OCR → Expense Categorization → Analysis → AI-style Guidance → LLM-powered Advice**.  

🔗 [Try the interactive demo on PartyRock](https://partyrock.aws/u/Zahab163/cZx-YcWaQ/Smart-Receipt-Spending-Analyzer)
[LIVE EMO}(https://youtu.be/Ok6dTDxbsaU)
---

## ✨ Features
- **Receipt Input**: Accepts receipt data in CSV format (`item, price, quantity`).  
- **Expense Categorization**: Automatically groups items into categories (dairy, bakery, meat, snacks, other).  
- **Spending Breakdown**: Calculates totals per category and overall spending.  
- **AI-Style Guidance (Simulated)**: Provides budgeting advice based on spending distribution without requiring an API key.  
- **LLM + Prompt Engineering**: Uses structured prompts to generate personalized financial guidance.  
- **Visualization Ready**: Outputs structured data suitable for charts and tables.  

---

## ⚙️ Installation
Clone the repository and install dependencies:
```bash
git clone https://github.com/yourusername/receipt-analyzer.git
cd receipt-analyzer
pip install -r requirements.txt
```

---

## ▶️ Usage
Run the analyzer script:
```bash
python analyzer.py
```

---

## 📄 Example Receipt Data (from Colab OCR Analyzer)
```csv
item,price,quantity
milk,2.5,1
bread,3.6,1
chicken,6.0,1
chips,9.0,1
```

---

## 🤖 AI-Powered Financial Guidance
**Simulated Output (Prompt-engineered with LLM):**
```
You spent the most on snacks ($9.00), which is 42.7% of your total spending.
Consider reducing snacks purchases to balance your budget.
Try setting a weekly budget for discretionary categories like snacks.
```

---

## 🧠 How LLM + Prompt Engineering Was Used
- **Step 1: OCR Extraction** → Receipts parsed into structured CSV format.  
- **Step 2: Categorization** → Items grouped into spending categories.  
- **Step 3: Prompt Engineering** →  
   - Designed prompts like:  
     *"Given this spending breakdown, provide budgeting advice in 2–3 sentences highlighting the largest category and suggesting actionable steps."*  
   - Ensured outputs were **concise, actionable, and personalized**.  
- **Step 4: LLM Guidance** → Generated financial insights that mimic a budgeting assistant.  

---

## 📊 Example Spending Breakdown
| Category | Total | % of Spending |
|----------|-------|---------------|
| Dairy    | $2.50 | 11.9% |
| Bakery   | $3.60 | 17.1% |
| Meat     | $6.00 | 28.3% |
| Snacks   | $9.00 | 42.7% |

---

## 📜 Requirements
- Python 3.8+  
- pandas  
- matplotlib (optional, for visualization)  

---

## 📄 License
MIT License  

