 <h1>Data Analysis using SQL and Python</h1>
    <p>This repository contains a Jupyter notebook that demonstrates data analysis techniques using both SQL and Python. The notebook covers various steps from loading the dataset to cleaning data, deriving new columns, and loading the cleaned data into a SQL server.</p>
    <h2>Dataset</h2>
    <p>The dataset used in this project is assumed to be available in a CSV file named <code>orders.csv</code>. Please ensure you have this file in your working directory.</p>
    
  <h2>Prerequisites</h2>
    <p>Make sure you have the following libraries installed:</p>
    <ul>
        <li>numpy</li>
        <li>pandas</li>
        <li>seaborn</li>
        <li>matplotlib</li>
        <li>sqlalchemy</li>
        <li>pymysql</li>
    </ul>
    <p>You can install these libraries using pip:</p>
    <pre><code>pip install numpy pandas seaborn matplotlib sqlalchemy pymysql</code></pre>
    
  <h2>Project Structure</h2>
    <ul>
        <li><code>Data_Analysis_using_sql_and_python.ipynb</code>: The main Jupyter notebook containing the code for data analysis and SQL integration.</li>
    </ul>
    
  <h2>Steps Covered</h2>
    <ol>
        <li><strong>Loading the Dataset</strong>
            <ul>
                <li>Importing necessary libraries</li>
                <li>Loading the dataset using <code>pandas</code> with custom NA values</li>
            </ul>
        </li>
        <li><strong>Initial Data Exploration</strong>
            <ul>
                <li>Displaying the first few rows of the dataset</li>
                <li>Checking the dataset's info and summarizing missing values</li>
                <li>Identifying unique values in specific columns</li>
            </ul>
        </li>
        <li><strong>Data Cleaning and Transformation</strong>
            <ul>
                <li>Renaming columns to lowercase and replacing spaces with underscores</li>
                <li>Deriving new columns for discount, sale price, and profit</li>
                <li>Converting date columns to datetime format</li>
                <li>Dropping unnecessary columns</li>
            </ul>
        </li>
        <li><strong>Loading Data into SQL Server</strong>
            <ul>
                <li>Establishing a connection to the SQL server using <code>sqlalchemy</code></li>
                <li>Loading the cleaned data into the SQL server</li>
            </ul>
        </li>
    </ol>
    
   <h2>Usage</h2>
    <ol>
        <li>Clone this repository:
            <pre><code>git clone https://github.com/saloni0212/data-analysis-using-sql-and-python.git</code></pre>
        </li>
        <li>Navigate to the project directory:
            <pre><code>cd data-analysis-using-sql-and-python</code></pre>
        </li>
        <li>Open the Jupyter notebook:
            <pre><code>jupyter notebook Data_Analysis_using_sql_and_python.ipynb</code></pre>
        </li>
        <li>Run the cells in the notebook to see the data analysis and SQL integration steps in action.</li>
    </ol>
    
   <h2>Contributing</h2>
    <p>Contributions are welcome! Please fork the repository and create a pull request with your changes.</p>
    
