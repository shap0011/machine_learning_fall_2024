## Machine Learning Portfolio

### Project 1: Core features of the Pandas library

[Click to open the file...](https://github.com/shap0011/machine_learning_fall_2024/blob/main/Pandas_Class.ipynb)

In the `Pandas_class.ipynb` file, I explore the core features of the Pandas library, a vital tool for data manipulation in Python. The file covers the following topics: 

<details>
  <summary>Click to see details</summary>

<ul>
  <li><strong>Creating a Python Library and Accessing it in Google Colab</strong>: Mounting a Google Drive folder to integrate external files into the Colab environment.</li>
  <li><strong>Importing Modules (Pandas)</strong>: Setting up the environment for efficient data analysis.</li>
  <li><strong>Pandas DataFrame</strong>: Reading data from a CSV file and exploring structured data tables.</li>
  <li><strong>Indexing DataFrame</strong>: Utilizing <code>.loc</code> and <code>.iloc</code> methods to perform operations such as retrieving values from specific rows and columns, selecting multiple rows, and specifying ranges of rows and columns.</li>
  <li><strong>Manipulating DataFrame</strong>: Executing operations such as adding new columns and rows, sorting the DataFrame, dropping rows and columns, removing duplicates, and checking for missing values.</li>
  <li><strong>Reading Data from Different Sources</strong>: Loading datasets from formats like <code>.xlsx</code>, <code>.txt</code>, <code>.zip</code>, <code>.html</code>, and <code>.json</code>. </li>
</ul>

<p>This project highlights practical skills in data handling.</p>  

</details>

---

### Project 2: Descriptive Statistics - Goodlife Fitness Case Study
[Click to open the file...](https://github.com/shap0011/machine_learning_fall_2024/blob/main/Goodlife_Fitness_Solution.ipynb)

In the `Goodlife_Fitness_Solutions.ipynb` file, I perform a descriptive analysis to create customer profiles for each GoodLife Fitness membership option. This analysis explores key statistical insights and visualizations, covering the following topics:  

<details>
  <summary>Click to see details</summary>
  <ul>
  <li><strong>Importing Libraries and Loading the Dataset</strong>: Import the necessary Python packages and load the <code>GoodlifeFitness.csv</code> dataset.</li>
  <li><strong>Basic Data Exploration</strong>: Print basic information about the dataset, check for null values, and review the data's structure.</li>
  <li><strong>Univariate Analysis</strong>:
    <ul>
      <li>Examine the five-number summary statistics.</li>
      <li>Analyze the dataset's summary, including descriptive stats for categorical data.</li>
    </ul>
  </li>
  <li><strong>Visualization of Numerical Distributions</strong>:
    <ul>
      <li>Plot the distribution of numerical columns such as <code>Age</code>.</li>
      <li>Create boxplots to identify outliers in <code>Age</code>.</li>
    </ul>
  </li>
  <li><strong>Categorical Data Analysis</strong>:
    <ul>
      <li>Determine value counts for each categorical column, including <code>Type</code>.</li>
      <li>Calculate the percentage distribution of user types using normalization.</li>
    </ul>
  </li>
  <li><strong>Bivariate Analysis</strong>: Visualize relationships, such as plotting a boxplot to compare <code>Income</code> with <code>Membership Type</code>.</li>
  <li><strong>Multivariate Analysis</strong>:
    <ul>
      <li>Use <code>pd.crosstab</code> to analyze data across <code>Gender</code> and <code>Type</code>.</li>
      <li>Apply <code>pd.pivot_table</code> to explore data by <code>Income</code> and <code>Type</code>. </li>
      <li>Create scatter plots using Pandas for further insights.</li>
    </ul>
  </li>
</ul>

<p>This case study demonstrates the application of descriptive statistics and visualization techniques to uncover actionable insights regarding fitness memberships.</p>

</details>

---

### Project 3: Standardization of Normal Variables - Z-Score Analysis 
[Click to open the file...](https://github.com/shap0011/machine_learning_fall_2024/blob/main/Z_score_Statistics.ipynb)

In the `Z_score_Statistics.ipynb` file, I perform standardizing normal variables using the Z-score method. This file includes the following steps: 

<details>
  <summary>Click to see details</summary>

<ul>
  <li><strong>Mounting Google Drive in Google Colab</strong>: Access files stored in Google Drive to enable seamless data loading.</li>
  <li><strong>Importing Libraries and Loading the Dataset</strong>: : Load the necessary Python packages and read the <code>scores.csv</code> file into a DataFrame.</li>
  <li><strong>Visualizing the Data Distribution</strong>:
    <ul>
      <li>Use the Seaborn library for visualization.</li>
      <li>Plot the distributions of <code>SAT</code> and <code>ACT</code> scores.</li>
    </ul>
  </li>
  <li><strong>Calculating Mean and Standard Deviation</strong>:
    <ul>
      <li>Compute the mean and standard deviation for <code>SAT</code> and <code>ACT</code> scores.</li>
      <li>Determine the Z-score for the highest scorer in <code>SAT</code> and <code>ACT</code> among all applicants.</li>
    </ul>
  </li>
  <li><strong>Applying the Z-Score to All Scores</strong>: Standardize the entire table by applying the Z-score formula to all values.</li>
  <li><strong>Fit-Transform Using StandardScaler</strong>:
    <ul>
      <li>Import <code>StandardScaler</code> from <code>sklearn.preprocessing</code>.</li>
      <li>Initialize the scaler and apply it to the <code>SATscore</code> and <code>ACTscore</code> columns using <code>fit</code> and <code>transform</code> methods, or utilize <code>fit_transform</code> directly. </li>
      <li>Display the updated DataFrame to confirm standardization.</li>
    </ul>
  </li>
</ul>

<p>This project highlights the use of Z-score standardization and the application of Python libraries to prepare data for further analysis.</p>

</details>

---

### Project 4: Data Visualization with Python 
[Click to open the file...](https://github.com/shap0011/machine_learning_fall_2024/blob/main/Data_Visualization.ipynb)

The `Data_Visualization.ipynb` file explores data visualization techniques to gain insights, identify patterns, and draw conclusions using Python.

<details>
  <summary>Click to see details</summary>
  
<h4>Visualization Libraries in Python</h4>

<ul>
  <li><strong>Seaborn</strong> and <strong>Matplotlib</strong>
    <ul>
      <li>Install or import Seaborn (<code>import seaborn as sns</code>).</li>
      <li>Import Matplotlib (<code>import matplotlib.pyplot as plt</code>).</li>
      <li>Retrieve sample datasets from the Seaborn library.</li>
      <li>Load the <code>tips</code> dataset (<code>df = sns.load_dataset('tips')</code>).</li>
      <li>Perform data exploration:
        <ul>
          <li>Check variable types.</li>
          <li>Preview the top 5 rows.</li>
          <li>Return a summary of the DataFrame.</li>
        </ul>
      </li>  
    </ul>
  </li>
</ul>

<h4>Key Visualization Tasks</h4>

<ul>
  <li><strong>Relationship Between Total Bill and Tip Amount</strong>:
    <ul>
      <li>Use a scatter plot to visualize and analyze the relationship.</li>
      <li>Determine the type of correlation (positive, negative, or none).</li>
    </ul>
  </li>
</ul>

<ul>
  <li><strong>Strip Plot</strong>:
    <ul>
      <li>Visualize average tip amounts by day of the week and time of day:
        <ul>
          <li><code>tip</code> vs. <code>day</code></li>
          <li><code>tip</code> vs. <code>time</code></li>
        </ul>
      </li>
    </ul>
  </li>
</ul>

<ul>
  <li><strong>Bar Plot</strong>:
    <ul>
      <li>Display average tip amounts:
        <ul>
          <li>By day of the week.</li>
          <li>By party size.</li>
          <li>By smoker status.</li>
          <li>By gender.</li>
        </ul>
      </li>  
    </ul>
  </li>
</ul>

<ul>
  <li><strong>Pair Plot</strong>:
    <ul>
      <li>Plot pairwise relationships in the <code>tips</code> dataset.</li>
      <li>Use the <code>hue</code> parameter (e.g., by <code>sex</code>).</li>
    </ul>
  </li>
</ul>

<ul>
  <li><strong>Distribution Plot</strong>:
    <ul>
      <li>Use <code>displot()</code> to visualize a univariate variable distribution:
        <ul>
          <li>Plot a histogram with a kernel density estimate (KDE).</li>
          <li>Calculate and annotate the mean, median, and mode.</li>
        </ul>
      </li>  
    </ul>
  </li>
</ul>

<ul>
  <li><strong>Count Plot</strong>:
    <ul>
      <li>Visualize counts of observations in each category:
        <ul>
          <li>Create a count plot by day, with <code>time</code> as the hue.</li>
        </ul>
      </li>  
    </ul>
  </li>
</ul>

<ul>
  <li><strong>Heatmap</strong>:
    <ul>
      <li>Display correlations as a two-dimensional heatmap:
        <ul>
          <li>Each square represents the correlation between two variables.</li>
        </ul>
      </li>  
    </ul>
  </li>
</ul>

<ul>
  <li><strong>Scatter Plot</strong>:
    <ul>
      <li>Customize scatter plots for <code>total_bill</code> vs. <code>tip</code>:
        <ul>
          <li>Experiment with colors, opacity, and shapes of data points.</li>
        </ul>
      </li>  
    </ul>
  </li>
</ul>

<ul>
  <li><strong>Bar Plot</strong>:
    <ul>
      <li>Create vertical bar plots to display categorical data:
        <ul>
          <li>Plot smoker and non-smoker counts using Matplotlib.</li>
        </ul>
      </li>  
    </ul>
  </li>
</ul>

<ul>
  <li><strong>Pie Plot</strong>:
    <ul>
      <li>Visualize univariate data distribution:
        <ul>
          <li>Plot the occurrence of different days.</li>
        </ul>
      </li>  
    </ul>
  </li>
</ul>

<ul>
  <li><strong>Exploded Pie Plot</strong>:
    <ul>
      <li>Separate one or more sectors from the pie:
        <ul>
          <li>Plot the occurrence of days with an exploded view.</li>
        </ul>
      </li>  
    </ul>
  </li>
</ul>

<ul>
  <li><strong>Histogram</strong>:
    <ul>
      <li>Analyze the distribution and spread of continuous variables:
        <ul>
          <li>Plot a histogram for the <code>tip</code> variable.</li>
        </ul>
      </li>  
    </ul>
  </li>
</ul>

<ul>
  <li><strong>Box Plot</strong>:
    <ul>
      <li>Visualize the five-number summary:
        <ul>
          <li>Plot the boxplot of <code>total_bill</code> to check for outliers.</li>
        </ul>
      </li>  
    </ul>
  </li>
</ul> 

<ul>
  <li><strong>Subplots</strong>:
    <ul>
      <li>Create multiple plots within a single canvas:
        <ul>
          <li>Use <code>plt.subplot(numrows, numcols, plot_number)</code> to position plots.</li>
          <li>Add a strip plot to visualize <code>tip</code> vs. <code>day</code>.</li>
        </ul>
      </li>  
    </ul>
  </li>
</ul> 

<p>The project highlights the use of powerful visualization libraries like Matplotlib and Seaborn to explore, analyze, and interpret data through various graphical representations, enabling insights into patterns, relationships, and distributions within the dataset.</p>

</details>

---

### Project 5: Exploratory Data Analysis (EDA) 
[Click to open the file...](https://github.com/shap0011/machine_learning_fall_2024/blob/main/EDA_Solution.ipynb)

In the `EDA_Solution.ipynb` file, I explore and analyze a real estate transaction dataset to uncover insights, identify patterns, and prepare the data for building a predictive pricing model.

<details>
  <summary>Click to see details</summary>
  
<ul>
  <li><strong>Mounting Google Drive in Google Colab</strong>: Access files stored in Google Drive to enable seamless data loading.</li>
  <li><strong>Importing Libraries and Loading the Dataset</strong>: 
    <ul>
      <li>Import the necessary Python libraries:
        <ul>
          <li><strong>NumPy</strong> for numerical computing.</li>
          <li><strong>Pandas</strong> for data manipulation.</li>
          <li><strong>Matplotlib</strong> for visualization.</li>
          <li><strong>Seaborn</strong> for enhanced visualization.</li>
        </ul>
       </li> 
      <li>Load the <code>real_estate.csv</code> file into a DataFrame.</li>
    </ul>
  </li>
  <li><strong>Displaying Basic Dataset Information</strong>:
    <ul>
      <li>Print the dataset using <code>.head()</code> to view the first five rows.</li>
      <li>Display the last five rows of the dataset.</li>
      <li>Check the dataset's dimensions using the <code>.shape</code> attribute.</li>
    </ul>
  </li>
  <li><strong>Exploring Feature Data Types</strong>:
     <ul>
      <li>Print the column data types using <code>.dtypes</code>.</li>
    </ul> 
  </li>
  <li><strong>Plotting Feature Distributions</strong>:
    <ul>
      <li>Use <strong>Seaborn's Pairplot</strong> to display distributions of numeric features.</li>
      <li>Plot a histogram grid using the same method.</li>
    </ul>  
  </li>
  <li><strong>Displaying Formal Summary Statistics</strong>:
    <ul>
      <li>Summarize numerical features with the <code>.describe()</code> function.</li>
      <li>Summarize non-numerical features using <code>.describe(include='object')</code>. </li>
      <li>Observe missing values in the dataset.</li>
    </ul>  
  </li>
  <li><strong>Exploring Segmentations</strong>:
    <ul>
      <li>Use segmentation to observe the relationship between categorical and numeric features:
        <ul>
          <li>Plot a <strong>box plot</strong> of <code>sqft</code> by <code>property_type</code> using Seaborn.</li>
          <li>Plot a <strong>box plot</strong> of <code>price</code> by <code>property_type</code> using Seaborn.</li>
        </ul>
      </li>
    </ul>  
  </li>
  <li><strong>Analyzing Correlations</strong>:
    <ul>
      <li>Calculate correlations between numeric features using the <code>.corr(numeric_only=True)</code> function.</li>
    </ul>  
  </li>
  <li><strong>Visualizing Correlation Grids</strong>:
    <ul>
      <li>Plot a heatmap of annotated correlations using Seaborn.</li>
    </ul>  
  </li>
  <li><strong>Observing Minimum Lot Size</strong>:
    <ul>
      <li>Use <code>.loc</code> to filter <code>lot_size</code> for properties of type <code>Condo</code>.</li>
      <li>Use <code>.loc</code> to filter <code>lot_size</code> for properties of type <code>Bungalow</code>.</li>
    </ul>  
  </li>
</ul>

<p>This project creates a regression model to predict property transaction prices with a mean absolute error (MAE) of under $70,000, providing a data-driven alternative to traditional appraisal methods.</p>

</details>

---

### Project 6: Data Cleaning
[Click to open the file...](https://github.com/shap0011/machine_learning_fall_2024/blob/main/Data_Cleaning_Solution.ipynb)

In Data_Cleaning_Solution.ipynb, I focus on identifying and addressing issues in the dataset, such as handling missing values, detecting and removing outliers, and ensuring data consistency to prepare it for effective model building.

<details>
  <summary>Click to see details</summary>

<ul>
  <li><strong>Mounting Google Drive in Google Colab:</strong>
    <ul>
      <li>Access files stored in Google Drive to enable seamless data loading.</li>
    </ul>
  </li>
  <li><strong>Importing Libraries and Loading the Dataset:</strong>
    <ul>
      <li>Import the necessary Python libraries:
        <ul>
          <li><strong>NumPy</strong>: For numerical computing.</li>
          <li><strong>Pandas</strong>: For data manipulation.</li>
          <li><strong>Matplotlib</strong>: For visualization.</li>
          <li><strong>Seaborn</strong>: For enhanced visualization.</li>
        </ul>
      </li>
      <li>Load the <code>real__estate.csv</code> file into a DataFrame.</li>
    </ul>
  </li>
  <li><strong>Displaying Basic Dataset Information:</strong>
    <ul>
      <li>Use  <code>.head()</code>,  <code>.tail()</code>, and  <code>.sample()</code> to view subsets of the data.</li>
    </ul>
  </li>
  <li><strong>Displaying Formal Summary Statistics:</strong>
    <ul>
      <li>Summarize numerical features using the <code>.describe()</code> function.</li>
    </ul>
  </li>
  <li><strong>Handling Missing Data:</strong>
    <ul>
      <li>Display unique values for <code>basement</code> and <code>property_type</code>. </li>
      <li>Recognize that <strong>NaN</strong> values for <code>basement</code> indicate properties without a basement.</li>
      <li>Replace <code>NaN</code> values with <code>0</code> using the <code>.fillna()</code> function.</li>
      <li>Convert the <code>basement</code> column data type to integer.</li>
    </ul>
  </li>
  <li><strong>Removing Outliers:</strong>
    <ul>
      <li>Import the <code>warnings</code> module to suppress warnings during visualization.</li>
      <li>Create violin plots for <code>beds</code>, <code>sqft</code>, and <code>lot_size</code> to identify potential outliers.</li>
      <li>Sort the <code>lot_size</code> column and display the top 5 largest values.</li>
      <li>Examine rows with unusually large lot sizes.</li>
      <li>Remove observations where <code>lot_size</code> exceeds <strong>500,000 sqft</strong>, as they are deemed outliers.</li>
    </ul>  
  </li>
  <li><strong>Saving the Cleaned Dataset:</strong>
    <ul>
      <li>Save the cleaned DataFrame as <code>cleaned_df.csv</code>.</li>
      <li>Verify the saved file by reloading it with Pandas.</li>
    </ul>  
  </li>
</ul>

<p>This section highlights my ability to clean and preprocess data systematically, culminating in the creation of a cleaned dataset stored as `cleaned_df.csv`, which serves as the foundation for further analysis and model development.</p>

</details>

---

