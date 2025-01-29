# UNVEILING ECONOMIC OBLIGATIONS LANDSCAPES:<br>	
###	A COMPREHENSIVE ANALYSIS OF GLOBAL DEBT DYNAMICS 

<img src="images/FinanceSQL/IDATitle.jpg?raw=true"/>

---

## **Why This Project?**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Following the COVID-19 pandemic 😷, global upheavals such as wars 🪖 and natural disasters have transformed the world’s economic environment. These incidents affect lives globally 🌍, highlighting the importance of understanding the role of loans and finances in international development. Through data analysis 📈, we can identify trends, reveal funding inequalities, and equip decision-makers to develop economic growth and poverty alleviation strategies.

## **Why Should You Pay Attention:**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Whether you’re planning for yourself, your family, or a nation, these insights into 1,379,049 loans with 30 attributes will inspire smarter decisions. Dive into this story of global lending 📊to discover:  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;🗺️ Which regions borrow the most?  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;📉 How do interest rates vary globally?  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;📊 What’s the connection between repayment and service charges?  



## **Key Findings at a Glance** 🚀

#####	**Top Borrowers by loan amount:**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Organization:   
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;The Ministry of Finance   
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Region:   
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;South Asia, Africa   
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Country:   
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;India, Bangladesh, Pakistan, Vietnam, Nigeria<br>
    
#####	**Interest Rates:**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;St. Kitts and Nevis:    
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;📈 Highest interest rate at 3.68%   
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;(165 loans worth $32M disbursed, $40M repaid).   
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Africa:🌍   
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;The lowest average interest rate is 0.09% (2,891 loans).   

#####	**Service Charge Rate Correlations:**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Higher repayments correlate with higher service charge rates.   
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Lower borrower obligations tend to have lower rates.   

#####	**Project-Specific Insights:**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;St. Kitts and Nevis:   
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Only 1 project (AG DEV Support) with a service charge rate >1.   
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Macedonia:  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;🚩59% of projects have a 3.4% interest rate.   
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Kenya:  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Leads in guaranteed loans (1,248).   
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Afghanistan:     
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Dominates in grants (12,302).   
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;India:  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Tops in credits (69,805).   

##	The Data:📊

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;The International Development Association (IDA) is crucial in aiding the world’s poorest nations. The [data set](https://financesone.worldbank.org/ida-statement-of-credits-grants-and-guarantees-historical-data/DS00976) analyzed comes from the World Bank’s IDA Statement of Credits, Grants, and Guarantees - Historical Data and offers detailed insights into global lending practices.<br>

## Tools & Techniques🛠️

<ul>
  <li>SQL: 
      Extracted and aggregated the dataset with precision.</li>
  <li>Tableau & Excel: 
      Visualized trends to make findings accessible and actionable.</li>
</ul>

**Let's start uncovering the hidden stories behind global loans to understand how they shape economic growth and social development together!** 🌐✨

---

## The Analysis and Commentary:

### **OVER VIEW OF THE DATA**

#####	Return all of the table

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<img src="images/FinanceSQL/1CODE_DataOverView.png" alt = "1CODE_DataOverView.png" width ="150"><br>
<img src="images/FinanceSQL/1DataOverView.png?raw=true"/><br>

#####	Return the first 5 rows of the table, but only the borrower & due to IDA column<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<img src="images/FinanceSQL/2CODE_OverView5Row.png" alt = "2CODE_OverView5Row.png" width ="300"><br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<img src="images/FinanceSQL/2OverView5Row.png" alt = "2OverView5Row.png" width ="250">
      
#####	Total number of transactions<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;**Row:**<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<img src="images/FinanceSQL/3CODETotalCount.png" alt = "3CODETotalCount.png" width ="250"><br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;**Column:**<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<img src="images/FinanceSQL/3CODETotalCountColumn.png" alt = "3CODETotalCountColumn.png" width ="300"><br>
   
### **Payment Timeframe Analysis**

Which was the most recent to pay?<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<img src="images/FinanceSQL/22MostRecentPayCODE.png" alt = "22MostRecentPayCODE.png" width ="300"><br>
<img src="images/FinanceSQL/22MostRecentPayRESULT.png?raw=true"/><br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<img src="images/FinanceSQL/Tanzania.jpg" alt = "Tanzania.jpg" width ="150"><br>

### **DUE to IDA (US$) Attribute Analysis:**

  **🏆 The Biggest Borrowers:**   
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;At the forefront, The Ministry of Finance leads with the highest total loan amount, steering resources to tackle financial and developmental challenges. Regionally, South Asia dominates, with Africa following closely, reflecting their significant development needs.<br>

#####	The top 15 highest organization borrowers**<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<img src="images/FinanceSQL/4CODE_15Highest Borrower.png" alt = "4CODE_15Highest Borrower.png" width ="350"><br>
<img src="images/FinanceSQL/4Highest Borrower15.png?raw=true"/><br>

>  🥇The Ministry of Finance has the highest total loan amount.<br>

#####	Abbreviate one of the column names so it's easier to write<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<img src="images/FinanceSQL/5AbbreviateColumn.png" alt = "5AbbreviateColumn.png" width ="400"><br>

#####	List the top 15 highest Region borrowers:**<br>

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<img src="images/FinanceSQL/6CODE15highestRegionborrower.png" alt = "6CODE15highestRegionborrower.png" width ="400"><br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<img src="images/FinanceSQL/6Result15highestRegionborrower.png" alt = "6Result15highestRegionborrower.png" width ="250"><br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<img src="images/FinanceSQL/6Graph15highestRegionborrower.png" alt = "6Graph15highestRegionborrower.png" width ="300"><br>

>  🥇South Asia has the highest total loan amount, followed by Africa.

#####	What is the maximum, minimum, and average amount owed to the IDA?**<br>

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<img src="images/FinanceSQL/7CODEOwedAvg_Max_Min.png" alt = "7CODEOwedAvg_Max_Min.png" width ="300"><br><br>

#####	Overall Impact of Loans:📊
<ul>
  <li>Cumulative Loan Amount: Over $25 trillion, reflecting decades of developmental investments.</li>
  <li>Snapshot Loan Total: Nearly $210 billion in the most recent data—a significant portion of global financial aid.</li>
</ul>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<img src="images/FinanceSQL/8TotalLoan.png" alt = "8TotalLoan.png" width ="450">
  
#####	Loan amount to the IDA by Country**:<br>
<img src="images/FinanceSQL/9SumLoanAmount_CountryMap.png?raw=true"/><br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<img src="images/FinanceSQL/9CODESumLoanAmount_CountryDESC.png" alt = "9CODESumLoanAmount_CountryDESC.png" width ="200"><br><br>
  
>🌟 Top Loan Recipients:   
><ul>
>  <li>🇮🇳 India</li>
>  <li>🇧🇩 Bangladesh</li>
>  <li>🇵🇰 Pakistan</li>
>  <li>🇻🇳 Vietnam</li>
>  <li>🇳🇬 Nigeria</li>
></ul>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<img src="images/FinanceSQL/9CODESumLoanAmount_CountryASC.png" alt = "9CODESumLoanAmount_CountryASC.png" width ="500"><br>
 
><ul>
>  <li>Haiti has almost a $0 loan amount.</li>
>  <li>Costa Rica has had a big jump of $82,407 in loan amounts.</li>
></ul>

#####	Who has the most loans?**   
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;**Total Transactions by Country**<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<img src="images/FinanceSQL/10CODEHighestNoLoan.png" alt = "10CODEHighestNoLoan.png" width ="350"><br>
<img src="images/FinanceSQL/10MapHighestNoLoan.png?raw=true"/><br><br>
  
>	**India has the highest number of loans, while World and International Finance Corporation has the lowest amount.**<br><br>

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<img src="images/FinanceSQL/10ResultHighestNoLoan.png" alt = "10ResultHighestNoLoan.png" width ="450"><br>

###  **The Service Charge Rate Puzzle** 💡:

####	Key players in steep rates:<br>
-	**St. Kitts and Nevis:**   
    <ul>
      <li>📈 Interest rate: 3.68% (highest globally).</li>
      <li>🏦 Loans: 165, with $32M disbursed and $40M repaid.</li>
      <li>💡 Insight: Despite the high rate, repayment amounts exceed disbursed funds—a testament to strategic financial management.</li>
    </ul>
-	**Africa:**   
    <ul>
      <li>🌍 Lowest average interest rate: 0.09% across 2,891 loans.</li>
      <li>🤔 Observation: Low rates help balance the repayment burden for developing nations.</li>
    </ul>

#####	**The High and Low of Service Charges**

  <img src="images/FinanceSQL/11ServiceCharge_Country.png?raw=true"/><br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<img src="images/FinanceSQL/11ServiceCharge_CountryResult.png" alt = "11ServiceCharge_CountryResult.png" width ="400"><br>
  
<ul>
  <li>St. Kitts and Nevis has the highest Interest rate of **3.68**.</li>
  <li>Africa has the lower Interest rate of **0.09**.</li>
</ul>

#####	Service Charge Rate by Country  
######	**0 interest rate:**<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<img src="images/FinanceSQL/12Countries0IntRate.png" alt = "12Countries0IntRate.png" width ="400">

######	**Top 10 countries with the lowest interest rate:**<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<img src="images/FinanceSQL/13Countries_IntRateASC.png" alt = "13Countries_IntRateASC.png" width ="400">

######	**Top 10 countries with the highest interest rate:**<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<img src="images/FinanceSQL/14CountriesIntRateDESC.png" alt = "14CountriesIntRateDESC.png" width ="400">

######	Knowing that most countries have an average interest rate **under 2.0**, I filter the graph to show better variation.<br>
  <img src="images/FinanceSQL/14ServiceCharge_Country_Und2Map.png?raw=true"/><br><br>

###  CRITICAL INFLUENCERS ASSESSMENT Analysis:
####	**Geospatial Data Analysis:**🎯 The Project Insights That Matter<br>
#####	**St. Kitts and Nevis**
The AG Dev Support Project is the sole project with a service charge rate >1, spotlighting a unique financial model.
#####	**Macedonia:** 🚩 <br>
  59% of projects have an interest rate of 3.4%, making it a region of high financial strain.
#####	**Bangladesh:**<br>
  The Padma Bridge Project emerges as a powerhouse, with the region's highest active Original Principal loan amount.

######	**How many loans do St. Kitts and Nevis have?**
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<img src="images/FinanceSQL/15StKittsNoLoan.png" alt = "15StKittsNoLoan.png" width ="350">
  
######	**How many loans does Africa have?**
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<img src="images/FinanceSQL/16AfricaNoLoan.png" alt = "16AfricaNoLoan.png" width ="350">
  
######	**Return all column groups by country with a Service Charge Rate greater than 1 for St. Kitts and Nevis**
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<img src="images/FinanceSQL/17StKittsServChrgGreater1.png" alt = "17StKittsServChrgGreater1.png" width ="550">
######	Return selected columns groups by project name with a Service Charge Rate greater than 1 for St. Kitts and Nevis**
<img src="images/FinanceSQL/18StKittsProjectCreditStatusTable.png?raw=true"/><br>

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<img src="images/FinanceSQL/17StKittsServChrgGreater1CreditStatusPie.png" alt = "17StKittsServChrgGreater1CreditStatusPie.png" width ="350">

>St. Kitts and Nevis‘s disbursed loan amount is almost $32 million, and $40 million is repaying the loan amount.
>AG DEV Support is the only project under this category.

<br><br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<img src="images/FinanceSQL/15StKittsNoLoan.png" alt = "15StKittsNoLoan.png" width ="400">

🔄 Correlations That Speak Volumes:

-	**Repayment Amount** ↔️ Service Charge Rate:   
	-	A **positive correlation** suggests that higher repayments often incur higher service charge rates.   
	-	This highlights the importance of negotiating better repayment terms to manage financial burdens.
-	**Borrower Obligation** ↔️ Service Charge Rate:   
	-	A **negative correlation** reveals that larger borrower obligations tend to result in lower service charge rates.
	-	Could this be a hidden incentive for bigger development projects?<br><br>

  <img src="images/FinanceSQL/17StKittsServChrgGreater1_RepaidIDABar.png?raw=true"/><br>
  
  <img src="images/FinanceSQL/17StKittsServChrgGreater1_BorrowerObligationBar.png?raw=true"/><br>

######	Return selected columns group by Project Name and Credit Status for **St. Kitts and Nevis** with Service Charge Rate greater than 1**
  <img src="images/FinanceSQL/18StKittsProjectCreditStatusTable.png?raw=true"/><br>
  Only the **AG Dev Support Project** has a service charge rate greater than 1 in St. Kitts and Nevis.<br>

#####	**Macedonia and North Macedonia**
-	**59%** of Projects in Macedonia have a high interest rate of **3.4**.
-	**70%** of Projects in North Macedonia have a high interest rate of **3.39**


######	Macedonia, the former Yugoslav Republic of:<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<img src="images/FinanceSQL/18MacedoniaProjectCreditStatusTable.png" alt = "18MacedoniaProjectCreditStatusTable.png" width ="450"><br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<img src="images/FinanceSQL/18MacedoniaProjectCreditStatusGRAPH.png" alt = "18MacedoniaProjectCreditStatusGRAPH.png" width ="500">

######	North Macedonia, the former Yugoslav Republic of:<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<img src="images/FinanceSQL/18NorthMacedoniaProjectCreditStatusTABLE.png" alt = "18NorthMacedoniaProjectCreditStatusTABLE.png" width ="450"><br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<img src="images/FinanceSQL/18NorthMacedoniaProjectCreditStatusGRAPH.png" alt = "18NorthMacedoniaProjectCreditStatusGRAPH.png" width ="500">

###  Project Attribute Analysis

#####	**Top 20 Highest Original Principal Amount (US$) Project:**<br>   
  <img src="images/FinanceSQL/19CODEHighestPrincipalProject.png?raw=true"/><br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<img src="images/FinanceSQL/19HighestPrincipalProjectMAP.png" alt = "19HighestPrincipalProjectMAP.png" width ="500"><br><br>

>	SAC II, followed by IN: Elementary Education (SAC II) Project, ranked the highest in the original principal amount.   

<br>
#####	**Return all columns for SAC II and Elementary Education (SSA II) project**   
-	**South Asia** has a higher SAC II loan amount than Africa.   
-	Meanwhile, **Africa** has a higher original principal amount than the loan amount.<br>

  <img src="images/FinanceSQL/20SACII_ElementaryEdSSAIIProjectRESULT.png?raw=true"/><br>
  <img src="images/FinanceSQL/20SGRAPHPrincipleProjectCOUNTRY.png?raw=true"/><br>
  <img src="images/FinanceSQL/20SGRAPHPrincipleProjectREGION.png?raw=true"/><br><br>
  
###  Credit Status Analysis

#####	**Top 15 projects** for countries with the highest loan amount to the IDA with active credit status in **India, Bangladesh, Pakistan, and Vietnam**<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<img src="images/FinanceSQL/21CODEActiveCreditLoan.png" alt = "21CODEActiveCreditLoan.png" width ="450"><br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<img src="images/FinanceSQL/21PIEChartActiveCreditLoan.png" alt = "21PIEChartActiveCreditLoan.png" width ="400"><br><br>

**Bangladesh** has the highest total active Original Principal, while **India** has the highest active loan amount due.  
**BD: The Padma Bridge project** has a significantly higher total active Original Principal loan amount than other projects.<br>

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<img src="images/FinanceSQL/21BarChartActiveCreditLoan.png" alt = "21BarChartActiveCreditLoan.png" width ="500"><br>

#####	🏗️ **Types of Loans Across the Globe:**

-	**Guarantees**: 🇰🇪 **Kenya** leads with 1,248 loans.   
-	**Grants**: 🇦🇫 **Afghanistan** dominates with 12,302 loans.   
-	**Credits**: 🇮🇳 **India** takes the crown with 69,805 loans.   

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<img src="images/FinanceSQL/23CountryLoanTypeLoanCountPie.png" alt = "23CountryLoanTypeLoanCountPie.png" width ="350">

#####	**List the countries with the highest count of loans for each of the following "Guarantees," "Grants," or "Credits"**
Clasification starts with the letters of the credit Number IDs
<ul>
  <li>Guarantees (IDAB and IDAG): Kenya at 1248 number of loans </li>
  <li>Grants (IDAD, IDAH and IDAE): Afghanistan at 12302 number of loans</li>
  <li>Credits (all others): India at 69805</li>
</ul>
  <img src="images/FinanceSQL/23CountryLoanTypeLoanCount.png?raw=true"/><br><br>

 
---

## The Bigger Picture:

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;This analysis is more than just numbers—it's a window into how nations grow, rebuild, and thrive. Behind every loan lies a story of ambition, resilience, and innovation.<br>

## Re-emphasizing Key Takeaways 🌟📊:

1.	**Top Borrowers & Regions:**
	-	The Ministry of Finance holds the highest total loan amount.
	-	South Asia leads regional allocations, followed by Africa.
	-	🇮🇳 India, 🇧🇩 Bangladesh, and 🇵🇰 Pakistan top the list of loan recipients.
2.	**High-Interest Countries:**   
&nbsp;&nbsp;&nbsp;&nbsp;St. Kitts and Nevis faces the highest interest rate of 3.68%, with 165 loans totaling $32M disbursed and $40M repaid.</li>

3.	**Correlations in Repayment & Rates:**
	-	Positive correlation: Higher **repayments** are linked to higher service charge rates.
	-	Negative correlation: Larger **borrower obligations** correspond to lower service charge rates.   <BR>
	
>These findings 💡highlight the significance of strategic financial planning to manage repayment burdens and secure favorable loan terms👏, offering valuable insights for 🌍 policymakers and decision-makers✅. <br>

## Where Do We Go From Here 🚀✨:

&nbsp;&nbsp;&nbsp;&nbsp;🔜	👌Use these insights to inform financial and policy decisions, negotiate smarter loan terms, and promote sustainable global🌍 growth.<br>
&nbsp;&nbsp;&nbsp;&nbsp;🔜	✍️ Dive deeper into how financing drives projects that change lives.<br>
&nbsp;&nbsp;&nbsp;&nbsp;🔜	🗨️ Engage & Share your takeaways, 💡ideas for further analysis.<br>
&nbsp;&nbsp;&nbsp;&nbsp;🔜	Collaborate with Me: Reach out for collaboration or work opportunities—I’m ready to dive into data with you! 🌟<br>
  
<img src="images/FloralBorder.JPG?raw=true"/>
