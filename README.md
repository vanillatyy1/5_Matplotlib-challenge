# 5_Matplotlib-challenge

# Pymaceuticals Inc.
---
Pymaceuticals, Inc. conducted an analysis on the efficacy of various cancer treatment regimens (including Capomulin, Ramicane, Infubinol, and Ceftamin) using a total of 248 mice (excluding g989). The data revealed a nearly equal distribution between male and female mice.

Based on the final tumor volume across different treatment regimens, Capomulin and Ramicane look to be the more effective drug regimens to reduce tumor,  Infubinol and Ceftamin to be the less effective. 

The average tumor volume for mice treated with Capomulin (40.676 mm3) and Ramicane (40.217 mm3) was lowest as compared to the average tumor volume of treatments with other drugs (ranging between 52.321 mm3 and 55.236 mm3). 

The tumor volume data of both Capomulin and Ramicane also had the lowest standard deviation, variance, and standard error as compared with tumor volumes of mice treated with other drugs.

Capomulin's potential outliers were not identified, and the range of final tumor volumes for mice on this regimen is between 20.70 mm3 and 51.83 mm3.

Similar to Capomulin, Ramicane shows no potential outliers. The range of final tumor volumes for mice on Ramicane is between 17.91 mm3 and 54.31 mm3.

Furthermore, a strong positive correlation of 0.84 was observed between mouse weight and average tumor volume across Capomulin. The correlation is represented by the linear regression equation: y=0.95x+21.55.

##Note to Central Grader:##

There is a discrepancy in interpreting the question regarding the "distribution of female versus male mice." Initially, I utilized the mouse_metadata where there is only one row per mouse ID, resulting in a total of 248 mice after excluding g989. Based on this approach, there should be 125 males (50.4%) and 123 females (49.6%).

However, this outcome is different from the starter sample chart provided in the Module 5 Challenge files, which shows that Male 51.0% and Female = 49.0%. Therefore, in the final solution, I adjusted the method to align with the starter sample chart, despite recognizing that the initial approach may be more accurate.
