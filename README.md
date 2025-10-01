Customer Segmentation Using RFM Analysis

Project Overview
This project was completed as part of my **Data Science Internship at Elevvo**.  
It applies **RFM (Recency, Frequency, Monetary) analysis** to the UCI Online Retail dataset to segment customers and design actionable marketing strategies.

Tools & Libraries
- Python (Google Colab)  
- Pandas, NumPy  
- Matplotlib, Seaborn  

Steps Performed
1. **Data Cleaning**: Removed null values, returns/cancellations, and negative sales.  
2. **Feature Engineering**: Created RFM metrics:  
   - Recency (days since last purchase)  
   - Frequency (number of purchases)  
   - Monetary (total money spent)  
3. **Scoring**: Assigned quartile-based RFM scores.  
4. **Segmentation**: Grouped customers into:  
   - Champions  
   - Loyal Customers  
   - Potential High Value  
   - Recent Customers  
   - At Risk  
   - Lost  
   - Others  
5. **Marketing Strategies**: Suggested targeted strategies for each segment (e.g., loyalty rewards, win-back campaigns).  
6. **Visualization**: Plotted bar charts and heatmaps to understand customer distribution.

Results
- Segmented customers into multiple actionable groups  
- Designed simple and effective marketing strategies  
- Exported results to `rfm_results.csv` for further use  

## Key Takeaway
RFM analysis is a simple yet powerful way to turn raw sales data into **actionable customer insights**, helping businesses move beyond one-size-fits-all marketing.  
