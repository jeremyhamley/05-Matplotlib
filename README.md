# 05-Matplotlib

Matplotlib Pymaceuticals

Jeremy Hamley


The data analyzed using Python and Pandas in this Jupyter notebook explores the effectiveness of tumor treatment using the drug Capomulin.
The data that was used for this analysis comes from a tumor study that included the drug Capomulin along with nine additional drugs.
Based on the analysis of the treatment study data, I have observed the following:

1- In comparing all ten drugs that were used to treat mice for tumors, Capomulin was the second most effective treatment for inhibiting tumor growth in the mice used in the study.
    Capomulin was a close second to Ramicane, which was the most effective treatment for the tumors. 
    Both the average tumor volume and the final tumor volume for mice treated with Capomulin in this study was the second lowest.
    
2- In focusing on four of the most promising drug treatments (Capomulin, Ceftamin, Infubinol, and Ramicane), the study data only included one outlier for the final tumor volume calculation.
    The single outlier was for Mouse ID c326 being treated with Infubinol.  The final timepoint for Mouse c326 was day 5 and the final tumor volume was lower than the initial tumor volume. 
    Besides mouse c326, all the mice being treated with Infubinol showed an increase in tumor volume over the entire study.
    
3- The most positive result for mice treated with Capomulin was found in Mouse ID s185.  The final tumor volume for Mouse s185 was 23.34.
    The average final tumor volume for mice treated with Capomulin was 38.13.  The final tumor volume for Mouse s185 displays some of the most promising results for Capomulin.

4- There is a positive correlation between mouse weight and average tumor volume.  As the weight of the mouse increases, the average tumor volume increases. 
    The correlation coefficient between mouse weight and average tumor volume for Capomulin is 0.84.


The data analyzed includes the following:  

 - Ten different drugs used to treat tumors.
 - Roughly 25 mice per drug studied over the course of 45 days.
 - data includes mouse gender, weight, age, and tumor volume.

This Jupyter notebook includes:

 - summary statistics table of mean, median, variance, standard deviation, and SEM of the tumor volume for each regimen

 - a bar plot showing the total number of mice for each treatment throughout the course of the study

 - a pie plot showing the distribution of female versus male mice

 - for four promising treatments: Calculate quartiles, IQR, upper and lower bounds, and identify outliers

 - a box plot of the final tumor volume of each mouse across four regimens of interest

 - a line plot of time point versus tumor volume for a mouse treated with Capomulin

 - a scatter plot of mouse weight versus average tumor volume for the Capomulin regimen - includes correlation coefficient and linear regression model 





