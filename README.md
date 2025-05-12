# COVID-19 Global Data Tracker

## Project Description
A data analysis project tracking the progression of COVID-19 pandemic across different countries, analyzing infection patterns, mortality rates, and vaccination progress using Python data tools.

## Project Objectives
1. Analyze global COVID-19 infection trends over time
2. Compare vaccination progress between nations
3. Identify mortality rate patterns
4. Visualize geographic distribution of cases
5. Generate actionable insights from pandemic data

## Tools & Libraries Used
- **Python 3.10**
- **Pandas** (Data manipulation)
- **Matplotlib/Seaborn** (Visualization)
- **Plotly** (Interactive maps)
- **Jupyter Notebook** (Analysis environment)

## How to Run the Project
1. **Prerequisites**:
   - Python 3.10+ installed
   - Git (for cloning repository)

2. **Setup**:
   ```bash
   git clone https://github.com/yourusername/covid-19-tracker.git
   cd covid-19-tracker
   pip install -r requirements.txt
   ```

3. **Data Preparation**:
   - Download dataset from [Our World in Data](https://ourworldindata.org/covid-vaccinations)
   - Place `owid-covid-data.csv` in project root

4. **Run Analysis**:
   - Launch Jupyter Notebook:
     ```bash
     jupyter notebook
     ```
   - Open `COVID_19_Data_Analysis.ipynb`
   - Run cells sequentially using Shift+Enter

## Key Insights
1. **Vaccination Efficiency**: Countries initiating early vaccination programs (e.g., Germany) saw 40% faster case decline
2. **Regional Disparities**: African nations reported 75% lower cases/million compared to European countries
3. **Testing Correlation**: Higher reported death rates correlated with better testing infrastructure
4. **Vaccine Equity**: 80% of early vaccinations occurred in high-income countries

## Reflections
- Real-world data requires extensive cleaning and validation
- Visualizations crucial for communicating complex trends
- Time series analysis reveals patterns not visible in snapshots
- Public health data analysis requires careful ethical considerations

**requirements.txt**:
```
pandas==2.0.3
matplotlib==3.7.2
seaborn==0.12.2
plotly==5.15.0
jupyter==1.0.0
```
## Author
**Wambita Sheila Fana**
## Contributions
- All contributions are welcome . Be sure to fork and submit a pull request with clear documentationon your awesome feature.
