# Analysis-of-Active-Video-Games-Sedentary-Habits-in-Children

### Motivation
The rising prevalence of screen time and its correlation with sedentary lifestyles in children initiated this project. It seeks effective interventions that could promote physical activity, using Active Video Games (AVGs) as a potential motivator due to their interactive and engaging nature.

### Why Build This Project?
This project was developed to address the critical issue of increasing sedentary behavior among children, with significant public health implications. By integrating autonomy into the choice of AVGs, it assesses whether this approach can lead to a meaningful increase in physical activity, informing future health interventions and policies.

### Tools Used
* R: Utilized for cleaning and preprocessing data to prepare it for analysis.
* Tableau: Used for creating dynamic and interactive visualizations to effectively present and analyze the data relationships.

### Key Learnings
* Data Pre-Processing: Handling and integrating complex datasets was essential for accurate analysis.
* Creating Dashboard: Demonstrated how effective visual representations, created through Tableau, help in interpreting complex data and communicating findings clearly.

### Useful Links:
* <a href="https://github.com/LakshmiPriyaDiwakar2706/Analysis-of-Active-Video-Games-Sedentary-Habits-in-Children/blob/main/actigraph_activity_data.xlsx">Actigraph Activity Data</a>
* <a href="https://github.com/LakshmiPriyaDiwakar2706/Analysis-of-Active-Video-Games-Sedentary-Habits-in-Children/blob/main/liking data.xlsx">Liking Data</a>
* <a href="https://github.com/LakshmiPriyaDiwakar2706/Analysis-of-Active-Video-Games-Sedentary-Habits-in-Children/blob/main/Data Cleaning.R">R Code file</a>

#### This project is based on a research study titled "Influence of Active Video Game Play upon Physical and Screen-Based Activities in Children." The dataset was obtained from USDA.gov, and the goal was to create a Tableau dashboard highlighting the key points discussed in the research paper. Additionally, we referred to other research papers to see if autonomy impacts children's physical activity levels through Active Video Games (AVG) or Traditional Active Play (TAP).

### Findings
* Baseline Comparison: In both the high and low autonomy groups, the average time spent in Moderate to Vigorous Physical Activity (MVPA) at baseline and week 10 was the same.
* Activity Trends: Visualized the average time spent in light, moderate, and sedentary activities across various stages (pre-intervention, during intervention, and post-intervention at baseline, week 1, week 3, week 6, and week 10). Sedentary activity was higher in both groups throughout all stages.
* Gender Differences: Moderate to vigorous activity was consistently higher in male participants compared to female participants across all weeks.
* Activity Categorization: Created a calculated column to categorize activity levels.

   IF [Sedentary] > [Light] + [Moderate] + [Vigorous] THEN "Not much Activity"
   ELSEIF [Sedentary] < [Light] + [Moderate] + [Vigorous] THEN "Some Activity"
   END
This formula helped visualize that high autonomy group activity levels were higher than the low autonomy group. Within the high autonomy group, activity levels remained consistent from baseline to week 10, whereas the low autonomy group showed a drop in activity at week 10 compared to pre-intervention and during intervention stages.

### Explore the Dashboard
Visit the interactive Tableau dashboard here: [Autonomy and Activity Dashboard](https://public.tableau.com/app/profile/lakshmi.priya.diwakar7591/viz/AutonomyandActivity/AutonomyandActivity)

[![Autonomy and Activity](https://github.com/LakshmiPriyaDiwakar2706/Analysis-of-Active-Video-Games-Sedentary-Habits-in-Children/blob/main/Autonomy%20and%20Activity.png)](https://public.tableau.com/app/profile/lakshmi.priya.diwakar7591/viz/AutonomyandActivity/AutonomyandActivity)
