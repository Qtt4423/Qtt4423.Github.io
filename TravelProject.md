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

**The Data:** [Link](https://www.kaggle.com/datasets/ndalziel/massachusetts-public-schools-data)<br>
  - 🗂️ nearly 4,900 Rows-Records<br>
  - 🗂️	20  Columns-Attributes<br>

    **Customer Attribute:**
      -  **Nominal Categorical Variables:** Gender, Marital Status, Occupation, Own Car, Passport
      -  **Discrete Quantitative Variable:** Customer ID, Age, Number of Children Visiting, Number of Person Visiting
      -  **Continuous Quantitative Variable:** Monthly Income<br>
    
    **Product Attribute:**
      -  **Nominal Categorical Variables:** Designation, Product Pitched, Type of Contact
      -  **Ordinal Categorical Variables:** City Tier, Preferred Property Star, ProdTaken
      -  **Discrete Quantitative Variable:** Number of Followups, Number of Trips, Pitch Satisfaction Score
      -  **Continuous Quantitative Variable:** Duration of Pitch<br><br>






**The Dashboard:** [Linked Tableau Dashboard](https://www.kaggle.com/susant4learning/holiday-package-purchase-prediction)<br>
breaks down key data to reveal where the money goes and how schools measure up in areas like academic performance and funding allocation.<br>

---
**The Analysis and Commentary:** [Video Link](https://www.loom.com/share/ff138cb1308142208182dc7022075286)<br>

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
