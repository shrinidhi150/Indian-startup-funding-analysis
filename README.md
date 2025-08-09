# Indian-startup-funding-analysis
# Startup Funding Data Loader

This project is a simple Python script to load and preview a startup funding dataset using **Pandas**.

## 📂 Project Structure

```
.
├── main.py               # Main script to load and display data
├── startup_funding.csv   # Dataset containing startup funding details
```

## 📋 Requirements

* Python 3.7+
* Pandas library

You can install the dependencies with:

```bash
pip install pandas
```

## 🚀 Usage

1. Place the dataset file (`startup_funding.csv`) in the appropriate path.
   In this script, it is expected at:

   ```
   /content/startup_funding.csv
   ```

   If your file is elsewhere, update the path in `main.py`.

2. Run the script:

   ```bash
   python main.py
   ```

3. The script will:

   * Load the dataset with Pandas.
   * Display the first five rows for inspection.

## 📄 Example Output

```
   Company Name  City Location  Investors Name  Investment Amount
0   XYZ Tech     Bangalore     ABC Ventures    5,000,000
1   Alpha Inc.   Delhi         XYZ Capital     2,000,000
...
```

