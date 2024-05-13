**Exploring the Data with Pandas and Seaborn**<br>
**The dataset contains 7,461,226 ultra-marathon race records registered between 1798 and 2022 , from 1,641,168 unique athletes.**

The following columns (with data types) are included:

Year of event (int64)<br>
Event dates (object)<br>
Event name (object)<br>
Event distance/length (object)<br>
Event number of finishers (int64)<br>
Athlete performance (object)<br>
Athlete club (object)<br>
Athlete country (object)<br>
Athlete year of birth (float64)<br>
Athlete gender (object)<br>
Athlete age category (object)<br>
Athlete average speed (object)<br>
Athlete ID (int64)<br>

**Steps performed:** <br>
**1.Import Python Libraries:** <br>
The necessary packages are installed for this project i.e Pandas for data manipulation and Seaborn for data visualisation.<br>
**2.Reading dataset:** <br>
 Using the read_csv() function, data can be converted to a pandas DataFrame.<br>
**3. Initial Inspection:** <br>
An overview of the data using df.head(), .shape and so on.
Checked the data types with df.dtypes.<br>
**4. Data Cleaning:** <br>
Identified and handled missing values using methods like df.isnull().sum().
Find and address duplicates with df.duplicated().sum().<br>
**5. Univariate Analysis:** <br>
Analyze single variables at a time.
Use descriptive statistics with df.describe() for numerical data.
Create histograms, box plots, and density plots to visualize distributions.<br>
**6. Bivariate Analysis:**
Explore relationships between two variables.
Create scatter plots to identify trends and potential correlations.<br>
**7. Visualization:**
Effective visualizations are crucial for understanding data.
Use various plots like bar charts, pie charts, and heatmaps to represent categorical data.<br>
Conclusion












