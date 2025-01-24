<img src="images/TravelProject.jpg?raw=true"/>

## **The Algorithm of Escape: A Statistical Dive from Passport to Crafting Perfect Vacations Packages**
 
---
**Background:**<br>
  Does the thought of a vacation 🛫 make your heart 💓 sing like mine? I often daydream about moments from my past vacations with sandy beaches 🐬 and mountain 🚞 retreats. If you’ve ever traveled through vacation packages, you will know the trick is finding the right one for your trip🧳.  But have you ever wondered how travel companies create the perfect vacation packages tailored just for you? I recently embarked on a project to explore this question and uncover how data can help a travel company refine its offerings👏.

**Why THIS Project?:**<br>
  The motivation behind this project was both personal and professional. As someone who loves traveling👙, I’ve always been curious about how companies know which vacation packages to promote. The travel industry is increasingly competitive, and I wanted to understand how data can enhance marketing strategies✍️. This project was unique because it aimed to optimize a company’s marketing budget and create tailored experiences for potential travelers🛄.

**What Readers Will Gain:**<br>
- 👋In this article, you will learn how data analytics can refine marketing strategies to shape the experience of 5,725 children and 4,888 adult travelers. We’ll uncover key customer insights, discover what influences purchasing decisions, and explore surprising findings that challenge conventional wisdom.🫰🏻<br>
- 👉Key Takeaways:
  - Pitch duration, designation, and marital status significantly impact whether a customer purchases a vacation package.
  - Children are a strong driving force for Sale.
  - Investing more in single and Tier 2 customer groups with local products can yield better marketing results.

**The Data:** [Link](https://www.kaggle.com/datasets/ndalziel/massachusetts-public-schools-data)
  - 🗂️ nearly 4,900 Rows-Records
  - 🗂️	20  Columns-Attributes
  - **Software used:** Python, R-studio, Excel, Tableau<br>
    
    **Customer Attribute:**<br>
      -  **Nominal Categorical Variables:** Gender, Marital Status, Occupation, Own Car, Passport
      -  **Discrete Quantitative Variable:** Customer ID, Age, Number of Children Visiting, Number of Person Visiting
      -  **Continuous Quantitative Variable:** Monthly Income<br>
    **Product Attribute:**<br>
      -  **Nominal Categorical Variables:** Designation, Product Pitched, Type of Contact
      -  **Ordinal Categorical Variables:** City Tier, Preferred Property Star, ProdTaken
      -  **Discrete Quantitative Variable:** Number of Followups, Number of Trips, Pitch Satisfaction Score
      -  **Continuous Quantitative Variable:** Duration of Pitch<br>
      
<img src="images/TravelDataOverView.png?raw=true"/>

---
**The Analysis and Commentary:**<br><br>

**1. Visuals and Insights**
**The Dashboard:** [Linked Tableau Dashboard](https://public.tableau.com/app/profile/quy.tran4833/viz/DashBoard_17376769592380/Dashboard1?publish=yes)<br>
I began by exploring the dataset to understand the distribution of variables and identify any missing values. Visualizations were created to observe trends and correlations between variables. Statistical analyses, including chi-square tests and stepwise regression, were conducted to determine significant predictors of product uptake.<br>

<img src="images/TravelDashBoard.jpg?raw=true"/><br>

  - Cities in tier 1 have the largest [product taken](https://public.tableau.com/app/profile/quy.tran4833/viz/TravelProject-ProductTypebyNo_TripsPersonChildren/ProdTaken-IncomebyCityTier?publish=yes), with the lowest average income and the highest [number of trips](https://public.tableau.com/app/profile/quy.tran4833/viz/TravelProject-ProductTypebyNo_TripsPersonChildren/NumberofTrips-AgebyCityTier?publish=yes), followed by tier 3, which has the highest average monthly income.<br>  
  - [King Product](https://public.tableau.com/app/profile/quy.tran4833/viz/TravelProject-Income-Product/IncomevsProductPitchedbyCityTier?publish=yes) has the smallest, least frequent, older visitors who lead in average monthly income and likelier to live in tier 1 cities, with preferred property star of 3.47.<br>
  - [Basic Product](https://public.tableau.com/app/profile/quy.tran4833/viz/TravelProject-ProductTypebyProdTakenPropStar/ProductTypebyProdTakenPropStar?publish=yes) has largest, most frequent, youngest [visitors](https://public.tableau.com/app/profile/quy.tran4833/viz/TravelProject-ProductTypebyNo_TripsPersonChildren/ProductTypebyNo_TripsPersonChildren?publish=yes) who lead in product taken count (552), with preferred property star of 3.58. <br><br>

**2. Predict Whether a Prod Taken**<br>
<img src="images/TravelProdTakenCorrelatedVariable.png?raw=true"/><br>

**Chi-Squares Analysis** – [R studio Code file](https://github.com/Qtt4423/Trip-and-Travel-Project/blob/main/1-DVsProdTaken/ProdTakenContinuousStepwise.ipynb)
<img src="images/TravelProdTakenChiSquares.jpg?raw=true"/><br>
- Result:<br>
<img src="images/TravelProdTakenCorrelatedResult.png?raw=true"/><br>

**Stepwise Regression - Best Fit Model:**  [Python- Jupyter Note Book file](https://github.com/Qtt4423/Trip-and-Travel-Project/blob/main/1-DVsProdTaken/ProdTakenContinuousStepwise.ipynb)
<img src="images/TravelProdTakenStepWise.png?raw=true"/><br>

**Summary**:

**Marketing Information:**<br>
  - Was pitched Basic and Deluxe packages with executives’ designation
  - Receive pitch duration above 30s.
  - Take an average of 3.4 trips<br>
**Customer Profile:**<br>
  - Have an average Age of above 30
  - Either single or married couples
  - Have monthly Income above 35000
  - Have a passport, preferably<br><br>

**3. Characteristics of Customers Who Took a Product**<br>
Predict No. of Trip & Person Visiting: [R-Studio File] (/Trip-and-Travel-Project/2-DVsTripVisitorProdTaken-1/ProTaken-Trip-VisistorsDVsObservation.R), [Manova File](https://github.com/Qtt4423/Trip-and-Travel-Project/blob/main/2-DVsTripVisitorProdTaken-1/ProdTakenMANOVA.R)<br>

<img src="images/TravelYesProdTakenManovaTable.png?raw=true"/><br>

**Stepwise Regression– Best Fit Model:** [Python- Jupyter Note Book file](https://github.com/Qtt4423/Trip-and-Travel-Project/blob/main/2-DVsTripVisitorProdTaken-1/VisitorOccupationStepWise.ipynb)<br>
Filter: Under 10 trips<br>
Continuous Variables: Age, Preferred Property Star, Number of follow-ups and children visiting<br>
Characters of Customers Take a Product<br>

 **Marketing Information:**<br>
  - Self-inquiry type of contact
  - City Tier 1 or 3
  - Either Manager preferably, or AVP or Executive Designation also performs well.
  - Preferred Property Star of 4 or 5
  - Pitch Satisfaction Score of 3<br>
 **Customer Profile:**<br>
  - Married or unmarried status
  - Age range of 37 - 47 and 54 - 56. (On average, take more than 4 trips)
  - High number of children visiting. The more children, the higher the number of trips and visitors.<br><br>

**4. Characteristics of Customers Who Did Not Took a Product** [GitHub directory folder](https://github.com/Qtt4423/Trip-and-Travel-Project/tree/main/3-DVsTripVisitorProdNotTaken-0)<br>

 **Marketing Information:**<br>
 - Are pitched with either Standard, Deluxe, or Super Deluxe products.
 - Receive the above 2 follow-ups, which yield similar to 4 follow-ups and above.
 - Although 5 and 6 followed yield slightly higher results, not much.<br>
 **Customer Profile:**<br>
 - In their 30s and 60s travel with most visitors. The older the customers are, the more trips they take.
 - Travel with children. The higher the number of children, the higher the number of trips and visitors.
 - Have an average monthly income of 20-30 thousand.<br><br>

**5. Predicting Sale Index ** [GitHub Directory File](https://github.com/Qtt4423/Trip-and-Travel-Project/tree/main/4-TravelFocusGroup/SaleIndex) <br>
Create Sale Index = Number of Trips * Person Visiting + Prod Taken
**Highest Sale Index Pivot Table:**<br>

<img src="images/TravelSaleIndexPivot1.png?raw=true"/><br>
  - Small Business, Basic Product for freelancers<br>

<img src="images/TravelSaleIndexPivot2.png?raw=true"/><br>
  - Small Business, Basic Product for freelancers
  - Pitch Satisfaction Score of 3 with a pitch duration shorter than 18 with a Preferred Property Star of 3.
  - Interestingly, except for the Pitch Satisfaction Score of 3, all other Pitch Satisfaction Scores have a Preferred Property Star of 5.<br>

<img src="images/TravelSaleIndexCityTiers.png?raw=true"/><br>
  - Single who travels with an average of 3 children with a Monthly Income Range under 200.<br><br>

**Predicting Sale Index - Machine Learning**
<img src="images/TravelSaleIndexMachineLearning.png?raw=true"/><br>

**Focus on customers who:**
 - Monthly income group above 20thousand
 - Travel with children
 - At least 30 years of age<br>

<img src="images/Indian Population Age Breakdown.png?raw=true"/><br>

<img src="images/Indian Population Map.png?raw=true"/><br>

** Citi Tiers Analysis:**
 - Tier 1: 100,000 and more population, Metropolitan center, densely populated, most developed, and higher living expense. Mumbai 12M population.
 - Tier 2: 50,000 to 99,999 population, Urban center, fastest growing tier.
 - Tier 3: 20,000 to 49,999 population, Semi-urban center, the underdeveloped and still evolving.<br>

<img src="images/TravelSaleIndexCityTiersIncome.png"/><br>
Tier 1 cities, with 63% of the customer base, have the highest average sale index even though they have lower average monthly incomes than tier 3 cities.<br>

<img src="images/TravelCityTiersChildrenPassportCar.png"/><br>
•	The more children visit, the more often they travel in all tiers (1 to 3).
•	The majority of customers do not have a passport and own a car. --> This insight suggests that they can benefit from local destinations.<br><br>

---
**Concise Summary:**
Insights led me to believe that a well-targeted marketing approach, informed by data analysis, can significantly enhance sales and customer satisfaction:<br>

**✅Marketing Factors:**<br>
 - Product Type: Basic and Deluxe packages are more appealing.
 - Customer Role: Executives show higher interest.
 - Pitch Length: Presentations over 30 seconds are more effective.
 - Travel Frequency: Customers averaging 3.4 trips are more inclined to buy.<br>
 
**✅Customer Demographics:**<br>
 - Age: Over 30 years old.
 - Marital Status: Both singles and married individuals.
 - Income: Monthly earnings above 35,000.
 - Passport Ownership: Having a passport increases purchase likelihood.<br>
 
**✅Target Segments:**<br>
 - Location: Residents of Tier 1 and Tier 3 cities.
 - Job Titles: Managers, Assistant Vice Presidents, and Executives.
 - Property Preferences: Those favoring 4 or 5-star accommodations.
 - Age Groups: Individuals aged 37-47 and 54-56.
 - Family Travelers: Customers traveling with multiple children.<br>

**Call to Action:**
  - 🔜 If you found this article insightful, let’s connect on LinkedIn! ✍️ <br>
  - 🔜 I’d love to hear your thoughts or answer any questions about the project..<br>
  - 🔜 If you or someone you know is looking to hire a data analyst, let’s talk!<br>
  
<img src="images/FloralBorder.JPG?raw=true"/>
