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

The principles of **tidy** data offer a way of recording your data, be it in spreadsheets or database tables, so that every element within those datasets can easily be accessed for new analysis and modelling. Even if a dataset needs to be reconfigured before being imported into the new software, it will be a simple process to produce the necessary file.

**The fundamental principles of tidy data are:**
- Each variable is a column.
- Each row is an observation.
- Each cell contains one value.

By arranging all the variables of an observation along a single row, all elements about that observation are contained within a single, clearly delineated record: the single row. With all variables recorded in columns, these observations of a patient, a survey respondent, an event, a biological sample etc, are reliably linked to their subject.

Tidy data provides both the stability and the flexibility to reliably process and export data to any system; including running processes and modelling which later become useful or significant to your research.  

In a spreadsheet, this format must not vary to accommodate additional data for an individual observation, or for creating an aesthetically pleasing layout e.g. merged cells. [***incorporate images from PowerPoint***]

With the requirement for each cell to contain one value, it is important for each cell to contain only one. This will isolate and label the information about a variable and simplify the process of accessing it when required. As an example, when recording the addresses of a respondent for future correspondence, the choice of a single cell for the entire address makes potential useable data difficult to access. By dividing these details across several variables, the potential exists to model additional data based on location.

A way of organising the data that you are normally collecting but doing in a way that helps importing into different systems for analysis and visualisation. Together, these approaches will give you the option to shift focus or introduce new elements to your analysis without major conversion. As you need to record data, best to future-proof it. 

**Don't look beyond here**

As part of the tidy data approach, each cell must contain a value and, in some cases, data validation, mandatory fields, and formatted cells can ensure data is stored correctly, avoiding inconsistent formats, typographical errors, and incomplete data.
Data cleaning and data wrangling 
While it is possible to avoid the worst of these two processes if you’re careful with your own data, you may have to fix both the accuracy of the data and the way that it is structured before you are able to import into any of your systems.
Even if you do everything to produce tidy data, you may find that you are drawing upon untidy data produced by someone else or from problematic processes such as web scraping.
Unfortunately, if you have untidy data from some other source or another time, you will need to do both some data cleaning and data wrangling.
In the case of having to do it respectively with your own data from before, or using data from a repository which doesn’t conform, or doing some process that outputs the results in a different format, there are ways that you can make the data tidy. Public data
https://www.tableau.com/learn/articles/what-is-data-cleaning
There are ways that existing data can be cleaned up. Sometimes called data wrangling.
