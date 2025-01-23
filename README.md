# Youtube Channel Analysis using Python

**Introduction:**

The "YouTube Channels Dataset" data analysis project focuses on exploring and understanding a dataset containing information about the top 5000 YouTube channels. The analysis is conducted using the Python programming language, primarily leveraging the pandas and seaborn libraries for data manipulation and visualization

**Data Loading and Overview:**

The project begins by importing the necessary libraries, including pandas and seaborn. The dataset is loaded into a pandas DataFrame using the `pd.read_csv` function. Initial exploration involves displaying a sample of the dataset using the `head` and `tail` methods, showcasing the first and last rows, respectively. The shape of the dataset (number of rows and columns) is obtained using the `shape` attribute.

**Data Information:**

Further insight into the dataset is gained by using the `info` method, which provides details about the total number of rows, total number of columns, data types of each column, and memory requirements. This step is crucial for understanding the structure of the dataset and identifying any potential data type issues.

**Data Statistics:**

The overall statistics of the dataset are calculated using the `describe` method, providing a summary of numerical columns. The formatting of floating-point numbers is adjusted for better readability.

**Data Cleaning:**

Data cleaning steps involve replacing '--' values with NaN, checking and handling null values, and converting data types of specific columns. The `replace` method from the numpy library is used for replacing values, and the `isnull` method is employed to identify and visualize null values. Rows with null values are dropped using the `dropna` method.

**Feature Engineering:**

The 'Rank' column is cleaned by removing unwanted characters and converting it to integers. Similar cleaning steps are applied to 'Video Uploads' and 'Subscribers' columns, ensuring numeric consistency and handling missing or non-numeric values appropriately.

**Exploratory Data Analysis (EDA):**

EDA involves analyzing key metrics such as average views, top channels by video uploads, and creating a correlation matrix to understand relationships between numeric features. Visualizations using seaborn and matplotlib aid in presenting insights about grades, video uploads, average views, subscribers, and video views.

