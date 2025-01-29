<img src="images/FinanceSQL/IDATitle.jpg?raw=true"/>

# UNVEILING ECONOMIC OBLIGATIONS LANDSCAPES:<br><br>  A COMPREHENSIVE ANALYSIS OF GLOBAL DEBT DYNAMICS 
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
  <li><strong>Interest Rates:<strong/>
    <ul>
      <li>St. Kitts and Nevis: 
          📈 Highest interest rate at 3.68% (165 loans worth $32M disbursed, $40M repaid).</li>
      <li>Africa:🌍 
          The lowest average interest rate is 0.09% (2,891 loans).</li>
    </ul>
  <li><strong>Service Charge Rate Correlations:<strong/>
    <ul>
      <li>Higher repayments correlate with higher service charge rates.</li>
      <li>Lower borrower obligations tend to have lower rates.</li>
    </ul>
  <li><strong>Project-Specific Insights:<strong/>
    <ul>
      <li>St. Kitts and Nevis: 
          Only 1 project (AG DEV Support) with a service charge rate >1.</li>
      <li>Macedonia: 
          🚩59% of projects have a 3.4% interest rate.</li>
      <li>Kenya: 
          Leads in guaranteed loans (1,248).</li>
      <li>Afghanistan: 
          Dominates in grants (12,302).</li>
      <li>India: 
          Tops in credits (69,805).</li>
    </ul>

## The Data
[Link to Data Set](https://financesone.worldbank.org/ida-statement-of-credits-grants-and-guarantees-historical-data/DS00976)<br>

The International Development Association (IDA) is crucial in aiding the world’s poorest nations. The dataset analyzed comes from the World Bank’s IDA Statement of Credits, Grants, and Guarantees - Historical Data and offers detailed insights into global lending practices.

## Tools & Techniques 🛠️:
<ul>
  <li>SQL: 
      Extracted and aggregated the dataset with precision.</li>
  <li>Tableau & Excel: 
      Visualized trends to make findings accessible and actionable.</li>
</ul>

Let's start uncovering the hidden stories behind global loans to understand how they shape economic growth and social development together! 🌐✨<br>

---

## The Analysis and Commentary:<br>

### Over View of the data<br>

1.  Return all of the table<br>
<img src="images/FinanceSQL/1CODE_DataOverView.png?raw=true"/>
<img src="images/FinanceSQL/1DataOverView.png?raw=true"/><br>

2.  Return the first 5 rows of the table, but only the borrower & due to IDA column<br>
<img src="images/FinanceSQL/2CODE_OverView5Row.png?raw=true"/><br>
<img src="images/FinanceSQL/2OverView5Row.png?raw=true"/><br>

3.  Total number of transactions<br>

<ul>
  <li><strong>Row:<strong/><br> <img src="images/FinanceSQL/3CODETotalCount.png?raw=true"/></li>
  <li><strong>Column:<strong/><br> <img src="images/FinanceSQL/3CODETotalCountColumn.png?raw=true"/></li>
</ul>
    <br>
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

1.	**Service Charge**<br>
  <img src="images/FinanceSQL/11ServiceCharge_Country.png?raw=true"/><br>
  <img src="images/FinanceSQL/11ServiceCharge_CountryResult.png?raw=true"/><br>
<ul>
  <li>St. Kitts and Nevis has the highest Interest rate of 3.68.</li>
  <li>Africa has the lower Interest rate of 0.09.</li>
</ul><br>

2.  Service Charge Rate by Country  
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
**St. Kitts and Nevis**
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

**Return selected columns groups by project name with a Service Charge Rate greater than 1 for St. Kitts and Nevis**
  <img src="images/FinanceSQL/18StKittsProjectCreditStatusTable.png?raw=true"/><br>
  
  <img src="images/FinanceSQL/17StKittsServChrgGreater1CreditStatusPie.png?raw=true"/><br>

>St. Kitts and Nevis‘s disbursed loan amount is almost $32 million, and $40 million is repaying the loan amount.
>AG DEV Support is the only project under this category.
  <br><br>

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

**Macedonia and North Macedonia**
><ul>
>  <li>59% of Projects in Macedonia have a high interest rate of 3.4.</li>
>  <li>70% of Projects in North Macedonia have a high interest rate of 3.39</li>
></ul>

Macedonia, the former Yugoslav Republic of:<br>
  <img src="images/FinanceSQL/18MacedoniaProjectCreditStatusTable.png?raw=true"/><br>
  <img src="images/FinanceSQL/18MacedoniaProjectCreditStatusGRAPH.png?raw=true"/><br>

North Macedonia, the former Yugoslav Republic of:<br>
  <img src="images/FinanceSQL/18NorthMacedoniaProjectCreditStatusTABLE.png?raw=true"/><br>
  <img src="images/FinanceSQL/18NorthMacedoniaProjectCreditStatusGRAPH.png?raw=true"/><br><br>

###  Project Attribute Analysis
1.	**Top 20 Highest Original Principal Amount (US$) Project:**<br>
  <img src="images/FinanceSQL/19CODEHighestPrincipalProject.png?raw=true"/><br>
  <img src="images/FinanceSQL/19HighestPrincipalProjectMAP.png?raw=true"/><br><br>
  
SAC II, followed by IN: Elementary Education (SAC II) Project, ranked the highest in the original principal amount.<br><br>

2.	**Return all columns for SAC II and Elementary Education (SSA II) project**<br>
<ul>
  <li>South Asia has a higher SAC II loan amount than Africa. </li>
  <li>•	Meanwhile, Africa has a higher original principal amount than the loan amount. </li>
</ul>
  <img src="images/FinanceSQL/20SACII_ElementaryEdSSAIIProjectRESULT.png?raw=true"/><br>
  <img src="images/FinanceSQL/20SGRAPHPrincipleProjectCOUNTRY.png?raw=true"/><br>
  <img src="images/FinanceSQL/20SGRAPHPrincipleProjectREGION.png?raw=true"/><br><br>
  
###  Credit Status Analysis
1.	**Top 15 projects** for countries with the highest loan amount to the IDA with active credit status in India, Bangladesh, Pakistan, and Vietnam<br>
  <img src="images/FinanceSQL/21CODEActiveCreditLoan.png?raw=true"/><br>
  <img src="images/FinanceSQL/21PIEChartActiveCreditLoan.png?raw=true"/><br><br>
Bangladesh has the highest total active Original Principal, while India has the highest total active loan amount due. BD: The Padma Bridge project has a significantly higher total active Original Principal loan amount than other projects.<br>
  <img src="images/FinanceSQL/21BarChartActiveCreditLoan.png?raw=true"/><br><br>

###  🏗️ Types of Loans Across the Globe:
<ul>
  <li>Guarantees: 🇰🇪 Kenya leads with 1,248 loans.</li>
  <li>Grants: 🇦🇫 Afghanistan dominates with 12,302 loans.</li>
  <li>Credits: 🇮🇳 India takes the crown with 69,805 loans.</li>
</ul>

2.	**List the countries with the highest count of loans for each of the following "Guarantees," "Grants," or "Credits"
Credit Number IDs starting with
<ul>
  <li>Guarantees: IDAB and IDAG </li>
  <li>Grants: IDAD, IDAH and IDAE </li>
  <li>Credits: the rest </li>
</ul>
  <img src="images/FinanceSQL/23CountryLoanTypeLoanCount.png?raw=true"/><br><br>

 
---
##  The Bigger Picture:<br>
This analysis is more than just numbers—it's a window into how nations grow, rebuild, and thrive. Behind every loan lies a story of ambition, resilience, and innovation.<br><br>

##  Re-emphasizing Key Takeaways 🌟📊:<br>
<ol>
  <li>Top Borrowers & Regions:
    <ul>
      <li>The Ministry of Finance holds the highest total loan amount.</li>
      <li>South Asia leads regional allocations, followed by Africa.</li>
      <li>🇮🇳 India, 🇧🇩 Bangladesh, and 🇵🇰 Pakistan top the list of loan recipients.</li>
    </ul>
  </li>
  <li>High-Interest Outlier:
    <ul>
      <li>St. Kitts and Nevis faces the highest interest rate of 3.68%, with 165 loans totaling $32M disbursed and $40M repaid.</li>
    </ul>
  </li>
  <li>Correlations in Repayment & Rates:
    <ul>
      <li>Positive correlation: Higher repayments are linked to higher service charge rates.</li>
      <li>Negative correlation: Larger borrower obligations correspond to lower service charge rates.</li>
    </ul>
  </li>
</ol>
These findings 💡highlight the significance of strategic financial planning to manage repayment burdens and secure favorable loan terms👏, offering valuable insights for 🌍 policymakers and decision-makers✅. <br><br>

##  Where Do We Go From Here 🚀✨:
  - 🔜 👌Use these insights to inform financial and policy decisions, negotiate smarter loan terms, and promote sustainable global🌍 growth.<br>
  - 🔜 ✍️ Dive deeper into how financing drives projects that change lives.<br>
  - 🔜 🗨️ Engage & Share your takeaways, 💡ideas for further analysis.<br>
  - 🔜 Collaborate with Me: Reach out for collaboration or work opportunities—I’m ready to dive into data with you! 🌟<br>
  
<img src="images/FloralBorder.JPG?raw=true"/>
