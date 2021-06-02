# Making spreadsheets accessible: a brief checklist of the basics 
For more information on any of these pointers see our ['Releasing statistics in spreadsheets' guidance](https://github.com/best-practice-and-impact/spreadsheet-accessibility/blob/main/interim-draft.md).

## Contents 

* [Tables](#Tables)
* [Footnotes](#Footnotes)
* [Formatting](#Formatting)
* [Structure](#Structure)
* [Before publishing](#Before-publishing)

## Tables
### 1.	Mark-up tables
Tables in spreadsheets need to be marked-up as tables. 
### 2.	Give tables meaningful names 
When tables in a spreadsheet document are marked-up they should also be given a meaningful name. 
### 3.	Remove merged cells, split cells and nested tables
Merged cells, split cells and nested tables make table structure hard to understand for assistive technology like screen reader software. 
### 4.	Remove blank rows and columns within tables 
Use row height and column width to create space instead. 
### 5.	All tables should have one tagged header row
When you mark-up a table you need to select ‘My table has headers’. 
Be aware all columns must have text in the header row (or Excel will give it a default name when you mark it up as a table). Also, header names must be unique – a table can’t have two columns with the same text in the header row. 
### 6.	Wrap text within cells 
It is important to ensure all text is visible and clearly spaced out. 
### 7.	Avoid adding filters and freeze panes
If you do need to use filters or freeze panes you should inform users and give instructions on how to turn them off. 
### 8.	Only leave cells with no data empty in certain circumstances
When cells with no data are left empty it can make it difficult for users of assistive technology to work out where the table starts and ends. 
If the following points are met, blank cells should not cause accessibility issues:
* There is only one reason a cell in a table may be left blank.
* The table is marked-up correctly.
* There is a note above the table, in a cell in column A, explaining that some cells are left blank and why.
If there are several reasons a cell in a table may be left blank you will need to describe why a cell has no data. 
### 9.	Avoid hiding rows or columns 
If you do need to hide some information you will need to give guidance in a cell in column A, above any tables, on what rows or columns are hidden and how to unhide them.

<br>  


## Footnotes
### 1.	Do not use symbols or superscript to signpost to notes 
You should not use superscript text or symbols to signify notes.
Instead, whenever possible put information at the point of need or use a letter as shorthand, for example: [unavailable] or [x]. 
All shorthand or words within a table should be presented in square brackets.
The type of shorthand used should follow our updated ‘Using symbols and shorthand in tables’ guidance. 
### 2.	Use the word ‘note’ when referring to footnotes
We advise you signpost to detailed footnotes using the word ‘note’ and a number in square brackets, for example: ‘[note 1]’. 
If a cell refers to more than one footnote you should list each in a separate pair of brackets, for example: ‘[note 1][note 2][note 3]’. 
### 3.	Avoid putting note markers in specific cells
Whenever possible, put note markers in titles, column headings or row labels. 
If you need to mention notes for specific data points, you should add a notes column to the table, on the right. You should describe which cell or cells the note applies to, for example: '[note 1] This note applies to B10, C10 and D10'.
### 4.	Put note text in a notes table on a notes worksheet
We advise you to create a worksheet called 'Notes'. This worksheet should contain a table that lists all the detailed notes for the spreadsheet. 

<br>  


## Formatting
### 1.	All written content needs to meet the accessibility guidelines 
Follow the advice in the 'Making written content accessible' section of our 'Making analytical publications accessible' guidance.
### 2.	Format text to make it accessible 
Pointers: 
* Use a sans serif font - serif fonts are more difficult to read, especially for people with dyslexia.
* Make text at least size 10 (although for titles we would suggest going for at least a size 12).
* Select the ‘automatic’ colour (unless you have used colour for emphasis). 
* Avoid the use of italic text – this can be difficult for some users to read.
* Avoid the use of cell borders on cells with lots of text in - underlined text is more difficult to read, particularly for people with low vision or dyslexia. 
* Avoid highlighting text with a background fill – if you do you will need to check the contrast between the font and the background. 
* Make sure all text is horizontal. 
### 3.	All worksheets should have descriptive titles which are properly tagged and formatted 
Each worksheet should have a descriptive title in Cell A1 which should be marked-up as ‘Headings 1’ using the 'Cell Styles' tool on the 'Home' ribbon. This helps assistive technology navigate around the spreadsheet.
Unfortunately, this will give the text default formatting. You need to edit it, see ‘Format text to make it accessible’. You can do this manually or by changing the default settings. 
If a worksheet has subheadings these must also be tagged and formatted correctly. First level subheadings should be tagged as ’Headings 2’, second level ones as ‘Headings 3’ and so on.  
### 4.	Avoid using symbols
Research by a company called Deque has listed 17 characters considered 'safe' to use. These include £, %, & and /. 
It is also OK to use dashes and slashes in classifications and geography codes as these are needed for consistency.
### 5.	Do not use headers and footers, floating text boxes or floating toolbars
These can fail a number of accessibility guidelines. 
### 6.	Do not use visual devices to divide data regions
No visual devices such as colour, shading or patterns should be used to divide up tables.
### 7.	Do not use a background fill 
It is better to leave the background of your spreadsheet blank. 
You can turn off Excel’s automatic grey gridlines on the ‘View’ ribbon if you wish. 
### 8.	Do not use colour as the only way to convey a message
Never use colour as the only way to communicate a message.
### 9.	When using colour for emphasis check the contrast 
Colour may be used for emphasis but you must check the colour contrast between the text and the background is strong enough to meet the accessibility guidelines. Use the WebAIM colour contrast checker to do this. Remember, legally you need to meet the AA standard.
### 10.	Avoid images in spreadsheets
Images should be avoided as they can disrupt navigation. If you cannot avoid including images, make sure all logos, graphics, charts and any other images within the spreadsheet document have alternative text attached to them.
### 11.	Remove macros
It is difficult to ensure these meet the accessibility regulations. They can also pose a security risk. 

<br>  

## Structure
### 1.	Give worksheets unique names or numbers
Each worksheet should have a unique tab name that clearly describes the information found in that sheet. If this is not possible, give each tab a number and use a (correctly marked-up) table of contents to describe what is on each worksheet.
### 2.	Remove blank worksheets
Blank worksheets can be confusing as it is not clear if they are meant to be blank or if something is missing. 
### 3.	Use cells in column A wisely 
The key thing to ensure is that the information a user needs to understand the table is positioned above the table, in a place where users are most likely to read it.
Cell A1 on each worksheet should tell a user what information is contained on that worksheet. Generally, it contains the title of the table on the worksheet. If the table title is very long it is better to break it up and put some of it in cell A2 and A3. 
The cell in column A, underneath the title, should be used for description – for example: 'This worksheet contains one table. Some cells refer to notes which can be found on the notes worksheet'.
Information about frozen panes, filters and any symbols or shorthand used within the table should also be presented in a cell in column A.
### 4.	Position tables against the left-hand edges of each sheet
Do not leave a blank column as a gap. 
### 5.	Avoid putting content below a table 
It is best practice to avoid putting any information below a table. 
### 6.	Avoid worksheets with multiple tables 
If you do need to have multiple tables please read the [Worksheets with multiple tables](#Worksheets-with-multiple-tables) section of the guidance. 

<br>  

## Before publishing 
### 1.	Run a spelling a grammar check 
Make sure there are no spelling or grammatical mistakes. You can run a spelling and grammar check in Excel – in newer versions it is on the 'Review' ribbon.
### 2.	Use the accessibility checker 
Newer versions of Excel have a built-in accessibility checker which will flag up any issues. Don’t rely on it completely as it is likely to miss some things and it may bring up things that are not relevant. Treat it like a spelling and grammar check. 
### 3.	Add document information 
The accessibility guidelines require the title field and information about document language to be complete.

