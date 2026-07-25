Thank you for listening the presentation link below:
https://drive.google.com/file/d/1GkQ0T-c6xkII4SuJGYYAvf8ZZe5xyY-d/view?usp=sharing 

Supply Cost Recovery Analytics 

A data analytics application built with Python and Excel to the simulated an SAP ERP environment. This project evaluates procurement data, calculates the purchase price variance (PPV), identifies cost discrepancies, and automates supplier cost recovery claims.

Objective:
The primary objective of this project is to mimic procurement and finance workflows within a simulated SAP ERP system:
Audit Price Variances: Calculate differences between standard material costs and actual invoiced costs.
Cost Recovery Claims: Automatically identify unfavorable balances ($Actual > Standard$) to initiate supplier overcharge claims.
Cross-Functional Collaboration: Collabration for procurement and finance management functions through clear data reporting.

Key Features:
PPV   Analysis: Automatically computes variance amounts as Favorable or Unfavorable.
System Investigation: Generates expense type of transactions posted the correct amount for G/L account balance and cost center audits upon detecting overcharges.
Duplicate Detection: Ensure the invoice records for matching amounts on AP account.
Interactive UI: Built using Gradio** for visual analysis and file loading.

Project Structure

├── dataset
│   └── procurement_data.csv       # Simulated procurement & invoice dataset
├── app.py                         # Main Python script (PPV calculations & Gradio UI
├── requirements.txt               # Required Python pandas
 
Thank  you for your questions and feedback.
