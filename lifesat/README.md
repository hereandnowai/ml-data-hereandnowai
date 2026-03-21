<p align="center">
  <img src="https://raw.githubusercontent.com/hereandnowai/images/refs/heads/main/logos/logo-of-here-and-now-ai.png" alt="HERE AND NOW AI Logo" width="250">
</p>

# Life Satisfaction & GDP Analysis Dataset

### *AI is Good*

This dataset explores the relationship between economic output (GDP per capita) and subjective well-being (Life Satisfaction) across multiple countries. It combines data from the OECD and IMF to provide a comprehensive view of global living standards.

## 📊 Dataset Components

### 1. Life Satisfaction
- **Source**: [OECD Better Life Index](http://stats.oecd.org/index.aspx?DataSetCode=BLI)
- **Indicators**: Covers 24 dimensions of well-being, including air quality, job security, and educational attainment.

### 2. GDP per Capita
- **Source**: [International Monetary Fund (IMF)](http://goo.gl/j1MSKe)
- **Metric**: Measured in USD for the year 2015.

## 📁 Included Files
- `oecd_bli.csv`: Raw well-being metrics.
- `gdp_per_capita.csv`: Raw economic data.
- `lifesat.csv`: A cleaned and merged subset for easy analysis.

## 💻 Sample Usage (Python/Pandas)

```python
import pandas as pd
life_sat = pd.read_csv("lifesat.csv")
# Analyze relationship between GDP and well-being
correlation = life_sat["GDP per capita"].corr(life_sat["Life satisfaction"])
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
