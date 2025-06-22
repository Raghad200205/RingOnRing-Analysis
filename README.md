# Ring-On-Ring Test Analysis

This script (`ring_on_ring_analysis.py`) analyzes Excel files from ring-on-ring strength tests. It calculates:

- Maximum load
- Failure time (extrapolated from deflection)
- Failure rate
- Temperature and humidity (if available)

📁 **Instructions**:
- Place your `.xlsx` test files in the specified folder path.
- Adjust `folder_path` in the script accordingly.

📄 **Output**:
- A `.xlsx` summary with results
- PDF reports of deflection and load plots

📦 Python dependencies:
```bash
pandas
matplotlib
scikit-learn
openpyxl
numpy
