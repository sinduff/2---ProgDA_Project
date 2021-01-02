## 2---ProgDA_Project

### Submitted by Sinéad Duffy, ID:10016151

***

#### Problem Statement
Select a dataset that simulates a real-world phenomenon. Create the dataset using synthesised data, and model using python.

#### Introdution
The purpose of this ReadMe file is to provide guidance on navigating the Jupyter Notebook for this module.  The notebook was completed to comply with the problem statement outlined above.  

The notebook is divided in to a number of different segments namely;

1. Introduction
2. Choosing a dataset
3. Exploring the variables
4. Synthesising the data
5. Detailing the research
6. Conclusion
7. Refrences

The refrences used throughout the notebook are outlined in section 7.  Throughout the notebook footnotes are used to indicate where the specific refrences are used.

The notebook also contains a number of examples, each of which are outlined in the following sections.

#### Section 1 - Introduction
The first cell in the notebook outlines an introduction to the notebook.  It outlines the approach of the author, a well as the chosen dataset.

The first cell containg code that the user sees is the one importing the python standard libaries.  The user must run this cell first **before** any of the following code cells are run to ensure that the subsequent cells will operater correctly.  Whilst completing the project, the author had to update the Pandas libary as well as the Seaborn libary.  Thi wa to ensure the correct running of code and display of the relevant plots.

As an example, the code used to update the Seaborn libary was 
**!pip install seaborn --upgrade**

Once Seaborn was updated, the new version was imported into the notebook, and confirmed as version 0.11.0 by using;
***import seaborn as sns
sns.__version__***

**%matplotlib inline** was included in the libary section to ensure that plots using matplotlib displayed correctly.

**sns.set_style("darkgrid")** set the style of the notebook to have dark grey plots behind each graph.

**rng = default_rng()** set a global variable called **rng** which can be used in later in the notebook when creating random numbers.

#### Section 2 - Choosing a dataset
This section outlines why the UCI dataset on wine was choosen.  How the dataset was cleaned of errors was also outlined.

*Code Cell 1* - outlines how the original dataset from UCI Machine Learing Repository is imported into the notebook.  It also prints a summary of the data within the file.

*Code Cell 2* - outlines how the import of cleaned data with headings was completed from the local drive.  the first 9 rows of the dataframe are displayed in the cell below.


#### Section 3 - Exploring the variables
Section 2 explores the variables that are contained in the UCI dataset.  An image of the properties is included.

*Code Cell 3* - prints out a summary of each variable in the 'cleaned' dataframe imported into the notebook.

Each variable is defined here, as is the range of each variable and type of number (integer / floating point number)

Correlation of data is also covered here.  

*Code Cell 4* - prints out the correlation of variables in the cleaned dataframe.  


#### Section 4 - Synthesising the data
This section outlines how the dataset is simulated using numpy, and it's random number generator. The author has chosen to document 6 variables instead of the original 13 within the dataset.

The following sections will complete a number of parts of the process including;

1. Creating the dataset
2 .Examining the data set in terms of its basic shape as well as describing key statistical features such as
     a. count
     b. mean
     c. standard deviation
     d. min and max values
3. Print each of the variables in turn 
4. Examine a correlation of the data to understand the relationships between variables.

**1 . Creating the dataset**
*Code Cell 5* - outlines how the data for the dataset was synthesised.  A seed was set to allow that the random data generated to be repeatable.

**2. Examing details of the dataset**
*Code Cell 6* - prints out details about the shape of the dataframe and returns the number of rows, and columns in the dataframe

*Code Cell 7* - describe function to show basic statistical details for the newly created dataframe df

**3. Examining and Plotting the Variables created**
*Code Cell 8* - Prints a pairplot grid of the 6 chosen variables against one other variable in grid.  

*Code Cell 9* - display the break down of each variety of wine and creates a plot using pandas 

*Code Cell 10* - Plot the variable 'Alcohol'

*Code Cell 11* - plotting the variable 'Ash' using seaborn

*Code Cell 12* - plotting the variable 'Magnesium'

*Code Cell 13* - plotting the variable 'Flavanoids'

*Cell Code 14* - plotting the variable 'Hue'

**4. Correlation and Matrices**
This section of the analysis looks at the correlation between the different variables, to understand if there is any relationship between  the.

*Cell Code 15* - Correlation map of abrevated dataset (See point 24 in refrence section)

#### Section 5 - Detailing the research

The research for each section has been outlined as the project unfurled.



#### Section 6 - Refrences

The refrences that the author used in each section are outlined here.  In all, 31 resources have been detailed.














