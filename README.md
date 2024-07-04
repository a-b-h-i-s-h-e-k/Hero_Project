# Hero_Project

# Superhero Analysis: DC vs. Marvel


## Overview
This project aims to analyze and compare the characteristics of superheroes from the DC and Marvel universes based on their qualities. The analysis highlights the parallels and discrepancies across superheroes in both realms, examining aspects such as power levels, durability, intelligence, and combat abilities.

## Data Sources
 - Marvel Super Heroes: Includes 3 CSV files with superhero datasets which have been slightly modified.
 - Marvel Comics Characters Stats and Powers: Provided inspiration for selecting the superhero dataset and determining what to do with it.

## Modifications
1. Added a weight column in marvel_characters_info.
2. Renamed datasets:
 - characters_stats.csv -> characterStats
 - superheroes_power_matrix.csv -> superPower
 - marvel_characters_info.csv -> heroesInformation

## Libraries Used
1. Tidyverse: Data manipulation and analysis (dplyr, ggplot2, tidyr)
2. plyr: Data splitting, application, and combination
3. reshape2: Data reshaping
4. readr: Reading rectangular data (like CSV files)
5. GridExtra: Layout and combining of multiple grid-based charts
6. ggplot2: Data visualization

## Data Preparation
1. Handling Missing Values: Converted -99 and - to NA.
2. Type Conversion: Updated variable classes in datasets.
3. Removed Unnecessary Columns: Dropped the first column in heroesInformation.

## Key Analyses
1. Height of Heroes
- Objective: Visualize the heights of the first 15 superheroes.
- Insights: Most heroes' heights range between 165 cm to 195 cm.

2. Most Common Eye Color
 - Objective: Count plot of eye colors among superheroes.
 - Insights: 'Blue' is the most common eye color, followed by 'Brown' and 'Green'.

3. Most Common Weight
 - Objective: Scatter plot of superhero weights.
 - Insights: Most heroes' weights range between 50 to 210 lbs.

4. Alignment Proportions
- Objective: Pie chart showing the proportions of "Good" and "Bad" alignments among superheroes.
- Insights: Visual representation of superhero alignments.

5. Durability Frequency
- Objective: Histogram of 'Durability' values.
- Insights: Most superheroes have high durability, indicating their ability to handle attacks.

6. Speed and Power
 - Objective: Combined analysis of speed and power among the top 38 superheroes.
 - Insights: Shows the relationship and ranking based on combined speed and power.

7. Gender Distribution
- Objective: Grouped bar plot of gender distribution in DC and Marvel.
- Insights: Both universes have more male characters, with Marvel having more female characters than DC.

8. Race Distribution
 - Objective: Comparison of the top 15 races in DC and Marvel.
 - Insights: Marvel has more 'Mutant' characters, while DC has more 'God/Eternal' characters.

9. Alignment Distribution
- Objective: Comparison of heroes, villains, and neutral characters in DC and Marvel.
- Insights: Marvel has more neutral and bad characters compared to DC.

10. Box Plot Comparisons
 - Attributes: Intelligence, Strength, Speed, Durability, Power, Combat
 - Insights: Detailed comparison of these attributes between DC and Marvel characters.

11. Top Characters by Attribute
 - Attributes: Intelligence, Strength, Speed, Durability, Power, Combat
 - Insights: Identifies and ranks the top characters in both universes for each attribute.
12. Superpowers Distribution
- Objective: Comparison of the top 20 superpowers in DC and Marvel.
- Insights: Marvel has more characters with super strength and stamina, while DC has unique powers like size - - changing and weapon mastery.


### Conclusion
This analysis provides a comprehensive comparison of superheroes from DC and Marvel, highlighting key differences and similarities in their attributes and characteristics. The visualizations and insights help in understanding the distribution and prevalence of various traits among superheroes from both universes.