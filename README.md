# InvestAnalysis_Excel

## Overview
This project analyzes investment durations and expectations using Microsoft Excel. It involves summarizing data using Pivot Tables, visualizing distributions with histograms, and comparing expectations with a Radar Chart.

## Steps to Perform the Analysis

### 1. Summarize Investment Durations (Using Pivot Table)
1. Open the dataset in Excel.
2. Click on any cell in the **"Duration"** column.
3. Go to **Insert** → **PivotTable** → Select **New Worksheet** → Click **OK**.
4. In the PivotTable Fields pane:
   - Drag **Duration** to the **Rows** section.
   - Drag **Duration** again to the **Values** section (to get "Count of Duration").
5. The Pivot Table will now show the count of each investment duration.

### 2. Create a Histogram for Investment Durations
1. Select the data from the Pivot Table (Investment Duration & Count).
2. Go to **Insert** → **Column Chart** → **Clustered Column Chart**.
3. Click on the chart → Enable **Axis Titles** and **Data Labels**.
4. Rename the X-axis as **Investment Duration** and the Y-axis as **Number of Participants**.
5. Customize colors and fonts for better readability.

### 3. Summarize Investment Expectations (Using Pivot Table)
1. Click on any cell in the **"Expect"** column.
2. Go to **Insert** → **PivotTable** → Select **New Worksheet** → Click **OK**.
3. In the PivotTable Fields pane:
   - Drag **Expect** to the **Rows** section.
   - Drag **Expect** again to the **Values** section (to get "Count of Expect").
4. The Pivot Table will now show the count of each expected return range.

### 4. Create a Radar Chart for Investment Expectations
1. Select the summarized data (Expected Returns & Count from Pivot Table).
2. Go to **Insert** → **Radar Chart** → Choose **Filled Radar Chart**.
3. Click on the chart → Enable **Data Labels** and **Axis Titles**.
4. Rename the chart title to **"Investment Expectations"**.
5. Customize the color scheme and axis scale for clarity.

### 5. Final Touches & Presentation
- Rename worksheet tabs for better organization (e.g., "Duration Summary", "Expectations Chart").
- Adjust column widths and chart sizes for clarity.
- Save the Excel file for presentation or reporting.

## Conclusion
This analysis provides a clear insight into investment duration preferences and return expectations among participants. The visualizations make it easier to interpret and present the findings effectively.

## Author
Created by Ashish

---
Feel free to modify and enhance the README as per your project requirements!

