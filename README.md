# Location Entropy Analysis

Calculates location entropy per taxi driver from the EPFL Cabspotting GPS dataset to analyze mobility patterns.

## Dataset

- **Source**: [EPFL Cabspotting](https://ieee-dataport.org/open-access/crawdad-epflmobility) - San Francisco Taxi GPS Traces
- **Size**: 536 taxi drivers, ~11M GPS records

## Setup

1. **Create a virtual environment**
   ```bash
   cd main
   python -m venv venv
   ```

2. **Activate the environment**
   - Windows:
     ```bash
     venv\Scripts\activate
     ```
   - macOS/Linux:
     ```bash
     source venv/bin/activate
     ```

3. **Install dependencies**
   ```bash
   pip install -r requirements.txt
   ```

## Running the Notebook

1. Start Jupyter:
   ```bash
   jupyter notebook
   ```

2. Open `location_entropy_cabspotting.ipynb` 

3. Run all cells (`Cell` → `Run All` or `Shift+Enter` per cell)

## Output

- `entropy_results.csv` - Entropy values per driver
- `entropy_analysis.png` - Visualization of entropy distribution

