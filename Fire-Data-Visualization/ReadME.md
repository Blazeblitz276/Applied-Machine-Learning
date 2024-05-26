
# Fire Data Visualization

This section focuses on visualizing fire data from Australia and New Zealand using various plotting techniques.


### Directory Structure
```
Fire-Data-Visualization/
├── data
│ ├── fire_nrt_V1_96617.csv
├── Fire_Data_Visualization.ipynb
└──  README.md
```


## Dataset

The dataset used is `fire_nrt_V1_96617.csv` which can be obtained from [NASA's VIIRS I-Band 375 m Active Fire Data](https://www.earthdata.nasa.gov/learn/find-data/near-real-time/firms/viirs-i-band-375-m-active-fire-data).

## Tasks

1. **Basic Scatter Plot:** Visualize longitude vs. latitude using matplotlib defaults.
2. **Scatter Plot with Adjustments:** Adjust alpha and marker size for better visualization.
3. **Hexbin Plot:** Use hexbin plot to visualize the density of fire occurrences.
4. **Subsampling Plot:** Subsample the dataset to handle overplotting.

## Requirements

- matplotlib
- pandas
- numpy

## How to Run

1. Install the required packages:
```bash
pip install -r requirements.txt
```
Run the Jupyter Notebook:
```bash
jupyter notebook Fire_Data_Visualization.ipynb
```
