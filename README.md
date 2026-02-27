# IDX Prolonged Suspension Dataset

## Overview
This repository provides the dataset for: **Early-Warning Classification of Prolonged Stock Suspension in Indonesia**.  
It contains labeled observations of Indonesia Stock Exchange (IDX) listed companies to support research on identifying stocks at risk of **prolonged suspension (e.g., ≥ 6 months)**. Each record includes financial features and a binary target label distinguishing **alive** vs **suspended** stocks for model training and evaluation.

## Columnn
- `company` : Company name.
- `year` : Observation year (reporting year).
- `status` : Target class (`alive` or `suspended`).
- `X1`  : Current Ratio  
- `X2`  : Quick Ratio  
- `X3`  : Debt-to-Equity Ratio  
- `X4`  : Asset–Liability Ratio  
- `X5`  : Equity Multiplier  
- `X6`  : Return on Assets (ROA)  
- `X7`  : Return on Equity (ROE)  
- `X8`  : Gross Profit Margin  
- `X9`  : Operating Profit Margin  
- `X10` : Net Profit Margin  
- `X11` : Growth Rate of EPS  
- `X12` : Growth Rate of Revenue  
- `X13` : Growth Rate of Net Income  
- `X14` : Asset Turnover Ratio  
- `X15` : Inventory Turnover Ratio  
- `X16` : Working Capital Turnover Ratio  
- `X17` : Earnings per Share (EPS)  
- `X18` : Revenue per Share  
- `X19` : Book Value per Share (BVPS)  
- `X20` : Price-to-Earnings (P/E)  
- `X21` : Price-to-Sales (P/S)  
- `X22` : Price-to-Book Value (P/B)  
- `X23` : Sector (company sector classification)

## License
This dataset is released under **CC BY 4.0**.

## Citation
If you use this dataset, please cite:
