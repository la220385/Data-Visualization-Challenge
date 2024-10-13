# Pymaceuticals Inc: Capomulin Drug Regimen Analysis

## Project Overview
This project is part of an analysis on the effectiveness of various drug regimens, particularly **Capomulin**, in reducing tumor volume in mice. The data contains information on **tumor volume**, **mouse weight**, and **treatment regimens**. Key goals include determining the relationship between mouse weight and tumor volume, calculating the **correlation coefficient**, and performing a **linear regression analysis** to visualize the relationship. 

### Analysis
- This analysis done by me on behalf of Pymaceuticals Inc. of the Capomulin regimen focused on examining the relationship between mouse weight and average tumor volume. A correlation coefficient of approximately 0.84 was found, indicating a moderately strong positive correlation between the two variables. This suggests that as mouse weight increases, the tumor volume also tends to increase. Further, a linear regression analysis was performed, yielding a slope of 0.95, meaning that for every 1-gram increase in mouse weight, the average tumor volume increases by 0.95 cubic millimeters. The R-squared value of 0.71 indicates that 71% of the variability in tumor volume can be explained by mouse weight, reinforcing the predictive power of weight in determining tumor volume. The scatter plot, with the regression line, visually confirms this positive linear trend. Overall, the findings suggest a strong positive correlation between mouse weight and tumor volume, providing useful insights into how body mass may be linked to tumor growth in mice treated with Capomulin.

## Key Steps
**Filtering the Data**
- Focused on the Capomulin treatment group by filtering the data.
Grouped by Mouse ID to calculate the average tumor volume and weight for each mouse.

**Correlation Coefficient**
- Computed to determine the strength of the relationship between mouse weight and tumor volume.
Correlation coefficient indicated a strong positive relationship.

**Linear Regression**
- Performed a regression analysis to fit a line through the data points and computed key metrics such as slope, intercept, and R-squared value.
Visualized the regression line alongside the scatter plot of the data.

## Resources Used
This section lists the resources used in the development of this project, including libraries, documentation, and tutorials that guided the code implementation and analysis.

1. **Pandas Documentation**
   - **Purpose**: Used for data manipulation, cleaning, filtering, and calculating statistics like the correlation coefficient.
   - **Link**: [Pandas Documentation](https://pandas.pydata.org/docs/)

2. **Matplotlib Documentation**
   - **Purpose**: creating the scatter plots, customizing visualizations, and adding regression lines to plots.
   - **Link**: [Matplotlib Documentation](https://matplotlib.org/stable/contents.html)

3. **SciPy Documentation**
   - **Purpose**: performing linear regression and calculating statistical properties such as slope, intercept, and R-squared value.
   - **Link**: [SciPy Documentation](https://docs.scipy.org/doc/scipy/)

5. **Python Official Documentation**
   - **Purpose**: General Python syntax reference and understanding basic programming logic.
   - **Link**: [Python Documentation](https://docs.python.org/3/)

6. **Stack Overflow**
   - **Resource**: Stack Overflow Community
   - **Purpose**: Helpful for troubleshooting code errors, optimizing solutions, and understanding best practices in Python programming.
   - **Link**: [Stack Overflow](https://stackoverflow.com/)

7. **Bootcamp Spot**
   -**Xpert Learning Assistant**: Used for any extra assistance needed 

## Conclusion
The analysis showed a **strong positive correlation** between mouse weight and tumor volume for mice treated with Capomulin, with an **R-squared value** of **0.71**, indicating that approximately **71% of the variability in tumor volume** can be explained by mouse weight.
