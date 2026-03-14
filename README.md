# Food Orders Analysis

This repository contains a Jupyter Notebook-based data analysis project focused on food delivery order data. The analysis includes data cleaning, feature extraction, revenue/cost breakdowns, profitability analysis, and visualizations for key business metrics.

---

## 📁 Repository Structure

- `food orders.ipynb` – Main Jupyter notebook with the full analysis pipeline.
- `requirements.txt` – Python dependencies required to run the notebook.
- `README.md` – This project overview and usage guide.

> ⚠️ Note: The notebook currently reads the dataset from an absolute path (`C:\Users\anshu\Downloads\food_orders_new_delhi (2).csv`). For portability, you should place the CSV in this repository (e.g., `data/food_orders.csv`) and update the path in the notebook accordingly.

---

## 🧰 Dependencies

Install dependencies into a virtual environment (recommended):

```bash
python -m venv .venv
# Windows
.venv\Scripts\activate
# macOS/Linux
source .venv/bin/activate

pip install -r requirements.txt
```

---

## ▶️ Running the Analysis

1. Ensure the dataset CSV is accessible locally (see the note above about the file path).
2. Start Jupyter:

```bash
jupyter notebook
```

3. Open `food orders.ipynb` and run the cells sequentially.

---

## 📌 What's Included in the Notebook

The notebook contains sections that cover:

- Loading and inspecting the dataset
- Parsing datetime columns
- Extracting discount types and values
- Calculating per-order profit, revenue, and cost metrics
- Visualizations and charts (histograms, pie charts, bar charts, KDE plots)
- Simulating alternative commission/discount strategies for profitability

---

## ✅ Tips for Extending the Analysis

- **Add new metrics:** e.g., order delivery time, average basket size, customer segmentation.
- **Improve data ingestion:** Add a small wrapper to locate the dataset in the repo (e.g., `data/food_orders.csv`) and fall back to a default path.
- **Add unit tests:** Use `pytest` to validate your discount extraction logic.

---

## 🧾 License

This project is for educational/data analysis purposes. Feel free to adapt the code and share improvements.
