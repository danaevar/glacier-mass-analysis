# Global Glacier Mass Loss Analysis (2000–2023)

This project analyzes global glacier mass change using the WGMS GlaMBIE dataset (calendar year aggregate).

## Dataset
World Glacier Monitoring Service (WGMS)  
GlaMBIE Global Glacier Mass Balance Dataset (Version 2024-07)  
DOI: 10.5904/wgms-glambie-2024-07  

## Methods
- Data loading and preprocessing using pandas
- Linear regression to estimate long-term trend
- Cumulative mass loss calculation
- Conversion to equivalent global mean sea level rise (360 Gt ≈ 1 mm)
- 5-year rolling mean smoothing
- Residual analysis to separate trend from variability

## Key Results
- Mean annual glacier mass loss ≈ **-273 Gt per year**
- Acceleration ≈ **-10 Gt per year²**
- Total cumulative mass loss since 2000 ≈ **-6500 Gt**
- Estimated sea level rise contribution ≈ **18 mm**
- Persistent downward trend with clear long-term signal

## Tools Used
- Python
- pandas
- numpy
- matplotlib
- Jupyter Notebook
