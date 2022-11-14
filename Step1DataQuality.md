---
title: Step1 - Data quality
nav: true
---


## Step 1 Data Quality

  Section 1: Using "tidy data" principles
 
  Section 2: Identify and code illigal or missing values

### Using "tidy data" principles
Are your datasets future-proof? 

As your research progresses, new possibilities for enquiry might be revealed, and you may want to use a new method to analyse your data. Depending on how you recorded and stored your data, it may take a lot of time-consuming work to reconfigure your datasets before you can process the new analysis. While all the necessary data may exist within your datasets, there may be no simple and reliable method for extracting it.

The principles of **tidy data** offer a way of recording your data, be it in spreadsheets or database tables, so that every element within those datasets can easily be accessed for new analysis and modelling. Even if a dataset needs to be reconfigured before being imported into the new software, it will be a simple process to produce the necessary file.

**The fundamental principles of tidy data are:**
- Each variable is a column.
- Each row is an observation.
- Each cell contains one value.

By arranging all the variables of an observation along a single row, all elements about that observation are contained within a clearly delineated record: the single row. With all variables recorded in columns, these observations of a patient, a survey respondent, an event, a biological sample etc, are reliably linked to their subject.

Tidy data provides both the stability and the flexibility to reliably process and export data to any system; including running processes and modelling which later become desirable or significant for your research.  

In a spreadsheet, this format must not vary; neither to accommodate additional data for an individual observation, nor to create an aesthetically pleasing layout e.g. merged cells. [***incorporate images from PowerPoint***]
![TidyData](https://github.com/LeanneLibGriff/nine-repro/blob/gh-pages/images/2022-11-Tidy_Data.jpg)

With the requirement for each cell to contain a value, it is important for each cell to contain only one. This will isolate and label the information about a variable, and simplify the process of accessing it when required. As an example, when recording the addresses of respondents, the use of a single cell or line for the entire address makes potentially useable data difficult to access. By dividing these details across several columns, the potential exists to model additional data based on location.

### Data cleaning and data wrangling 
To take datasets from outside sources or from inexact processes such as webscraping and prepare them for analysis along with your tidy data, you may need to:
- convert the format or structure of the data
- remove duplicate or irrelevant observations
- standardise the format of observations
- change naming conventions
- correct errors
- or preform many more adjustments to make a dataset suitable for your processes.

The terms "data cleaning" and "data wrangling" are often used interchangably but they can be defined separately as:
- Data wrangling: transforming and mapping a dataset
- Data cleaning: removing or correcting data 

While small datasets could be altered manually, large scale datasets will require specialised functions or software to process multiple values. Griffith Library provides a [guide to preparing data](https://www.griffith.edu.au/library/research-publishing/working-with-data/process-and-analyse), which offers an introduction to [OpenRefine](https://openrefine.org/), one of the major tools.


Suggestions
 

Intermediate is formulating the cells in a column to record the date in the YYY-MM-DD format.  

The advanced option could the conversion to csv and reopen in Excel to see if it survives. 

