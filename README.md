# NovaRetail-Plus-Analysis
Statistical analysis of customer behavior and revenue drivers for NovaRetail+ using Python, Seaborn, and SciPy.
Customer Value & Correlation Analysis: The NovaRetail+ Case Study 🛒📊

This repository contains a comprehensive exploratory and statistical analysis of factors associated with Annual Revenue for NovaRetail+, an e-commerce platform. The project focuses on identifying key value drivers through rigorous correlation methodologies.

🎯 **Project Objectives**
- Identify variables with the strongest association with annual revenue.
- Visually validate relationships using Heatmaps and Scatterplots.
- Apply robust statistical coefficients: **Pearson, Spearman, Point-Biserial, and Cramér's V.**
- Provide data-driven business recommendations while strictly adhering to the "Correlation ≠ Causality" principle.

🛠️ **Tech Stack**
- Language: Python 3.x
- Libraries: * Pandas & NumPy (Data Wrangling)
  - Matplotlib & Seaborn (Data Visualization)
  - SciPy (Advanced Statistical Computing)
- Environment: Jupyter Notebook

📈 **Key Insights**
- Transaction Frequency: The most critical driver, showing a 0.967 correlation, indicating a near-perfect synchrony with annual revenue.
- Targeted Advertising: Displayed a weak association (0.1975), suggesting an opportunity to optimize ad spend and targeting strategies.
- Geographic Independence: Cramér's V (0.0000) confirmed that device preference and user location are entirely independent variables.
- Premium Status: Membership status showed a low correlation (0.0931), indicating that customer value in 2024 was not strictly tied to subscription tiers.

📂 **Repository Structure**
- `novaretail_analysis.ipynb`: Main notebook containing code, visualizations, and diagnostic commentary.
- `data/`: Folder containing the raw/processed dataset.
