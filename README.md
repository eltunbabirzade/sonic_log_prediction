# Prediction of Sonic Log from Drilling Parameters and Wireline Logs
In the oil and gas industry, accurate prediction of subsurface properties is crucial for optimizing drilling operations and reservoir characterization. Sonic logs, such as the compressional wave slowness (DT), play a pivotal role in this process. However, acquiring complete well log data is often challenging, as certain logs may be missing or unavailable in some wells. This study focuses on addressing this challenge by employing supervised machine learning techniques to predict the DT log from available wireline logs and drilling parameters, utilizing data from the Volve field open database.

## Dataset Description
The training dataset comprised the three wells with complete DT logs, using NPHI, RHOB, GR, PEF, CALI logs, and drilling parameters (ROP, WOBAVG, FLOWIN, TORQUEAV, PUMPAVG) as features, while the missing DT logs in the other two wells served as the test data. Our study showcases the effectiveness of machine learning in filling gaps in well log data, ultimately enhancing the understanding of subsurface properties and aiding in the optimization of drilling operations.

## Repository Structure
The repository is organized as follows:
- [x] Data Acquisition: Download the dataset from [Equinor](https://www.equinor.com/) and save it to a local directory.

- [x] Data Loading: Explore the structure of the DataFrame by examining the column names, data types, and initial rows.
    
- [x] Data Cleaning and Preprocessing: Identify columns with missing values Handle duplicate data.
      
- [x] Exploratory Data Analysis (EDA): Conduct preliminary data exploration, and calculate summary statistics such as mean, median, and standard deviation. Visualize the data using plots and charts to identify patterns and relationships.

- [x] Visualization: Utilize matplotlib or other visualization libraries to create informative and visually appealing plots.
- [x] Prediction: Predict Sonic Log values based on Drilling and well logging data

- [x] Conclusion: Summarize the key findings and insights obtained from the data analysis. 

- [x] README.md: This file provides an overview of the project, including instructions on how to set up the environment, run the code, and reproduce the analysis.


## WorkFlow
![Workflow](https://github.com/eltunbabirzade/sonic_log_prediction/assets/86204008/1ecf9f52-1625-45a0-a14a-227b6b08c5f5)



## License
The code in this repository is licensed under the Apache License, Version 2.0.

For details, please refer to the [LICENSE](LICENSE) file.


## Collaborators
This project was developed and maintained by the following collaborators:
[Eltun Babirzade](https://github.com/eltunbabirzade), [Ramin Asgarli](https://github.com/raminasgarl1) 
