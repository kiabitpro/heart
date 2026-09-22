<div align="center">

<h1>❤️ Heart Dataset — Data Preprocessing & EDA</h1>

<p>
  <strong>Data Cleaning • Preprocessing • Exploratory Data Analysis</strong>
</p>

</div>

<hr>

<div style="
    background:linear-gradient(135deg,#fff1f2,#ffe4e6);
    border:1px solid #fecdd3;
    border-radius:20px;
    padding:25px;
    margin:25px 0;
">

<h2>📌 About This Project</h2>

<p>
This project focuses on <strong>data preparation, preprocessing, and Exploratory Data Analysis (EDA)</strong>
on a heart-related dataset.
</p>

<p>
The main purpose of this notebook is to inspect the dataset, prepare the data,
identify potential data quality issues, and perform EDA to better understand
the structure and characteristics of the dataset.
</p>

</div>


<div style="
    background:#f8fafc;
    border:1px solid #e2e8f0;
    border-radius:20px;
    padding:25px;
    margin:25px 0;
">

<h2>🎯 Project Goal</h2>

<p>
The main goal of this project is to <strong>prepare the dataset for analysis and Exploratory Data Analysis (EDA)</strong>.
</p>

<p>
Before performing any meaningful analysis, it is important to understand
the structure of the dataset and make sure that the data is loaded and
prepared correctly.
</p>

<p>
The workflow of this project includes:
</p>

<ul>
  <li>Inspecting the dataset file</li>
  <li>Detecting the file encoding</li>
  <li>Identifying the correct delimiter</li>
  <li>Loading the dataset</li>
  <li>Converting the dataset into a DataFrame</li>
  <li>Preprocessing the data</li>
  <li>Checking the quality and structure of the data</li>
  <li>Performing Exploratory Data Analysis</li>
</ul>

</div>


<div style="
    background:linear-gradient(135deg,#eff6ff,#dbeafe);
    border:1px solid #bfdbfe;
    border-radius:20px;
    padding:25px;
    margin:25px 0;
">

<h2>🛠️ Libraries Used</h2>

<p>
The following Python libraries were imported for data processing,
analysis, visualization, and dataset inspection:
</p>

<pre><code>import numpy as np
import pandas as pd
import matplotlib.pyplot as plt
import seaborn as sns
import missingno as msno
import chardet
import csv</code></pre>

<br>

<table>
<tr>
<th>Library</th>
<th>Purpose</th>
</tr>

<tr>
<td><strong>NumPy</strong></td>
<td>Numerical computations and array operations</td>
</tr>

<tr>
<td><strong>Pandas</strong></td>
<td>Data loading, manipulation, preprocessing, and analysis</td>
</tr>

<tr>
<td><strong>Matplotlib</strong></td>
<td>Data visualization and plotting</td>
</tr>

<tr>
<td><strong>Seaborn</strong></td>
<td>Statistical data visualization</td>
</tr>

<tr>
<td><strong>Missingno</strong></td>
<td>Visualization and analysis of missing values</td>
</tr>

<tr>
<td><strong>Chardet</strong></td>
<td>Detecting the encoding of the dataset file</td>
</tr>

<tr>
<td><strong>CSV</strong></td>
<td>Inspecting CSV file structure and delimiters</td>
</tr>

</table>

</div>


<div style="
    background:#f8fafc;
    border:1px solid #cbd5e1;
    border-radius:20px;
    padding:25px;
    margin:25px 0;
">

<h2>🔍 1. Dataset File Inspection</h2>

<p>
Before loading the dataset with Pandas, the structure of the source file
was inspected.
</p>

<p>
This step is important because an incorrect encoding or delimiter can cause
the dataset to be loaded incorrectly, resulting in improperly separated
columns or incorrectly interpreted values.
</p>

<h3>🔤 Encoding Detection</h3>

<p>
The file encoding was examined using the <strong>Chardet</strong> library
to identify the encoding used by the dataset.
</p>

<p>
Checking the encoding helps ensure that text data is interpreted correctly
when the file is loaded.
</p>

<h3>🔣 Delimiter Detection</h3>

<p>
The dataset was also inspected to determine the correct delimiter used to
separate values within the CSV file.
</p>

<p>
Identifying the correct delimiter ensures that the dataset is loaded with
the correct column structure.
</p>

</div>


<div style="
    background:linear-gradient(135deg,#f0fdf4,#dcfce7);
    border:1px solid #bbf7d0;
    border-radius:20px;
    padding:25px;
    margin:25px 0;
">

<h2>📂 2. Loading the Dataset</h2>

<p>
After identifying the appropriate encoding and delimiter, the dataset was
loaded using <strong>Pandas</strong> and converted into a
<strong>DataFrame</strong>.
</p>

<p>
The DataFrame serves as the main data structure used throughout the project.
All preprocessing, data inspection, and EDA steps are performed on this
DataFrame.
</p>

<p>
The purpose of this stage is to make sure that the dataset is imported
correctly and maintains its expected structure.
</p>

</div>


<div style="
    background:linear-gradient(135deg,#fff7ed,#ffedd5);
    border:1px solid #fed7aa;
    border-radius:20px;
    padding:25px;
    margin:25px 0;
">

<h2>🧹 3. Data Preprocessing</h2>

<p>
After loading the dataset into a DataFrame, the
<strong>Data Preprocessing</strong> stage was performed.
</p>

<p>
The purpose of preprocessing is to prepare the data for further analysis
and ensure that potential data quality issues do not negatively affect the
EDA process.
</p>

<p>
During this stage, the dataset structure and data quality were examined,
and the data was prepared for the Exploratory Data Analysis stage.
</p>

<p>
Data preprocessing is an essential part of a Data Science workflow because
the quality and reliability of the analysis depend heavily on the quality
of the input data.
</p>

</div>


<div style="
    background:linear-gradient(135deg,#fdf4ff,#fae8ff);
    border:1px solid #e9d5ff;
    border-radius:20px;
    padding:25px;
    margin:25px 0;
">

<h2>📊 4. Exploratory Data Analysis — EDA</h2>

<p>
After preparing the dataset, <strong>Exploratory Data Analysis (EDA)</strong>
was performed to gain a better understanding of the data.
</p>

<p>
EDA helps reveal the structure, distributions, relationships, and important
patterns within a dataset before moving to further analysis or machine
learning tasks.
</p>

<p>
Different statistical and visualization techniques were used to explore
the dataset and make the underlying information easier to understand.
</p>

</div>


<div style="
    background:#0f172a;
    color:#f8fafc;
    border-radius:20px;
    padding:30px;
    margin:30px 0;
">

<h2>🧠 Project Workflow</h2>

<p style="color:#cbd5e1;">
The overall workflow of this project can be summarized as follows:
</p>

<pre style="color:#e2e8f0;"><code>
Dataset File
     │
     ▼
Encoding Detection
     │
     ▼
Delimiter Detection
     │
     ▼
Load Dataset
     │
     ▼
Convert to DataFrame
     │
     ▼
Data Preprocessing
     │
     ▼
Data Quality Check
     │
     ▼
Exploratory Data Analysis
     │
     ▼
Ready for Further Analysis
</code></pre>

</div>


<div style="
    background:linear-gradient(135deg,#fff1f2,#ffe4e6);
    border:1px solid #fecdd3;
    border-radius:20px;
    padding:25px;
    margin:25px 0;
">

<h2>❤️ Final Objective</h2>

<p>
The final objective of this project is to create a clean and well-prepared
dataset that can be effectively used for <strong>heart data analysis and
further exploration</strong>.
</p>

<p>
This notebook mainly focuses on the essential early stages of a Data Science
workflow:
</p>

<p align="center">
<strong>Data Inspection → Preprocessing → EDA</strong>
</p>

<p>
The prepared dataset can then be used for deeper analysis or, if required,
for future Machine Learning tasks.
</p>

</div>


<div align="center">

<h2>🚀 Data Science Workflow</h2>

<p>
<strong>Inspect → Clean → Preprocess → Explore → Analyze</strong>
</p>

<br>

<p>
⭐If you found it useful, make sure to follow me and stay tuned for the next notebook! 🚀
</p>

</div>
