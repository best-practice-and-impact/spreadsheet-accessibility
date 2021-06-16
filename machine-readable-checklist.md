
# Making machine readable spreadsheets – a checklist 

## Best to supply through an API
When providing data for machines to read, providing a well-designed data Application Programming Interface (API) to supply the data is the best thing you can do. However, if this is not possible and you need to provide it via a file format, this checklist should help you.

## More information 
For more information on any of these pointers see our ['Releasing statistics in spreadsheets' guidance](https://github.com/best-practice-and-impact/spreadsheet-accessibility/blob/main/interim-draft.md).

## Checklist

### 1.	No merged cells
Some programming languages don’t understand merged cells. It makes it ambiguous where that data belongs in the table. 

### 2.	One header row 
This makes your tables easier to work with when using programming languages. Some languages can’t interpret more than one header row.  

### 3.	Clear and consistent column headings 
Clear and consistent headings help accessibility, usability and machine readability.

If your spreadsheet uses multiple worksheets and the columns in these worksheets hold similar or identical data, use the same column names. For example: in a spreadsheet listing employee satisfaction survey results, use ‘department name’ in all tabs rather than ‘department name’ in some and ‘name of department’ in others. 

This is also important across different releases as well, so for example if you are updating a spreadsheet every month, keep the column headings the same. 

It is also good practice to keep a change log which records all the changes you have made to your outputs. This can go in your metadata file or in background quality report. 

### 4.	Consistent formatting
Consistency in formatting helps programmers write programs using your spreadsheets. 
When talking about units and note markers, if you put units in rounded brackets and note markers in square brackets in one place on a spreadsheet, do this throughout the spreadsheet and throughout all spreadsheets in your portfolio. 
For example: Number of people employed (thousands) [note 1]

### 5.	Consistency of data type and format within columns 
If a column has numbers in it, make sure it only has numbers. If it has dates, only dates. Don’t mix the type of data in a column. Also, ensure that values follow a consistent format within columns, for example a consistent date format.

This also applies when talking about hierarchies and categories. Use separate columns for separate levels of hierarchy or category.

#### Example

Don’t do this:  
| Date         | Data | Area           |
|--------------|------|----------------|
| 01/01/1900   | 85   | United Kingdom |
| 02/01/1900   | 72   | England        |
| 3rd Jan 1900 | 83   | Aberdeenshire  |

Instead you should do this: 
| Date       | Data | Country        | Nation   | County        |
|------------|------|----------------|----------|---------------|
| 01/01/1900 | 85   | United Kingdom |          |               |
| 02/01/1900 | 72   | United Kingdom | England  |               |
| 03/01/1900 | 83   | United Kingdom | Scotland | Aberdeenshire |


### 6.	Don’t use the indentation tool
Excel has an indentation tool that sometimes gets used to indicate subsections or hierarchies. This is not good for machine readability. For example, don’t use the indent tool to indent a list of regions under a row for ‘England’. 

### 7.	Leave cells with no data blank
When a cell has no data, it is best practice for machine readability to leave that cell blank and provide information about why it is blank in the accompanying metadata file. 

### 8.	Don’t use colour or other formatting as the only way to communicate a message 
It is not obvious when colour or other formatting has been used so it is difficult for programmers to write it into a program. 

### 9.	Notes should be in a metadata file 
If you are optimising a spreadsheet for machine readability the best thing to do is not use any note markers, shorthand or text in the data cells of your tables. Instead you should put notes in the metadata file accompanying your spreadsheet and specify which notes apply to which cells. 

### 10.	Remove ‘hidden’ spaces at the start or end of cells with text in

### 11.	Check there are no spaces at the start or end of worksheet names

### 12.	Keep worksheet names as consistent as you can between releases

### 13.	Use the right codes 
If your data has codes make sure you are using the correct codes, for example the correct geography codes. Also make sure they are formatted correctly with no extra spaces at the start or end or spaces where there shouldn’t be spaces.

### 14.	Put codes in separate cells 
For example if using country code AD, this should be in a separate cell to the country name Andorra, and then there should be another cell for the data linked to this country.

| Country name | Country code | Data |
|--------------|--------------|------|
| Andorra      | AD           | 120  |

### 15.	Use symbols if you need to but explain what they mean in the metadata
If you are making a spreadsheet solely for machines to read you can use shorthand and symbols but you must provide information on what those symbols mean via an accopampanying metadata file. 

These symbols and shorthand should not be in a column with data. You can use them in text cells like the title, column heading or row label (unless the labels are numeric).

For example a column that reads  '7, 7, 6, x' is not good practice. This goes back to the point 5 about mixing data types. 

### 16.	Be consistent when naming spreadsheets, worksheets and titles of tables 
If names keep changing, programs will keep needing to be updated which makes things difficult. If you have to change something then make sure you warn users in advance and publish a change log so users understand what has changed and when. 

### 17.	Each worksheet should only have one table
Multiple tables on a worksheet cause problems for programmers as it is difficult to code where one table ends and another one begins. 

### 18.	Do not use macros
Macros change spreadsheets and their behaviour is difficult to predict for programmers. 

### 19.	Publish your data in CSV format 
The CSV format is easy for machines to read. However, it only allows one worksheet per file. If you are supplying many worksheets you can provide them in a zip file. This zip file should contain one CSV file per table and a metadata JSON file.   

## Do you need more? 
We are looking at providing more guidance around how to release data in way that is optimised for machine readability. Please let us know if this is something you need vy emailing [gsshelp@statistics.gov.uk](mailto:gsshelp@statistics.gov.uk). 

