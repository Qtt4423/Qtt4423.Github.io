<img src="images/NBA/1DunkingTheData.png?raw=true"/>

# "Dunking The Data: <br>A Tableau Showcase of 🏀 NBA Insights"
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;**2024-2025 Season**
<br><br><br>

---

## **Background:**
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;On a recent trip to San Francisco, in addition to visiting the Oracle campus, I had an unforgettable experience at San Francisco's pier during the Chinese New Year parade celebrations. Imagine this: a renowned NBA player engaging in a friendly shooting contest with a local at the bustling pier. It struck me how sports unite people, igniting excitement and stirring emotions. Later that day, I was captivated by Michael Jordan's commentary, reliving iconic moments that define the NBA. This blend of inspiration and nostalgia-fueled my desire to dive into the world of NBA statistics, leading me to my latest project: a data analysis of the 2024-2025 NBA season using Tableau.

## **Why THIS Project?**
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;My journey into data science has been both thrilling and daunting. I wanted to create something that resonates with my passion for sports and showcases statistics' influential role in making crucial decisions in the NBA, from trades to game strategies. With an abundance of resources available online, this project became a compelling way for me to build my portfolio while having fun. Exploring NBA data could also be an engaging experience for you, dear readers!<br><br>

## **What Readers Will Gain**
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;In this article, you'll discover the fascinating insights I uncovered about the NBA. I will share key findings from my analysis, highlight surprising statistics, and showcase visual representations of the data that bring the numbers to life. You’ll also learn how these insights can influence better decision-making in sports.<br><br>

## **Key Takeaways**
  - The Denver Nuggets lead in total points scored during the NBA season.
  - Shai Gilgeous-Alexander and Anthony Edwards are the top individual scorers.
  - Teamwork, reflected in assists and rebounds, is as important as scoring in evaluating player performance.<br><br>
    <img src="images/NBA/2KeyPlayers.png?raw=true"/>

## [**The Data:**](https://www.basketball-reference.com/leagues/NBA_2025_totals.html#totals_stats)
I sourced my dataset from [Basketball-Reference](https://www.basketball-reference.com/leagues/NBA_2025_totals.html#totals_stats). <br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;🏀&nbsp;&nbsp;It includes 33 columns and 633 rows detailing player and team performance metrics such as points made, assists, rebounds, and shooting percentages. <br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;🏀&nbsp;&nbsp;This rich dataset was ideal for my project because it provided a comprehensive view of players' contributions throughout the season.<br>
    <img src="images/NBA/3KeyDefinition.png?raw=true"/><br><br>
    <img src="images/NBA/4PositionDefinition.png?raw=true"/>
<br><br>

---

[**The Tableau Story Link**](https://public.tableau.com/app/profile/quy.tran4833/viz/2025NBA/AnalysisforNBA122024?publish=yes)<br>

## **The Analysis Process and Commentary:**
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;My analysis began with cleaning the data to ensure accuracy and consistency. Once cleaned, I transformed the data into various visual formats using Tableau. I created bubble graphs, heat maps, and tree maps to illustrate key statistics effectively. I was surprised to discover that the team with the highest total points also excelled in three-pointers, challenging my initial belief that star players solely drive success.<br><br>


**Visuals and Insights**
### **1. Total Scores Made:**
  [<img src="images/NBA/5TotalScore.png?raw=true"/>](https://public.tableau.com/app/profile/quy.tran4833/viz/2025NBAStack/TeamsvsTotalPointsScored?publish=yes)<br>
&nbsp;&nbsp;&nbsp;&nbsp;🏀&nbsp;&nbsp;This visualization reveals that the **Denver Nuggets** led all teams in total points scored. <br>
&nbsp;&nbsp;&nbsp;&nbsp;🏀&nbsp;&nbsp;Individual performances stood out, with **Shai Gilgeous-Alexander** scoring the most at 1,696 points, **Anthony Edwards** at 1,460, and **Nikola Jokic** at 1,458. <br>
    <img src="images/NBA/6TopScores.png?raw=true"/><br>
&nbsp;&nbsp;&nbsp;&nbsp;👉&nbsp;&nbsp; This visual showcases team performance and highlights the standout players who make a difference.<br>

### **2. Team Players Bubble Graph:**
  <img src="images/NBA/7PlayersSpotLight.png?raw=true"/><br>
&nbsp;&nbsp;&nbsp;&nbsp;👉&nbsp;&nbsp; This graph demonstrates player teamwork using points, assists, and rebounds.<br>
  - ⛹️**Nikola Jokic** stands out as a center with remarkable statistics, highlighting that scoring alone isn’t the entire picture.
  - ⛹️‍♂️Meanwhile, **Shai Gilgeous-Alexander** tops the points leaderboard but provides fewer assists.<br>
    [<img src="images/NBA/8PointsAstTrb.png?raw=true"/>](https://public.tableau.com/app/profile/quy.tran4833/viz/2025NBABubble/Bubble?publish=yes)<br>
&nbsp;&nbsp;&nbsp;&nbsp;👉&nbsp;&nbsp; This analysis illustrates how various player roles uniquely enhance a team’s success.<br>

### **3. Assist Point Tree Map:**
Do you wonder how position affects a player's performance?  Me too.
  [<img src="images/NBA/9AssistTreeMap.png?raw=true"/>](https://public.tableau.com/app/profile/quy.tran4833/viz/2025NBAStack/AssistByPos?publish=yes)<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;🏀Leading the scoring charts is the point guard, **Trae Young**. <br> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;🏀Interestingly, centers such as **Jokic** and small forwards such as **LeBron James** are also among the top scorers, reflecting a shift in conventional roles. <br>
    <img src="images/NBA/10AssSummary.png?raw=true"/><br>
👉&nbsp;&nbsp;This visualization emphasizes the significance of assists in measuring a player's overall influence.<br><br>

### **4. 3-Pointers Heat Map**
#### **Team⛹️⛹️‍♂️⛹️‍♀️:**
This heat map highlights which teams excel at three-point shooting.<br>
    [<img src="images/NBA/11-3PointersHeatMap.png?raw=true"/>](https://public.tableau.com/app/profile/quy.tran4833/viz/2025NBAHeatMap/3Pointersform_?publish=yes)<br>
  - The **Dallas Mavericks** and **Memphis Grizzlies** showcase differing performances that highlight the extremes of shooting accuracy. The **Dallas Mavericks** secured a flawless score of 1 in the center position, converting their only attempt. In contrast, the **Memphis Grizzlies** missed all 3-pointers from their small forward position.
  - The **Cleveland Cavaliers** and the **Golden State Warriors** scored 0 in the center position.
  - Notably, the **Denver Nuggets** consistently succeed across positions, with several players achieving impressive shooting percentages of **36%** to **42%**.
  - The centers for the **Sacramento Kings** and **New York Knicks** earned a notable score of **43%** in 3-point attempts.<br>
    <img src="images/NBA/12-3PointersSummary.png?raw=true"/><br>

#### **⛹️‍♀️Players:**
<br>  [<img src="images/NBA/11b-3PointersPlayer.png?raw=true"/>](https://public.tableau.com/app/profile/quy.tran4833/viz/2025NBAHeatMapPlayer/3Pointersform_Players?publish=yes)<br>    
  - Among the top players, many are small forwards, led by **Anthony Edwards**, who has **536** points at a **42%** success rate.
  - The only power forward, **Jayson Tatum**, ranks second with **528** points, achieving **35.8%** on all attempts.
  - Point guard **Stephen Curry** follows closely in fourth place with **503** points and a success rate of **38.9%**.<br>
<br><br>

---

## **Main Takeaways:**
  - 🏀A great team is more than just a collection of star players; it requires collaboration across different positions.
  - 🏀Scoring is vital, but contributions in assists and rebounds are equally crucial for overall team success.
  - 🏀Players like Nikola Jokic and Trae Young exemplify how diverse skills contribute to a team's achievements.<br><br>

## **Call to Action:**
&nbsp;&nbsp;&nbsp;&nbsp;I’d love to connect with fellow sports enthusiasts and data analysts! If you have thoughts or questions about my project, please comment below or contact me on LinkedIn. Let's talk about whether you or someone you know requires a data analyst!<br><br>
  
<img src="images/FloralBorder.JPG?raw=true"/>
