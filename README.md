[README_COMPLETE_GUIDE.txt](https://github.com/user-attachments/files/32806194/README_COMPLETE_GUIDE.txt)
WEEK 5 TASK 05 — COMPLETE BUILD GUIDE

1. Dataset
Use Microsoft's official Power BI Financial Sample. Microsoft provides this sample as an Excel workbook and also allows it to be loaded directly from Power BI Desktop's sample-data option.

Official source:
https://learn.microsoft.com/en-us/power-bi/create-reports/sample-financial-download

2. Power BI import
Home → Get Data → Excel → select Financial Sample.xlsx → select Financials → Load.

Alternative:
Home → Learn with sample data → Load sample data → Financials.

3. Power Query
Home → Transform data.
- Check column names.
- Check data types.
- Remove blank rows.
- Check duplicate rows.
- Check nulls.
- Confirm Date is Date.
- Confirm numeric columns are numeric.
- Close & Apply.

4. DAX
Create the measures in Documentation/DAX_Measures.txt.

5. Theme
View → Themes → Browse for themes → Design/PowerBI_Theme.json.

6. Dashboard
Use the layout in Design/Dashboard_Layout.txt and the PNG mockup as the visual reference.

Top:
Title + date slicer

KPI row:
Total Sales | Total Profit | Profit Margin | Units Sold | Sales YoY %

Middle:
Sales & Profit Trend | Sales by Segment

Lower:
Sales by Country | Top Products

Bottom:
Performance Matrix

Slicers:
Date | Country | Segment | Product

7. Interactivity
Select a country and confirm all relevant charts update.
Select a segment and confirm the trend and product charts update.
Use Ctrl-click when selecting multiple items where appropriate.

8. Formatting
- Use the supplied dark blue theme.
- Use consistent fonts.
- Use K/M/B number formatting where suitable.
- Use percentage formatting for margins and growth.
- Avoid unnecessary borders.
- Keep titles aligned.
- Do not overcrowd the canvas.

9. Deliverables
According to the Week 5 assignment:
- .pbix file
- PDF/image export of final dashboard
- 0.5–1 page write-up with dataset, KPIs and 2–3 insights.

10. Suggested file name
RollNumber_Name_Week5_Task5_PowerBI.pbix
