# **Historical Analysis of FIFA World Cup Outcomes**
---------------------------------------------------------------------------------

# Purpose:
The goal was to explore trends as well as patterns in the FIFA World Cup tournament, with key insight into metrics eg. winning team , goals statistics, and attendance over the years.

# Objectives:
 The analysis
 1. **identifies the dorminant teams**. Which teams have had more showings/attendance to the worldcup and frequent winners over the years.
 2. **Asses the tournament evolution over the years.** Has the attendance increased over the years and what changed.
 3. **Goal statistics**- With the statistics what is shown regarding the number of goals over the years.

# Data
Find the data [here](https://github.com/Kitemange/Worldcup/blob/230a490af53876543bcadad59b5697781d004c41/world_cup_results%20(1).xlsx)
and the Dashboard [here]([https://github.com/nyarotoyi/SQL-Portfolio/blob/main/llin_%20distribution_analysis/lln_distributions_analysis.sql](https://github.com/Kitemange/Worldcup/blob/036f373c7c2a333e30edd47f66887213583fbc8e/Tableau)).

Data Source [Tableau public (https://public.tableau.com/app/learn/sample-data). It contains the following Sheets:

1. WorldCupMatches.

2. WorldCups.

## Solutions Approach
 After cleaning the data of duplicate data different sheets were created:

 1. **Matches over the Years**. Used visualize how the number of matches has changed over the years.
     ![Matches over the years](https://github.com/user-attachments/assets/2b1d39b1-fe1a-425c-8e73-fb8acd529a8b)
 2. **Winning Countries.** show the distribution of World Cup wins among different countries.
    ![Screenshot (20)](https://github.com/user-attachments/assets/fa76b617-9ab9-4693-b164-d46a627cc85e)
3. **Goal statistics**- To compare the goal-scoring performance of different teams, filtering the goals by minimum of 40 home goals per team as well as more or 20 goals for away goals for easy readability
     ![Home Goals](https://github.com/user-attachments/assets/c303c803-5523-4ed0-982f-40f2ce96fa2b)
     ![Away Goals](https://github.com/user-attachments/assets/3f3b312e-af25-46fd-8ed8-0933ecebbc59)
4. Host countries: This indicates which continents have  hosted the corld cup as well as country.
    ![Screenshot (24)](https://github.com/user-attachments/assets/be0ca0a8-1727-48e2-8520-7774b57d3b67)

## Findings
The screenshot you provided appears to be a Tableau dashboard titled "Worldcup Overview Dashboard." Here are the key findings based on the visual elements displayed:

1. **Match Outcome Over Time**:
   - The top line graph shows the match outcomes over time, indicating a generally upward trend in terms of goals but in correlation of the number of matches played.

2. **Home Team Goals vs. Away Team Goals**:
   - Bar charts show the goals scored by home teams and away teams:
     - **Home Team Goals**: Mexico leads in home goals, followed by Belgium and Korea.
     - **Away Team Goals**: Brazil is the top scorer as an away team, followed by Spain and Italy.

3. **Winners**:
   - A treemap highlights the World Cup winners:
     - Brazil has won the most, followed by Germany (FR) and Italy. Other notable winners include Uruguay, Argentina, and France.

4. **World Cups Attendance**:
   - The bar chart on attendance shows fluctuating attendance figures, with a notable peak in one of the tournaments, potentially the 2014 World Cup in Brazi, which had high attendance.

### Summary of Findings:
- **Brazil** stands out as a dominant force in World Cup history winning it **5** times as well as excelling in away goals.
- **Home advantage** is significant for countries like Mexico, which leads in home goals.
- **Attendance trends** have varied over the years, with specific tournaments drawing significantly larger crowds.
- **Geographical Distribution of World Cup Hosts** The World Cup, being a global event, has been hosted across the world, this in return reflects on the tournament international nature and its wide acceptance. The showcases FIFA's efforts to spread the event across different regions, promoting the sport globally and allowing diverse cultures to experience the excitement of the tournament firsthand.
- 
    **1. Host Continents Overview**
    The World Cup has been hosted on five continents:
    - **Europe**: Europe has hosted the World Cup the most, with countries like Germany, France, and Italy playing host. The continent's strong football tradition and infrastructure have made it a popular choice.
    - **South America**: As the birthplace of some of the most passionate football nations, South America has hosted the tournament multiple times, with Brazil, Argentina, and Uruguay being key hosts.
    - **North America**: The United States and Mexico have hosted the World Cup, with Mexico being the first country to host it twice, highlighting its significant football culture and infrastructure.
    - **Asia**: Asia made its debut as a host continent in 2002 when South Korea and Japan co-hosted the tournament, a milestone in spreading football’s popularity across the globe.
    - **Africa**: In 2010, South Africa became the first African nation to host the World Cup, marking a historic moment and demonstrating the sport's growing influence on the continent.

    **2. Impact of Host Selection on Attendance**
       The choice of host country has significantly influenced World Cup attendance. Tournaments held in Europe and South America typically draw large crowds, reflecting the strong football culture in these regions. However, the 1994            World Cup in the United States set a record for average attendance(69,174 per match), demonstrating the growing popularity of football even in countries where it is not the dominant sport. 

    **3. Continental Rotation and Future Hosting**
     In recent years, FIFA has shown a trend toward rotating the tournament between different continents to ensure global representation. This approach has seen the World Cup hosted in diverse regions, including Asia and Africa, and will       continue with the last tournament being hosted in the Middle East (Qatar 2022) and the next on in North America (USA 2026).

    **3. Tally of Participating Countries**
    The diversity of host countries is also reflected in the tally of participating nations boasting a total of 79 different countries that have tken part in the tournament, with countries from every inhabited continent having competed        in the tournament.
