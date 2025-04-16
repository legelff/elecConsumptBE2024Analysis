# Electricity Consumption Analysis for Belgium (2024)

This project analyzes electricity consumption data for Belgium in 2024, focusing on key metrics such as carbon intensity, carbon-free energy percentage, and renewable energy percentage. The analysis evaluates Belgium's performance against EU-wide targets for 2030.

## Data Sources

The data used in this analysis is sourced from [Electricity Maps](https://www.electricitymaps.com/). The dataset includes daily metrics for Belgium in 2024.

## Key Metrics and Results

### 1. Carbon Intensity (gCO₂eq/kWh - Direct)
- **Threshold**: Below 100 gCO₂eq/kWh (direct) to meet EU-wide targets. (rough estimate)
- **Results**:
  - Days above threshold: 155
  - Days below threshold: 211
- **Conclusion**: Good performance, as most days are below the threshold.

### 2. Carbon Intensity (gCO₂eq/kWh - Life Cycle)
- **Threshold**: Below 100 gCO₂eq/kWh (life cycle) to meet EU-wide targets. (rough estimate)
- **Results**:
  - Days above threshold: 323
  - Days below threshold: 43
- **Conclusion**: Poor performance, as most days exceed the threshold.

### 3. Carbon-Free Energy Percentage (CFE%)
- **Threshold**: Above 70% to meet EU-wide targets. (rough estimate)
- **Results**:
  - Days above threshold: 303
  - Days below threshold: 63
- **Conclusion**: Good performance, as most days exceed the threshold.

### 4. Renewable Energy Percentage (RE%)
- **Threshold**: Above 60% to meet EU-wide targets. (rough estimate)
- **Results**:
  - Days above threshold: 0
  - Days below threshold: 366
- **Conclusion**: Poor performance, as no days exceed the threshold.

## Visualizations

The analysis includes the following visualizations:
1. **Carbon Intensity (Direct)**: Daily trends with a threshold line at 100 gCO₂eq/kWh.
2. **Carbon Intensity (Life Cycle)**: Daily trends with a threshold line at 100 gCO₂eq/kWh.
3. **Carbon-Free Energy Percentage (CFE%)**: Daily trends with a threshold line at 70%.
4. **Renewable Energy Percentage (RE%)**: Daily trends with a threshold line at 60%.

## Summary

| Metric                              | Performance |
|-------------------------------------|-------------|
| Carbon Intensity (Direct)           | Good        |
| Carbon Intensity (Life Cycle)       | Bad         |
| Carbon-Free Energy Percentage (CFE%)| Good        |
| Renewable Energy Percentage (RE%)   | Bad         |

## How to Run the Analysis

1. Install the required Python libraries:
   ```bash
   pip install polars matplotlib numpy
2. Clone the repository:
    ```bash
    git clone https://github.com/legelff/elecConsumptBE2024Analysis.git
    cd elecConsumptBE2024Analysis
    ```
3. Run the analysis script in any code editor with jupyter notebook (run all):

## Contact

If you have any questions, suggestions, or just want to have a chat, feel free to reach out:

- Email: business@l145.be
- LinkedIn: [Aryan Shah](https://www.linkedin.com/in/aryan-shah-l145)
- GitHub: [legelff](https://github.com/legelff)