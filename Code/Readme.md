# Data Query
## Problem Set 2: Regression Discontinuity
### Query Process
https://www.kaggle.com/datasets/riinuanslan/sleep-data-from-fitbit-tracker
The dataframe "Sleep_data" is found in an open datasource from kaggle. The data is a record of the sleep data of an individual from November to April, down by her apple watch. This dataframes includes detailed parameters of the sleep data, such as deep_sleep, sleep_hours. The overall sleep quality is measured by "SLEEP_SCORES", which can be used for this research. In my research, I wonder whether the sleep quality can be influecned by seasonal changes, for instance, from winter to spring. Therefore, this time-series data can be applied for conducting regression discontinuity. I first cleaned a few NAs in the data set. Then, I added the number of days since the author started recording, which can make the data processing easier. The days are splited at day 92, which is the last day of January marking the end of the winter. 


\begin{table}[H]
\centering
\begin{tabular}{|l|}
\hline
\textbf{Pseudo-Code for Data Query Process} \\ \hline
1. Connect to Data Source \\
2. Formulate Data Query \\
3. Execute Query against Data Source \\
4. Fetch Results into Data Structure \\
5. Process/Analyze Data \\
6. Close Connection to Data Source \\ \hline
\end{tabular}
\caption{Generalized Data Query Process}
\label{table:data_query_process}
\end{table}
