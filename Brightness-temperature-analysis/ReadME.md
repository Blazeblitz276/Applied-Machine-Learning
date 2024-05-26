
# Brightness Temperature Analysis

This section involves visualizing the distribution of brightness temperature I-4 and analyzing its impact on fire detection.

#### Directory Structure
```
Brightness-Temperature-Analysis/ 
(data already present in the repository in Applied-Machine-Learning\Fire-Data-Visualization\data\fire_nrt_V1_96617.csv)
├── Brightness_Temperature_Analysis.ipynb
├── README.md
```
## Dataset

The dataset used is `fire_nrt_V1_96617.csv` which can be obtained from [NASA's VIIRS I-Band 375 m Active Fire Data](https://www.earthdata.nasa.gov/learn/find-data/near-real-time/firms/viirs-i-band-375-m-active-fire-data).

## Tasks

1. **Histogram:** Visualize the distribution of brightness temperature I-4.
2. **Class Distribution Plot:** Plot latitude vs. longitude for points with saturated and non-saturated brightness separately.
3. **Combined Plot with Legends:** Plot both groups in the same axes with different colors and a legend.

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
jupyter notebook Brightness_temperature_analysis.ipynb
```
