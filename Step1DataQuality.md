---
title: Step1 - Data quality
nav: true
---


## Step 1 Data Quality

  Section 1: Using "tidy data" principles
 
  Section 2: Identify and code illigal or missing values

### Using "tidy data" principles
In the future, you might want to analyse your data in a way that you didn’t plan for originally. Depending on how you recorded and stored your data, the amount of work required to reconfigure your datasets so that new analyses can be modelled may be excessively time-consuming. While all the necessary data may exist within your datasets, there is no straightforward way of extracting it.

The principles of **tidy data** offer a way of recording your data, be it in spreadsheet or database tables, so that which every element within the dataset can easily be accessed for new analysing and modelling. Even if a dataset needs to be reconfigured to before being imported into the new software, it is a simple process to produce the necessary file from tidy data. 

**The fundamental principles of tidy data are:**
- Each variable is a column.
- Each row is an observation.
- Each cell contains one value.

These principles are not an arbitrary approach to structuring data. By arranging all the variables of an observation along a single row, all elements about an observation are contained within a single, clearly delineated record: its own row. With all variables recorded in columns, these observations of a patient, a survey respondent, an event, or a biological sample etc, are reliably linked to their subject. 

Tidy data provides both the stability and the flexibility to reliably process and export data to any system, including running processes and modelling which later become useful or significant to your research.  

In a spreadsheet, this format cannot vary for putting in additional data for one observation or for aesthetically pleasing layout so there can be no merged cells. [***incorporate images from PowerPoint***]

With the requirement for each cell to contain one value, it is important for each cell to contain only one. This will isolate and label the information about a variable and simplify the process of accessing it when required. As an example, when recording the addresses of a respondent for future correspondence, the choice of a single cell for the entire address makes potential useable data difficult to access. By dividing these details across several variables, the potential exists to model additional data based on location.

A way of organising the data that you are normally collecting but doing in a way that helps importing into different systems for analysis and visualisation. Together, these approaches will give you the option to shift focus or introduce new elements to your analysis without major conversion. As you need to record data, best to future-proof it. 

**Don't look beyond here**

***Hey, I said don't look***


This can largely be done through validating data and input via forms in the case of spreadsheets.
special characters or encoding issues 
inconsistent name case & format 
date format variations 
whitespace around values  
typographical errors, misspellings 
incomplete answers 
conflicting conventions for data values

Data cleaning and data wrangling
While it is possible to avoid the worst of these two processes if you’re careful with your own data, you may have to fix both the accuracy of the data and the way that it is structured before you are able to import into any of your systems. 

You want to this because data cleaning and data wrangling can be very time consuming. Folk have said that researchers spend most of their time fixing.

Unfortunately, if you have untidy data from some other source or another time, you will need to do both some data cleaning and data wrangling. 

You may have to export data in a different format for different systems, and tidy data makes it possible.

This can be done on spreadsheets through creating forms. Also validating the input. 

In the case of having to do it respectively with your own data from before, or using data from a repository which doesn’t conform, or doing some process that outputs the results in a different format, there are ways that you can make the data tidy. Public data

https://www.tableau.com/learn/articles/what-is-data-cleaning

Data wrangling

There are ways that existing data can be cleaned up. Sometimes called data wrangling.

Even if you do everything to produce tidy data, you may find that you are drawing upon untidy data produced by someone else or from problematic processes such as web scraping.

There are operational reasons for ensuring that your data are laid out in a consistent way. There is often a need to translate values etc to use in different systems.

Considering that spreadsheets are the most common way to collate data but there are also databases. 

Maybe there is a value that does not register very often. If it is not given its own column, there is nothing that can be done with that information - even the information that it is a negative value for most data points. 
