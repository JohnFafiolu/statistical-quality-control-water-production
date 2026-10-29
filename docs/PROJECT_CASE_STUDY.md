# Statistical Quality Control in Table-Water Production

## 1. Project Overview

This project demonstrates how statistical quality control techniques
can be applied to simulated table-water production data to examine
product defects, water-quality measurements, machine downtime,
and production-related sales patterns.

The analysis uses Python to explore the data, identify patterns,
and demonstrate how statistical methods can support operational
monitoring and decision-making.

**Important:** The dataset is simulated and does not represent
verified operational records from the university's water factory.

## 2. Business Problem

A production manager needs a structured way to monitor product
defects, assess process measurements, understand machine downtime,
and examine the relationship between production and sales.

This case study demonstrates how statistical analysis can help
organize these questions and identify areas for further investigation.

## 3. Analytical Questions

- What proportion of simulated production units are defective?
- Which defect categories account for the largest number of defects?
- How do simulated turbidity measurements vary over time?
- What patterns appear in machine downtime?
- What relationship exists between production and calculated revenue?
- How consistent are the simulated questionnaire responses?

## 4. Tools and Methods

- **Python:** Data analysis and visualization.
- **Pandas and NumPy:** Data manipulation and calculations.
- **Matplotlib and Seaborn:** Charts and visual exploration.
- **SciPy and Statsmodels:** Statistical analysis and regression.

Methods included descriptive statistics, a Pareto chart, a
proportion control chart, an Individuals control chart, a
7-day moving average, linear regression, and Cronbach's alpha.

## 5. Key Findings

- **Total simulated production:** 35,821 units.
- **Recorded simulated defects:** 1,994 units.
- **Overall defective proportion:** 5.57%.
- **Most frequent defect category:** Poor sealing, with 1,130 recorded defects.
- **Production and revenue correlation:** Approximately 0.636.
- **Regression R-squared:** Approximately 0.405.
- **Questionnaire Cronbach's alpha:** -0.565, indicating poor
  internal consistency among the questionnaire items.

Revenue was calculated using an assumed fixed price of ₦150
per unit sold. It should not be interpreted as actual factory revenue.

## 6. Business Interpretation

The simulated data illustrates how defect counts and proportions
can be used to prioritize quality-control investigations.

Poor sealing accounts for a substantial share of recorded defects,
making it a useful starting point for a hypothetical investigation
into sealing equipment, operating procedures, and quality checks.

The regression identifies an association between production and
calculated revenue. It does not establish causation, and the
relationship should be interpreted in light of the way revenue
was calculated.

The negative Cronbach's alpha suggests that the questionnaire
items should be reviewed before the scale is used to draw
reliable conclusions.

## 7. Recommendations

Based on the analytical approach demonstrated in this case study:

1. Investigate the causes of sealing-related defects.
2. Monitor defect proportions over time using suitable control charts.
3. Review unusual turbidity measurements against relevant quality
   specifications.
4. Track machine downtime and investigate recurring interruptions.
5. Review questionnaire design and item consistency before
   interpreting survey results.

These are proposed actions for a real production setting, not
evidence that these problems occurred at the actual factory.

## 8. Limitations

- All datasets used in this analysis are simulated.
- The findings cannot establish actual factory performance.
- No verified operational quality thresholds were supplied.
- Revenue uses an assumed fixed selling price.
- The questionnaire contains only 15 simulated responses.
- Statistical associations do not establish causal relationships.

## 9. Conclusion

This project demonstrates the application of statistical quality
control, exploratory data analysis, and regression techniques
to a simulated production scenario.

It highlights how statistical thinking can help identify patterns,
prioritize investigations, and communicate evidence while
recognizing data limitations.

## 10. Project Resources

- [GitHub Repository](https://github.com/JohnFafiolu/statistical-quality-control-water-production)
- [Data Dictionary](DATA_DICTIONARY.md)

## Author

**John Fafiolu**  
Statistics Graduate | Data Analytics | Statistical Analysis
