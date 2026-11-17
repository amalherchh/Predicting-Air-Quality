# Air Quality Classification – KNN

## Objective
Build a supervised machine learning model to classify daily air quality as Good or Bad using environmental measurements.

## Dataset
- Source: [UCI Air Quality Dataset](https://archive.ics.uci.edu/dataset/360/air+quality)
- Original observations: 9,357 hourly records.
- Final dataset: 341 daily observations.
- Features: NOx and Relative Humidity (RH).
- Target: Air Quality (Good / Bad).

## Methodology
1. Data cleaning and missing-value removal.
2. Daily aggregation of hourly measurements.
3. Binary target construction using CO and NO2 reference thresholds (75th percentile).
4. Feature selection and standardization.
5. Train/test split (80/20).
6. KNN training and hyperparameter selection.

## Results
- Best K: 4
- Test accuracy: **84.06%**

## Conclusion
The KNN model achieved 84.06% test accuracy using NOx and relative humidity to classify daily air quality.

## Tools
Python, Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn.
