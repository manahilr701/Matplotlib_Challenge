                            Pymaceuticals Inc. - Anti-Cancer Drug Analysis
Overview:
This project involves analyzing the results of an animal study conducted by Pymaceuticals Inc., a pharmaceutical company specializing in anti-cancer medications. The study aimed to compare the performance of Pymaceuticals’ drug of interest, Capomulin, against other treatment regimens in treating squamous cell carcinoma (SCC), a commonly occurring form of skin cancer.

Files:
Mouse_metadata.csv: Contains metadata about the mice.
Study_results.csv: Contains results of the study, including tumor volume measurements over time.
pymaceuticals_starter.ipynb: Jupyter notebook containing the analysis.
Analysis
The analysis includes the following steps:

Prepare the Data:

Merged the Mouse_metadata and Study_results DataFrames.
Checked for duplicate records and removed them to ensure data integrity.
Generate Summary Statistics:

Calculated mean, median, variance, standard deviation, and SEM of the tumor volume for each drug regimen.
Visualizations:

Created bar charts to show the total number of rows (Mouse ID/Timepoints) for each drug regimen using both Pandas and Matplotlib.
Generated pie charts to show the distribution of unique female versus male mice in the study using both Pandas and Matplotlib.
Created a box plot to show the distribution of the final tumor volume for all mice in each treatment group.
Generated a line plot of tumor volume vs. time point for a single mouse treated with Capomulin.
Generated a scatter plot of mouse weight vs. average observed tumor volume for the entire Capomulin regimen.
Statistical Analysis:

Calculated the correlation coefficient and a linear regression model for mouse weight and average observed tumor volume for the entire Capomulin regimen.
Observations and Inferences
Effectiveness of Capomulin and Ramicane:

Both Capomulin and Ramicane treatments resulted in significantly lower final tumor volumes compared to Infubinol and Ceftamin.
There were no significant outliers for Capomulin and Ramicane, suggesting consistent results across different mice.
Correlation between Mouse Weight and Tumor Volume:

A strong positive correlation (correlation coefficient of approximately 0.842) was observed between mouse weight and average tumor volume for the Capomulin regimen.
The linear regression model showed a clear upward trend between weight and tumor volume.
Gender Distribution:

The distribution of male and female mice in the study is fairly balanced, ensuring that the results are not biased by gender differences.
Instructions
Clone the repository to your local machine.
Ensure you have Jupyter Notebook installed.
Place the provided CSV files in the same directory as the notebook.
Open pymaceuticals_starter.ipynb in Jupyter Notebook.
Run the cells sequentially to perform the analysis.
Requirements
Python 3.x
Jupyter Notebook
Pandas
Matplotlib
Scipy
Conclusion
This analysis provides insights into the effectiveness of different drug regimens in treating squamous cell carcinoma in mice. The findings suggest that Capomulin and Ramicane are more effective than Infubinol and Ceftamin in reducing tumor volume, with consistent results across different mice. Additionally, there is a significant correlation between mouse weight and tumor volume for the Capomulin regimen.
