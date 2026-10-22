# BCG Financial Chatbot 🤖

A rule-based financial chatbot developed using Python and Pandas as part of the **BCG GenAI Job Simulation on Forage**.

The chatbot answers predefined questions about the financial performance of Microsoft, Apple, and Tesla using financial data from 2023 to 2025.

## 🚀 Features

* Retrieves company revenue and net income.
* Displays total assets and liabilities.
* Provides operating cash flow information.
* Compares revenue across consecutive years.
* Uses rule-based logic to match questions with financial data.
* Handles unsupported questions with helpful messages.
* Supports interactive command-line conversations.

## 🛠️ Technologies Used

* Python
* Pandas
* CSV
* Jupyter Notebook

## 📂 Project Files

| File                   | Description                           |
| ---------------------- | ------------------------------------- |
| `financial_chatbot.py` | Main chatbot implementation           |
| `financial_data.csv`   | Financial dataset for three companies |
| `requirements.txt`     | Python dependencies                   |
| `test_results.txt`     | Chatbot test questions and outputs    |
| `README.md`            | Project documentation                 |

## ⚙️ Installation and Usage

**1. Clone the repository**

```bash
git clone https://github.com/mahevish05/BCG-Financial-Chatbot.git
```

**2. Open the project folder**

```bash
cd BCG-Financial-Chatbot
```

**3. Install dependencies**

```bash
pip install -r requirements.txt
```

**4. Run the chatbot**

```bash
python financial_chatbot.py
```

Ensure that `financial_chatbot.py` and `financial_data.csv` are in the same folder.

## 💬 Example Questions

```text
What is Microsoft's revenue?
Apple revenue 2025
What is Tesla's net income?
What are Apple's total assets?
What are Microsoft's liabilities?
What is Tesla's operating cash flow?
How did Apple's revenue change in 2025?
help
exit
```

## 🧠 How It Works

1. Loads financial data from a CSV file using Pandas.
2. Accepts a user's question.
3. Matches keywords using conditional statements.
4. Retrieves the corresponding financial information.
5. Calculates revenue changes when requested.
6. Returns an answer or an unsupported-query message.

## ⚠️ Limitations

* Uses predefined keyword matching rather than advanced AI or NLP.
* Supports only the companies and metrics available in the dataset.
* Does not fetch live financial information.
* Its answers depend on the accuracy of the dataset.

## 🔮 Future Improvements

* Add more companies and financial metrics.
* Improve question recognition using NLP.
* Build a web interface with Streamlit or Flask.
* Add charts for financial comparisons.
* Integrate reliable financial data APIs.

## 🎓 Project Information

Developed as part of the **BCG GenAI Job Simulation on Forage** for practical learning in financial data analysis and rule-based chatbot development.

This is an educational prototype, not an official BCG product or financial advisory tool.

## 👩‍💻 Author

**Mahevish Fatema**

GitHub: [mahevish05](https://github.com/mahevish05)

**Repository:** [BCG-Financial-Chatbot](https://github.com/mahevish05/BCG-Financial-Chatbot)
