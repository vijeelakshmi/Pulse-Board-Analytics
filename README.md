# Pulse Board Analytics

Pulse Board Analytics is a Tableau dashboard project for exploring retail sales performance across time, regions, product categories, and customer segments.

## Project contents

```text
Dataset/
  PulseBoard_Analytics.csv       Source transaction data
Tableau/
  Pulse Board Analytics.twbx     Packaged Tableau workbook
```

## Dashboard

Open `Tableau/Pulse Board Analytics.twbx` in Tableau Desktop or Tableau Reader. The workbook includes an overview with:

- Total revenue, total orders, total customers, and average order value
- Revenue trends and monthly growth
- Revenue by product category
- Actual revenue compared with target
- Regional performance
- A filters view for exploring the data

The packaged workbook includes a Tableau data extract. The source CSV is also included in `Dataset/` for inspection or reconnecting the workbook's data source if Tableau requests it.

## Dataset

The CSV contains 3,000 transaction records from January 1 through June 30, 2025. Each row includes:

| Column | Description |
| --- | --- |
| `Transaction_ID` | Unique transaction identifier |
| `Date` | Transaction date |
| `Region` | Sales region |
| `Category` | Product category |
| `Product` | Product name |
| `Customer_ID` | Customer identifier |
| `Customer_Name` | Customer name |
| `Customer_Segment` | Customer segment |
| `Quantity` | Quantity purchased |
| `Revenue` | Revenue recorded for the transaction |
| `Orders` | Order count represented by the record |
| `Target` | Target value associated with the record |
| `Payment_Method` | Payment method |
| `Status` | Transaction status |
| `Average_Order_Value` | Average order value recorded for the transaction |

Source file: [`Dataset/PulseBoard_Analytics.csv`](Dataset/PulseBoard_Analytics.csv)
