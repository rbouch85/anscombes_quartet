# anscombes_quartet
Creating visuals for Anscombe's Quartet

## Overview
This project creates four separate charts of Anscombe's Quartet using Python in a Jupyter notebook. The data points are sourced from [Wikipedia](https://en.wikipedia.org/wiki/Anscombe%27s_quartet).

## Features
- Four datasets (I, II, III, IV), each in its own pandas DataFrame
- Each dataset saved as a separate PNG file (10x8 inches)
- Minimalist design with tick marks but no axis labels
- Light grey linear regression lines
- Blue data points (enhanced visibility)
- High-resolution PNG output (300 DPI)

## Usage
1. Install dependencies:
   ```bash
   pip install pandas matplotlib scipy jupyter
   ```

2. Open and run the notebook:
   ```bash
   jupyter notebook anscombes_quartet.ipynb
   ```

3. The notebook will generate four PNG files in the current directory:
   - `anscombes_quartet_I.png`
   - `anscombes_quartet_II.png`
   - `anscombes_quartet_III.png`
   - `anscombes_quartet_IV.png`

## Requirements
- Python 3.x
- pandas
- matplotlib
- scipy
- jupyter
