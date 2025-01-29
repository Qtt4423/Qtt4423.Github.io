<img src="images/FinanceSQL/IDATitle.jpg?raw=true"/>

# UNVEILING ECONOMIC OBLIGATIONS LANDSCAPES: A COMPREHENSIVE ANALYSIS OF GLOBAL DEBT DYNAMICS 
---

## Why This Project?

Following the COVID-19 pandemic 😷, global upheavals such as wars 🪖 and natural disasters have transformed the world’s economic environment. These incidents affect lives globally 🌍, highlighting the importance of understanding the role of loans and finances in international development. Through data analysis 📈, we can identify trends, reveal funding inequalities, and equip decision-makers to develop economic growth and poverty alleviation strategies.<br>

## Why Should You Pay Attention:

Whether you’re planning for yourself, your family, or a nation, these insights into 1,379,049 loans with 30 attributes will inspire smarter decisions. Dive into this story of global lending 📊to discover:

<ul>
  <li>🗺️ Which regions borrow the most?</li>
  <li>📉 How do interest rates vary globally?</li>
  <li>📊 What’s the connection between repayment and service charges?</li>
  <li>Fourth item</li>
</ul>

## Key Findings at a Glance 🚀
<ul>
  <li><strong>Top Borrowers by loan amount:<strong/>
    <ul>
      <li>Organization: 
          The Ministry of Finance</li>
      <li>Region: 
          South Asia, Africa</li>
      <li>Country: 
          India, Bangladesh, Pakistan, Vietnam, Nigeria</li>
    </ul>
  </li>
  <li><strong>Interest Rates:<strong/>
    <ul>
      <li>St. Kitts and Nevis: 
          📈 Highest interest rate at 3.68% (165 loans worth $32M disbursed, $40M repaid).</li>
      <li>Africa:🌍 
          The lowest average interest rate is 0.09% (2,891 loans).</li>
    </ul>
  </li>
  <li><strong>Service Charge Rate Correlations:<strong/>
    <ul>
      <li>Higher repayments correlate with higher service charge rates.</li>
      <li>Lower borrower obligations tend to have lower rates.</li>
    </ul>
  </li>
  <li><strong>Project-Specific Insights:<strong/>
    <ul>
      <li>St. Kitts and Nevis: 
          Only 1 project with a service charge rate >1.</li>
      <li>Macedonia: 
          🚩59% of projects have a 3.4% interest rate.</li>
      <li>Kenya: 
          Leads in guaranteed loans (1,248).</li>
      <li>Afghanistan: 
          Dominates in grants (12,302).</li>
      <li>India: 
          Tops in credits (69,805).</li>
    </ul>
  </li>
</ul>



## The Data: [Link](https://financesone.worldbank.org/ida-statement-of-credits-grants-and-guarantees-historical-data/DS00976)

The International Development Association (IDA) is crucial in aiding the world’s poorest nations. The dataset analyzed comes from the World Bank’s IDA Statement of Credits, Grants, and Guarantees - Historical Data and offers detailed insights into global lending practices.<br><br>

## Tools & Techniques 🛠️:**
<ul>
  <li>SQL: 
      Extracted and aggregated the dataset with precision.</li>
  <li>Tableau & Excel: 
      Visualized trends to make findings accessible and actionable.</li>
</ul>

Let's start uncovering the hidden stories behind global loans to understand how they shape economic growth and social development together! 🌐✨<br>

---
## The Analysis and Commentary:

### Over View of the data

1.    **Return all of the table**<br>
<img src="images/FinanceSQL/1CODE_DataOverView.png?raw=true"/>
<img src="images/FinanceSQL/1DataOverView.png?raw=true"/><br>

2.  **Return the first 5 rows of the table, but only the borrower & due to IDA column**<br>
<img src="images/FinanceSQL/2CODE_OverView5Row.png?raw=true"/><br>
<img src="images/FinanceSQL/2OverView5Row.png?raw=true"/><br>

3.  **Total number of transactions**<br>

<ul>
  <li><strong>Row:<strong/><br> <img src="images/FinanceSQL/3CODETotalCount.png?raw=true"/></li>
  <li><strong>Column:<strong/><br> <img src="images/FinanceSQL/3CODETotalCountColumn.png?raw=true"/></li>
</ul>
    
###  Payment Timeframe Analysis
Which was the most recent to pay?<br>
  <img src="images/FinanceSQL/23CountryLoanTypeLoanCount.png?raw=true"/><br>
  <img src="images/FinanceSQL/Tanzania.jpg?raw=true"/><br><br>

### DUE to IDA (US$) Attribute Analysis:
  **🏆 The Biggest Borrowers:** <br>

At the forefront, The Ministry of Finance leads with the highest total loan amount, steering resources to tackle financial and developmental challenges. Regionally, South Asia dominates, with Africa following closely, reflecting their significant development needs.

1.	**The top 15 highest organization borrowers**<br>
<img src="images/FinanceSQL/4CODE_15Highest Borrower.png?raw=true"/><br>
<img src="images/FinanceSQL/4Highest Borrower15.png?raw=true"/><br>

>  🥇The Ministry of Finance has the highest total loan amount.

2.	**Abbreviate one of the column names so it's easier to write**<br>
<img src="images/FinanceSQL/5AbbreviateColumn.png?raw=true"/><br><br>

3.	**List the top 15 highest Region borrowers:**<br>
<img src="images/FinanceSQL/6CODE15highestRegionborrower.png?raw=true"/><br>
<img src="images/FinanceSQL/6Result15highestRegionborrower.png?raw=true"/><br>
<img src="images/FinanceSQL/6Graph15highestRegionborrower.png?raw=true"/><br><br>
>  🥇South Asia has the highest total loan amount, followed by Africa.

4.	**What is the maximum, minimum, and average amount owed to the IDA?**<br>
<img src="images/FinanceSQL/7CODEOwedAvg_Max_Min.png?raw=true"/><br><br>

5.	**📊 Overall Impact of Loans:**<br>
<ul>
  <li>Cumulative Loan Amount: Over $25 trillion, reflecting decades of developmental investments.</li>
  <li>Snapshot Loan Total: Nearly $210 billion in the most recent data—a significant portion of global financial aid.</li>
</ul>
  <img src="images/FinanceSQL/8TotalLoan.png?raw=true"/><br><br>
  
6.	**Loan amount to the IDA by Country**:<br>
  <img src="images/FinanceSQL/9SumLoanAmount_CountryMap.png?raw=true"/><br>
  <img src="images/FinanceSQL/9CODESumLoanAmount_CountryDESC.png?raw=true"/><br><br>
>🌟 Top Loan Recipients:<br>
><ul>
>  <li>🇮🇳 India</li>
>  <li>🇧🇩 Bangladesh</li>
>  <li>🇵🇰 Pakistan</li>
>  <li>🇻🇳 Vietnam</li>
>  <li>🇳🇬 Nigeria</li>
></ul>
<img src="images/FinanceSQL/9CODESumLoanAmount_CountryASC.png?raw=true"/><br><br>

><ul>
>  <li>Haiti has almost a $0 loan amount.</li>
>  <li>Costa Rica has had a big jump of $82,407 in loan amounts.</li>
></ul>

7.	**Who has the most loans?**  Total Transactions by Country<br>
  <img src="images/FinanceSQL/10CODEHighestNoLoan.png?raw=true"/><br>
  <img src="images/FinanceSQL/10MapHighestNoLoan.png?raw=true"/><br><br>
India has the highest number of loans, while World and International Finance Corporation has the lowest amount.<br><br>
  <img src="images/FinanceSQL/10ResultHighestNoLoan.png?raw=true"/><br><br>

###  The Interest Rate Puzzle 💡:<br>
One country stands out for its steep rates:<br>
<ul>
  <li>St. Kitts and Nevis:
    <ul>
      <li>📈 Interest rate: 3.68% (highest globally).</li>
      <li>🏦 Loans: 165, with $32M disbursed and $40M repaid.</li>
      <li>💡 Insight: Despite the high rate, repayment amounts exceed disbursed funds—a testament to strategic financial management.</li>
    </ul>
  </li>
  <li>	Africa:
    <ul>
      <li>🌍 Lowest average interest rate: 0.09% across 2,891 loans.</li>
      <li>🤔 Observation: Low rates help balance the repayment burden for developing nations.</li>
    </ul>
  </li>
</ul><br>

8.	**Service Charge**<br>
  <img src="images/FinanceSQL/11ServiceCharge_Country.png?raw=true"/><br>
  <img src="images/FinanceSQL/11ServiceCharge_CountryResult.png?raw=true"/><br>
<ul>
  <li>St. Kitts and Nevis has the highest Interest rate of 3.68.</li>
  <li>Africa has the lower Interest rate of 0.09.</li>
</ul><br>

9.  Service Charge Rate by Country
     **What are the countries with 0 interest rate:**<br>
  <img src="images/FinanceSQL/12Countries0IntRate.png?raw=true"/><br><br>
    **Top 10 countries with the lowest interest rate:**<br>
  <img src="images/FinanceSQL/13Countries_IntRateASC.png?raw=true"/><br><br>
    **Top 10 countries with the highest interest rate:**<br>
  <img src="images/FinanceSQL/14CountriesIntRateDESC.png?raw=true"/><br><br>
Knowing that most countries have an average interest rate under 2.0, I filter the graph to show better variation.<br>
  <img src="images/FinanceSQL/14ServiceCharge_Country_Und2Map.png?raw=true"/><br><br>


###  CRITICAL INFLUENCER ASSESSMENT Analysis:<br>

**Geospatial Data Analysis**🎯 Project Insights That Matter:<br>
<ul>
  <li>St. Kitts and Nevis:<br>
  The AG Dev Support Project is the sole project with a service charge rate >1, spotlighting a unique financial model.</li>
  <li>•	Macedonia: 🚩 <br>
  59% of projects have an interest rate of 3.4%, making it a region of high financial strain.</li>
  <li>•	Bangladesh:<br>
  The Padma Bridge Project emerges as a powerhouse, with the highest active Original Principal loan amount in the region.</li>
</ul>

1.	**How many loans do St. Kitts and Nevis have?**
  <img src="images/FinanceSQL/15StKittsNoLoan.png?raw=true"/><br><br>
  
2.	**How many loans does Africa have?**
  <img src="images/FinanceSQL/16AfricaNoLoan.png?raw=true"/><br><br>
  
3.	**Return all column groups by country with a Service Charge Rate greater than 1 for St. Kitts and Nevis**
  <img src="images/FinanceSQL/17StKittsServChrgGreater1.png?raw=true"/><br>

  <img src="images/FinanceSQL/18StKittsProjectCreditStatusTable.png?raw=true"/><br>
  <img src="images/FinanceSQL/17StKittsServChrgGreater1CreditStatusPie.png?raw=true"/><br>

>St. Kitts and Nevis‘s disbursed loan amount is almost $32 million, and $40 million is repaying the loan amount.
  
  <img src="images/FinanceSQL/17StKittsServChrgGreater1.png?raw=true"/><br>

>🔄 Correlations That Speak Volumes:
>
><ul>
>  <li>Repayment Amount ↔️ Service Charge Rate:
>    <ul>
>      <li>A positive correlation suggests that higher repayments often incur higher service charge rates.</li>
>      <li>This highlights the importance of negotiating better repayment terms to manage financial burdens.</li>
>    </ul>
>  </li>
>  <li>Borrower Obligation ↔️ Service Charge Rate:
>    <ul>
>      <li>A negative correlation reveals that larger borrower obligations tend to result in lower service charge rates.</li>
>      <li>Could this be a hidden incentive for bigger development projects?</li>
>    </ul>
>  </li>
></ul>
>

  <img src="images/FinanceSQL/17StKittsServChrgGreater1_RepaidIDABar.png?raw=true"/><br>
  <img src="images/FinanceSQL/17StKittsServChrgGreater1_BorrowerObligationBar.png?raw=true"/><br>

4.	**Return selected columns group by Project Name and Credit Status for St. Kitts and Nevis with Service Charge Rate greater than 1**
  <img src="images/FinanceSQL/18StKittsProjectCreditStatusTable.png?raw=true"/><br>
  Only the AG Dev Support Project has a service charge rate greater than 1 in St. Kitts and Nevis.<br>

><ul>
>  <li>59% of Projects in Macedonia have a high interest rate of 3.4.</li>
>  <li>70% of Projects in North Macedonia have a high interest rate of 3.39</li>
></ul>

Macedonia, the former Yugoslav Republic of:<br>
  <img src="images/FinanceSQL/18MacedoniaProjectCreditStatusTable.png?raw=true"/><br>
  <img src="images/FinanceSQL/18MacedoniaProjectCreditStatusGRAPH.png?raw=true"/><br>

North Macedonia, the former Yugoslav Republic of:<br>
  <img src="images/FinanceSQL/18NorthMacedoniaProjectCreditStatusTABLE.png?raw=true"/><br>
  <img src="images/FinanceSQL/18NorthMacedoniaProjectCreditStatusGRAPH.png.png?raw=true"/><br><br>

###Project Attribute Analysis
1.	**Top 20 Highest Original Principal Amount (US$) Project:**<br>












<br><br><br>
  
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
