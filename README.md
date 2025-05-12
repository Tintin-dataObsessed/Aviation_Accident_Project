# Aviation_Accident_Project
Analysis of aviation accident data from 1962 to 2023 about civil aviation accidents and selected incidents in the United States and international waters.

# Business understanding
Listing the goal of the analysis, the problem which involves the breaking down and analysing the data to find the lowest risk Aircraft. This will help the stakeholders to choose the right aircraft to purchase and invest in.

# Data understanding
The data is from the "Aviation Accident Database & Synopses, up to 2023". I loaded the data and looked at the two datasets. Using describe, I got the basic descriptive statistics, and using info, I was able to get an overview of the dataset. I then gave a summary of the data and limitations.

# Data Preparation
To clean the data, I searched and removed missing values by filling the floats with an average value and dropping smaller values that would not affect the dataset.
I used N/A to preserve the data. For duplicates, the unique ID was identified and searched for the duplicates the dropped.

# Data Analysis
First, for further accuracy, the text was all converted into small letters for the categories. I started by looking at accidents and incidents concerning the Make and Model of aircraft, looking at the least accident-prone and least injury-prone. A recommendation given on models and makes by accident/incident value, concluding with data at looks at incidents and the lowest amount of incidents.

The second was the on-air category, which includes different kinds of aircraft that are categorized by Fatal injuries in either an incident or an accident. Creating a graph and a data set that lists all categories that have the highest and lowest injuries.

Lastly, we look specifically at airplanes, filtering for airplanes and concluding that although most injuries in aircraft are airplanes, you can further filter for the lowest injuries you get a list of all airplanes that are considered to be safe. This means minor damage, lower serious injury, etc.

# The Repository
The CSV files ae stored inside a folder called Data.
The repo contains the presentation.pdf , the Airplane_Analysis.ipynb ,the cleaned_AviationData.csv for the tableau, and the Readme file.
Other include the presentation.ppt file and the tableau file.

# links
Here is the link to the Tableau: https://public.tableau.com/views/Accident_Aviation/Dashboard4?:language=en-US&publish=yes&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link
