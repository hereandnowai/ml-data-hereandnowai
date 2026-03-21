<p align="center">
  <img src="https://raw.githubusercontent.com/hereandnowai/images/refs/heads/main/logos/logo-of-here-and-now-ai.png" alt="HERE AND NOW AI Logo" width="250">
</p>

# California Housing Prediction Dataset

### *AI is Good*

This dataset provides detailed information for predicting housing prices in California. It is based on the 1990 California census and is a classic dataset for regression tasks in machine learning.

## 📊 Dataset Overview

- **Source**: Modified from [Luís Torgo's page](http://www.dcc.fc.up.pt/~ltorgo/Regression/cal_housing.html) (University of Porto).
- **Core Reference**: Pace, R. Kelley and Ronald Barry, "Sparse Spatial Autoregressions," *Statistics and Probability Letters*, 1997.
- **Unit**: Census Block Groups (approx. 600–3,000 residents).

## 🛠 Features & Tweaks

- **Target Column**: `median_house_value`.
- **Key Modification**: 207 `total_bedrooms` values were removed to simulate missing data handling.
- **Added Feature**: `ocean_proximity` (categorical) for grouping by geographical proximity to water.

## 📈 Data Quick Look

```python
# housing.info() output
<class 'pandas.core.frame.DataFrame'>
RangeIndex: 20640 entries, 0 to 20639
Data columns (total 10 columns):
longitude             20640 non-null float64
latitude              20640 non-null float64
housing_median_age    20640 non-null float64
total_rooms           20640 non-null float64
total_bedrooms        20433 non-null float64
population            20640 non-null float64
households            20640 non-null float64
median_income         20640 non-null float64
median_house_value    20640 non-null float64
ocean_proximity       20640 non-null object
```

---

## 🤝 Connect with Us

- **Website**: [hereandnowai.com](https://hereandnowai.com)
- **LinkedIn**: [HERE AND NOW AI](https://www.linkedin.com/company/hereandnowai/)
- **X (Twitter)**: [@hereandnow_ai](https://x.com/hereandnow_ai)
- **Instagram**: [@hereandnow_ai](https://instagram.com/hereandnow_ai)
- **YouTube**: [HERE AND NOW AI](https://youtube.com/@hereandnow_ai)
- **GitHub**: [hereandnowai](https://github.com/hereandnowai)

📧 **Email**: [info@hereandnowai.com](mailto:info@hereandnowai.com)
📞 **Phone**: +91 996 296 1000
   
    75%     -118.010000     37.720000           37.000000   3141.000000   
    max     -114.310000     41.950000           52.000000  39320.000000   

           total_bedrooms    population    households  median_income  
    count    16355.000000  16513.000000  16513.000000   16513.000000  
    mean       534.885112   1419.525465    496.975050       3.875651  
    std        412.716467   1115.715084    375.737945       1.905088  
    min          2.000000      3.000000      2.000000       0.499900  
    25%        295.000000    784.000000    278.000000       2.566800  
    50%        433.000000   1164.000000    408.000000       3.541400  
    75%        644.000000   1718.000000    602.000000       4.745000  
    max       6210.000000  35682.000000   5358.000000      15.000100
 
