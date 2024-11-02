# Exploaratory_Analysis-of-50_startups-dataset

##### Overview
  The objective of this exploratory analysis is to understand the range, central tendencies and spread of each numerical feature. I used "data.describe()" method that provides the metrics for mean, standard deviation, minimum and maximum quartiles for each numeric column present. From the method I found out that **R&D Spend, Administration, and Marketing Spend** displays wide range of values which suggests an significant difference in how each startup has allocated its funds. The target variable shows a large range having mean of **112,012** which means that the high changes in profit indicates that some companies are achieving higher profits than the rest which might be tied down to their investing/spending state.

##### Histograms and Box Plots
![image](https://github.com/user-attachments/assets/bfba7abc-06d9-4f33-ab2f-f6c2718185b9)
![image](https://github.com/user-attachments/assets/f2693be4-a732-48dc-8cae-a0aaa3bd1db5)
![image](https://github.com/user-attachments/assets/3362512f-de88-4fce-9b3f-2f93d567366b)
![image](https://github.com/user-attachments/assets/1375d968-a8b1-42f1-8498-3a8f7e81b32e)
  For each numeric feature I have created an Histogram to visualize the frequency distribution and detect skewness and Box plot is created to display the spread of the data nad pinpoint any outliers present.
  ###### R&D Spend:
          * The Histogram shows a right-skewed distribution which indicates that most of the companies spend less on R&D whereas a small percentage of companies invest more.
          * The box plot further proves the point by highlighting the companies having high R&D investments as its outliers.
  
  ###### Administration:
          * The Histogram of Administration is symmetrically distributed in comparision to other features which displays the consistent approach to administrative costs by all companies.
          * The box plot shows few outliers which is less extreme than the other columns implying some comapnies prioritize administrative spending.

  ###### Marketing Spend:
          * The Histogram of marketing spend shows an significant right skewness which indicates that  many companies are investing heavily in marketing whereas the majority of the companies have moderate spending.
          * The box plot shows alot of outliers reinforcing the point that marketing strategies are different for all companies.

  ###### Profit:
          * The Histogram shows an right skewness which indicates most of the companies are generating moderate profit whereas few achieve high profits.
          * The outliers shown by the box plot could indicate highly successful companies or the companies having great spending strategy.

##### Correlation Matrix:
![image](https://github.com/user-attachments/assets/1dcacf8f-f001-456e-a192-294a939d43c5)
**R&D Spend vs Profit**
  From the correlation matrix we found out that **R&D Spend** vs **Profit** has positive correlation which suggests that the companies having higher R&D investments has higher profits. From this we can derive that research and development is a critical driver of profitability for startup.

**Marketing Spend vs Profit**
  From the correlation matrix we determine that **Marketing Spend** vs **Profit** has average correlationg which suggests that marketing does contribute to profit but it is not as significant as R&D.

**Administration vs Profit**
  From the correlation matrix we can determine that **Administration** vs **Profit** has low correlation which suggests that administration does not directly influence profit.

##### Profit by State (Categorical Analysis)
![image](https://github.com/user-attachments/assets/8a6a21a3-e824-47f2-a496-f9d3adb250c9)
  **New York**: New York has the highest median profit which indicates a favorable envrionment for statups in this state.
  **California and Florida**: Both California and Florida has lower median profits although each state shows a wide spread of profit where some companies have achieved high profitability.

##### Conclusion
  The EDA provides different insights into the 50-startups dataset where:
  1. R&D Spend is the main contributor to gain higher profit suggesting startups could benefit from prioritizing R&D investments.
  2. Marketing Spend also shows positive relatoin to profit but it is not as significant as R&D Spend suggesting the investments needs to be carefully balanced alongside R&D.
  3. Profit by state shows the difference in profit accross state but other factors likely play a role in a startup's success.

Overall, the EDA provides a solid understanding for further strategic decision making which helps startups understand where resources should be allocated to maximize profits.
