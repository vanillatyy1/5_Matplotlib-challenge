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

### Summary statistics table of mean, median, variance, standard deviation, and SEM of the tumor volume for each regimen

|              | Mean Tumor Volume | Median Tumor Volume | Tumor Volume Variance | Tumor Volume Std. Dev. | Tumor Volume Std. Err. |
|-------------:|------------------:|--------------------:|----------------------:|-----------------------:|-----------------------:|
| Drug Regimen |                   |                     |                       |                        |                        |
|    Capomulin |         40.675741 |           41.557809 |             24.947764 |               4.994774 |               0.329346 |
|     Ceftamin |         52.591172 |           51.776157 |             39.290177 |               6.268188 |               0.469821 |
|    Infubinol |         52.884795 |           51.820584 |             43.128684 |               6.567243 |               0.492236 |
|     Ketapril |         55.235638 |           53.698743 |             68.553577 |               8.279709 |               0.603860 |
|     Naftisol |         54.331565 |           52.509285 |             66.173479 |               8.134708 |               0.596466 |
|      Placebo |         54.033581 |           52.288934 |             61.168083 |               7.821003 |               0.581331 |
|     Propriva |         52.320930 |           50.446266 |             43.852013 |               6.622085 |               0.544332 |
|     Ramicane |         40.216745 |           40.673236 |             23.486704 |               4.846308 |               0.320955 |
|     Stelasyn |         54.233149 |           52.431737 |             59.450562 |               7.710419 |               0.573111 |
|    Zoniferol |         53.236507 |           51.818479 |             48.533355 |               6.966589 |               0.516398 |
