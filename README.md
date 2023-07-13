# Matplotlib

## Background

You've just joined Pymaceuticals, Inc., a new pharmaceutical company that specializes in anti-cancer medications. Recently, it began screening for potential treatments for squamous cell carcinoma (SCC), a commonly occurring form of skin cancer.

As a senior data analyst at the company, you've been given access to the complete data from their most recent animal study. In this study, 249 mice who were identified with SCC tumors received treatment with a range of drug regimens. Over the course of 45 days, tumor development was observed and measured. The purpose of this study was to compare the performance of Pymaceuticals’ drug of interest, Capomulin, against the other treatment regimens.

The executive team has tasked you with generating all of the tables and figures needed for the technical report of the clinical study. They have also asked you for a top-level summary of the study results.

## Analysis

As a senior data analyst at Pymaceuticals, Inc, I have received a data set from a study with 249 mice who were identified with SCC tumors and received treatment with a range of drug regimens. The objective of the study was to identify the performance of the laboratory drug (Capomulin) against other treatment regimens. So, the first step was to identify if the data that I had was clean. For that reason, I decided to check the variable "Mouse ID", and I found that I had one duplicate ID. After that, I completed an analysis, finding the bellow results:

*Summary Statistics where it can see the different drug regimens with their respective mean, median, variance, standard deviation, and standard error of the tumor volume. According to the above, it can say that the mean and median of Capomulin and Ramicane are the lowest for that reason they have the lowest and symmetric distribution of tumor volume with respect to the other drug regimens. Additionally, it can say that the highest variance and standard deviation, and dispersion were from Ketapril, Naftisol, Placebo y Stelasyn. It could indicate the highest variability in the tumor volume in those drug regimenes.

*As well as it can see in the bar chart that Capomulin and Ramicane were the drugs that had more than 200 observed mouse timepoints, on the other hand, Propriva was the drug with less than 150 observed mouse timepoints.

*Moreover, the pie chart shows the mice's sex distribution in the study. It can see that 51% were male and 49% were female.

*Also, I generated a box plot that shows the distribution of the tumor volume for each treatment group. If i zoom to the Capomulin box i could say that the median is close to the first quarter and the superior outlier was more or less 48 and the lower outlier was more or less 23. If i Compared it with the others i could say that the best drug regimenes according with the final tumor volume distribution were Capomulin and Ramicane.

*With the line plot of tumor volume vs. time point for a single mouse treatment with Capomulin. It can see that with more days of treatment with Capomulin the tumor volume is going down.

*It was a strong correlation between mouse weight and average tumor volume, as was demonstrated in the linear regression model of Capomulin drug mice. The more weight of the mouse, the greater the risk of having a tumor in the mice.
