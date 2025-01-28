<img src="images/FinanceSQL/IDATitle.jpg?raw=true"/>

# UNVEILING ECONOMIC OBLIGATIONS LANDSCAPES: A COMPREHENSIVE ANALYSIS OF GLOBAL DEBT DYNAMICS 
---

## Why This Project?

Following the COVID-19 pandemic 😷, global upheavals such as wars 🪖 and natural disasters have transformed the world’s economic environment. These incidents affect lives globally 🌍, highlighting the importance of understanding the role of loans and finances in international development. Through data analysis 📈, we can identify trends, reveal funding inequalities, and equip decision-makers to develop economic growth and poverty alleviation strategies.<br>

## Why Should You Pay Attention:

Whether you’re planning for yourself, your family, or a nation, these insights into 1,379,049 loans with 30 attributes will inspire smarter decisions. Dive into this story of global lending 📊to discover:<br>
    -🗺️ Which regions borrow the most?
    -📉 How do interest rates vary globally?
    -📊 What’s the connection between repayment and service charges?<br><br>

# Key Findings at a Glance 🚀

  - **Top Borrowers by loan amount:**
    - **Organization**: The Ministry of Finance
    - **Region**: South Asia, Africa
    - **Country**: India, Bangladesh, Pakistan, Vietnam, Nigeria<br>
 
  - **Interest Rates:**
    - **St. Kitts and Nevis**: 📈 Highest interest rate at 3.68% (165 loans worth $32M disbursed, $40M repaid).
    - **Africa**🌍 Lowest average interest rate at 0.09% (2,891 loans).<br>
    
  - **Service Charge Rate Correlations:**
    - <mark>Higher repayments</mark> correlate with higher service charge rates.
    - <mark>Lower borrower obligations</mark> tend to have lower rates.<br>
    
  - **Project-Specific Insights:**
    - **St. Kitts and Nevis**: Only 1 project with a service charge rate >1.
    - **Macedonia**: 🚩 59% of projects have a 3.4% interest rate.
    - **Kenya**: Leads in guaranteed loans (1,248).
    - **Afghanistan**: Dominates in grants (12,302).
    - **India**: Tops in credits (69,805).<br>
    <br>
## The Data: [Link](https://financesone.worldbank.org/ida-statement-of-credits-grants-and-guarantees-historical-data/DS00976)

The International Development Association (IDA) is crucial in aiding the world’s poorest nations. The dataset analyzed comes from the World Bank’s IDA Statement of Credits, Grants, and Guarantees - Historical Data and offers detailed insights into global lending practices.<br><br>

## Tools & Techniques 🛠️:**
  -  <mark>SQL</mark>: Extracted and aggregated the dataset with precision.
  -  <mark>Tableau & Excel</mark>: Visualized trends to make findings accessible and actionable.<br>
  
Let's start uncovering the hidden stories behind global loans to understand how they shape economic growth and social development together! 🌐✨<br>

---
## The Analysis and Commentary:

### Over View of the data

1.    **Return all of the table**
<th><img src="images/FinanceSQL/1CODE_DataOverView.png?raw=true"/>
<th><img src="images/FinanceSQL/1DataOverView.png?raw=true"/><br><th>

2.  **Return the first 5 rows of the table, but only the borrower & due to IDA column**<br>
<th><img src="images/FinanceSQL/2CODE_OverView5Row.png?raw=true"/><br><th>
<th><img src="images/FinanceSQL/2OverView5Row.png?raw=true"/><br><th>

3.  **Total number of transactions**<br>
      - **Row:**  <img src="images/FinanceSQL/3CODETotalCount.png?raw=true"/> <br>
      - **Column:**    <img src="images/FinanceSQL/3CODETotalCountColumn.png?raw=true"/><br>

### DUE to IDA (US$) Attribute Analysis:
  **🏆 The Biggest Borrowers:** <br>
At the forefront, The Ministry of Finance leads with the highest total loan amount, steering resources to tackle financial and developmental challenges. Regionally, South Asia dominates, with Africa following closely, reflecting their significant development needs.

4.	**The top 15 highest organization borrowers**<br>
<th><img src="images/FinanceSQL/4CODE_15Highest Borrower.png?raw=true"/><br><th>
<th><img src="images/FinanceSQL/4Highest Borrower15.png?raw=true"/><br><th>
>🥇The Ministry of Finance has the highest total loan amount.<br>
>
  - 👉🏼 High School Graduation Performance?<br>
    <img src="images/HighSchool.jpg?raw=true"/>
    - Bottom 10 HS Grad %: **Springfield Public Day High School** leads the chart<br>
    - The highest % of the bottom 10 High School graduates is 19%. 
 <img src="images/Bottom 10 HS.png?raw=true"/><br>
 [Link to Interactive Graph](https://public.tableau.com/app/profile/quy.tran4833/viz/MassStatBottom10HSGrad/Bottom10HSGrad)<br><br>

  - 👉🏼 Are there meaningful regional differences within MA? <br>
   <img src="images/ILoveMath.jpg?raw=true"/>
      4th grade Math (14/53 or 26% district is under 50%)<br>
        <img src="images/4th Grade Math.png?raw=true"/><br><br>
 [Link to Interactive Graph](https://public.tableau.com/app/profile/quy.tran4833/viz/4thGradeMath_17375968453200/4thGradeMath)
    
  - 👉🏼 What contributes to differences in schools' outcomes?<br>
    <img src="images/Score.jpg?raw=true"/>
      Both are significant since the P value is close to 0. Number of Observations: 340<br>
      - **Class size**: 
         R2= 0.189728 -> explain almost 19%<br>
       <img src="images/College Attendance vs Class Size.png?raw=true"/><br>
 [Link to Interactive Graph](https://public.tableau.com/app/profile/quy.tran4833/viz/CollegeAttendancevsClassSize_17375967565970/CollegeAttendancevsClassSize)<br><br>
      - **Economic Disadvantage**:
        <img src="images/College Attendance vs Econ Disadvtg.png?raw=true"/><br>
 [Link to Interactive Graph](https://public.tableau.com/app/profile/quy.tran4833/viz/CollegeAttendancevsEconDisadvtg/CollegeAttendancevsEconDisadvtg)    
         R2= 0.379253 -> Explain nearly 37%<br>
       ==> Economic Disadvantage % has a higher (negative) impact on College Attendance than Class Size.<br>    
 
   - 🏆 Which schools do well despite limited resources?<br>
   <img src="images/College Graduation.JPG?raw=true"/><br>  
      - Measure by high % disadvantage and large classroom size with high College Attendance %:<br>
      - 🥇 Match Charter Public School<br>
      - 🥇 Quincy Upper School<br>
 
---
**Concise Summary:**
    Even with a $306 billion annual budget, the 1 million students in Massachusetts schools performances are:<br>
  - ✅ % of College Attendance had a more substantial negative impact by Economic Disadvantage % than Class Size<br>
         👏 Schools with high economic disadvantage and small classroom sizes show they put in the effort. Unfortunately, their efforts haven’t translated to a desirable college attendance percentage. It’s worth further investigating and assisting to address their struggle.<br>
  - ✅26% of schools fall under 50% of 4th Grade Math with P + A grade passing.<br>
  - ✅ Hall of Fame: Match Charter Public School, Quincy Upper School, Sherborn Elementary School<br>
  - ✅ Struggling Leader: Springfield Public Day High School, Tec Connections Academy Commonwealth Elementary School.<br>

**Call to Action:**
  - 🔜 Are you wondering how schools in your state perform? Contact me. ✍️ <br>
  - 🔜 If you are involved in a project that requires similar analysis.  Let's collaborate.<br>
  - 🔜 Drop your comments💬, thoughts💡, and questions⁉️ for interesting further analysis ideas<br>
  
<img src="images/FloralBorder.JPG?raw=true"/>
