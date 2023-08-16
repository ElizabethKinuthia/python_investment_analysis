# 📊 Investment Analysis Project

This repository presents the details of an investment analysis project that I conducted using Python. The analysis focuses on evaluating the potential investment in solar batteries for Naomi, a client seeking to optimize her electricity costs and usage efficiency.

## 📝 Introduction

The analysis is centered around Naomi's solar electricity generation and electricity usage data for the year 2020, recorded in hourly increments. The objective is to determine whether investing in solar batteries would be financially viable for Naomi. The entire analysis was performed using Python in a Jupyter Notebook. You can view the detailed Jupyter Notebook via the following link: [Investment Analysis Jupyter Notebook](https://github.com/ElizabethKinuthia/python_investment_analysis/blob/437079d1713d74ade6576b4203b5428ab9e58290/Elizabeth%20Nduta%20Kinuthia%20-%20Investment%20Analysis%20using%20Python.ipynb)

## 📊 Background

Naomi's current energy consumption involves a combination of solar power and purchased electricity. The excess solar energy generated but not utilized does not provide her any benefit due to the lack of storage. Considering investing in a solar battery, priced at $7000, Naomi aims to evaluate its cost-effectiveness over the projected lifespan of 20 years. Key considerations include the battery's capacity of 12.5 kWh and a threshold of 0 kWh.

## 💡 Purpose

The primary goals of the analysis are as follows:

1. **Calculate Extra kWh from Solar Battery**: Determine the additional kWh Naomi could harness with the solar battery.

2. **Analyze Potential Electricity Cost Savings**: Analyze the potential reduction in electricity costs by adopting the battery.

3. **Calculate NPV and IRR**: Compute the Net Present Value (NPV) and Internal Rate of Return (IRR) to gauge the investment's financial viability.

## 📊 Data Analysis Process

The analysis process encompassed several stages:

### Data Checks

Initial exploratory data analysis revealed no null values or duplicates. However, a sharp spike in electricity use during noon hours required investigation. An extreme outlier was detected and replaced with the median to ensure accurate analysis.

### Modeling Battery Charge Level

A model was developed to simulate the cumulative battery charge level based on electricity generation, usage, and purchase. This model factored in constraints like the battery's maximum capacity of 12.5 kWh. Visualizations were employed to understand and aggregate the modeled data.

### Visualizing Monthly Data

Monthly visualizations were created to analyze solar generation compared to electricity usage. The contrast highlighted months where surplus solar energy could not be stored and potential electricity cost savings.

### Calculating NPV and IRR

NPV and IRR calculations were performed for two scenarios of electricity price increases: 4% per year and 4% with an additional 0.25% increment per year. The results were used to determine the investment's profitability.

## 📂 Files

The primary file associated with this project is the detailed Jupyter Notebook available here: [Investment Analysis Jupyter Notebook](https://github.com/ElizabethKinuthia/python_investment_analysis/blob/437079d1713d74ade6576b4203b5428ab9e58290/Elizabeth%20Nduta%20Kinuthia%20-%20Investment%20Analysis%20using%20Python.ipynb)

## 📝 Conclusion

Based on the comprehensive analysis conducted, it is not recommended for Naomi to invest in solar batteries solely from a financial perspective. While the battery offers increased energy storage capacity, the projected cost savings do not justify the investment's expense. The analysis provides valuable insights for Naomi's decision-making process regarding solar battery adoption.

Thank you for your time and consideration. I look forward to discussing this project further.

Feel free to explore the Jupyter Notebook for a deeper understanding of the analysis process and results.
