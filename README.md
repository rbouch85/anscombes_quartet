# anscombes_quartet
Creating visuals for Anscombe's Quartet

## Overview
This project creates four charts of Anscombe's Quartet using Python in a Jupyter notebook. The data points are sourced from [Wikipedia](https://en.wikipedia.org/wiki/Anscombe%27s_quartet).

## Features
- Four datasets (I, II, III, IV), each in its own pandas DataFrame
- Horizontal layout optimized for 8.5x11 paper (landscape orientation)
- Minimalist design with no axis labels
- Light grey linear regression lines
- Blue data points
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

3. The notebook will generate `anscombes_quartet.png` in the current directory.

## Requirements
- Python 3.x
- pandas
- matplotlib
- scipy
- jupyter
