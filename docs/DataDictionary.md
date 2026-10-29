# Data Dictionary

## Overview

This document describes the datasets used in the Statistical Quality Control in Table-Water Production project.

**Data notice:** The datasets are simulated and do not represent verified operational records or actual staff responses.

## 1. Production Dataset

**File:** `data/master_factory_data.csv`

Contains 90 simulated daily observations used to analyze production quality, defects, turbidity, machine downtime, and sales-related variables.

| Variable | Description | Unit / Format |
|---|---|---|
| Date | Date associated with the production observation | Date |
| Qty_Produced | Quantity produced during the observation | Units |
| Qty_Sold | Quantity sold during the observation | Units |
| Qty_Defective | Number of units recorded as defective | Units |
| Poor_Sealing | Defects attributed to poor sealing | Defects |
| Wrong_Labeling | Defects attributed to incorrect labeling | Defects |
| Underfilled | Defects attributed to underfilling | Defects |
| Leakages | Defects attributed to leakage | Defects |
| Overfilled | Defects attributed to overfilling | Defects |
| Turbidity | Simulated turbidity measurement | NTU, if confirmed by the dataset |
| Downtime_Hours | Recorded simulated machine downtime | Hours |
| Revenue_NGN | Simulated revenue calculated from units sold | Nigerian naira (NGN) |

**Note:** Confirm the exact column names and units against the CSV before finalizing this table. Add the remaining variables if the dataset contains additional columns.

## 2. Questionnaire Dataset

**File:** `data/staff_questionnaire_data.csv`

Contains 15 simulated questionnaire responses across five items. It is used to demonstrate questionnaire reliability analysis.

| Variable | Description |
|---|---|
| Item_1 | Response to questionnaire item 1 |
| Item_2 | Response to questionnaire item 2 |
| Item_3 | Response to questionnaire item 3 |
| Item_4 | Response to questionnaire item 4 |
| Item_5 | Response to questionnaire item 5 |
| Total_Score | Combined score across questionnaire items, if included in the CSV |

## 3. Derived Analysis Variables

The notebook also creates variables during analysis, including:

- `Moving_Range`: Absolute difference between consecutive turbidity measurements.
- `Prop_Defective`: Daily defective proportion.
- `UCL_p`: Upper control limit for the p-chart.
- `LCL_p`: Lower control limit for the p-chart.
- `Downtime_7Day_MA`: Seven-day moving average of downtime.

These are derived variables created during analysis and may not exist in the original CSV files.

## 4. Interpretation Notes

- All source datasets are simulated.
- Revenue is calculated using a fixed selling price of ₦150 per unit sold.
- Statistical findings describe the simulated data and should not be generalized to actual factory operations.
