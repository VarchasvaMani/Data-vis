# 📊 Data Analyst Candidate Selection Tool

An interactive Jupyter Notebook for filtering, analysing, and visualising top Data Analyst candidates from an Excel dataset — no coding required.

---

## 🖼️ Overview

This tool helps you:
- Upload any candidate Excel file directly in the notebook
- Filter candidates by skill keyword (e.g. "Data Analysis")
- Pick how many top candidates to display
- Choose which columns to include
- Save filtered results to a new Excel file
- Visualise data with Bar and/or Pie charts
- View quick summary statistics

---

## 📁 Project Structure

```
data-vis/
├── Data_Analyst_Interactive.ipynb   # Main interactive notebook
├── Unstructured.xlsx                # Sample input data (raw candidates)
├── requirements.txt                 # Python dependencies
└── README.md                        # Project documentation
```

---

## ⚙️ Requirements

- Python 3.8+
- Jupyter Notebook or JupyterLab

Install dependencies:

```bash
pip install -r requirements.txt
```

Or install manually:

```bash
pip install pandas matplotlib ipywidgets openpyxl xlrd
```

> **Note:** `ipywidgets` requires widget extensions to be enabled. In JupyterLab, run:
> ```bash
> jupyter labextension install @jupyter-widgets/jupyterlab-manager
> ```

---

## 🚀 Getting Started

1. **Clone the repository**
   ```bash
   git clone https://github.com/YOUR_USERNAME/data-vis.git
   cd data-vis
   ```

2. **Install dependencies**
   ```bash
   pip install -r requirements.txt
   ```

3. **Launch Jupyter**
   ```bash
   jupyter notebook
   # or
   jupyter lab
   ```

4. **Open** `Data_Analyst_Interactive.ipynb`

5. **Run all cells** top to bottom with `Shift + Enter`

---

## 🧭 How to Use the Notebook

| Step | What to do |
|------|-----------|
| **Step 1** | Setup — installs packages and imports libraries |
| **Step 2** | Upload your Excel file using the file upload button |
| **Step 3** | Preview raw data with an adjustable row slider |
| **Step 4** | Filter by skill keyword, top N count, and columns |
| **Step 5** | Save filtered results to a timestamped Excel file |
| **Step 6** | Generate Bar chart, Pie chart, or both |
| **Step 7** | View summary statistics (age, skill breakdown, names) |

---

## 📊 Input File Format

Your Excel file should contain columns similar to:

| Name | Mobile Number | Skill | Age |
|------|--------------|-------|-----|
| John Doe | 9876543210 | Data Analysis - Advanced | 28 |
| Jane Smith | 9123456789 | Data Analysis - Intermediate | 32 |

The notebook auto-detects columns containing **"Skill"**, **"Name"**, and **"Age"** — exact column names are flexible.

---

## 📤 Output

Filtered results are saved as:
```
filtered_candidates_YYYYMMDD_HHMMSS.xlsx
```
in the same directory as the notebook.

---

## 🛠️ Built With

- [pandas](https://pandas.pydata.org/) — data manipulation
- [matplotlib](https://matplotlib.org/) — charts and visualisation
- [ipywidgets](https://ipywidgets.readthedocs.io/) — interactive UI widgets
- [openpyxl](https://openpyxl.readthedocs.io/) — Excel file handling

---

## 👤 Author

**Varchasva Mani**
