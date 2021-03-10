# Creating accessible spreadsheets 

## Interim status 
This guidance is still under review. We are publishing it in an interim state to give people information on what they may need to implement and to collate feedback. When it is finalised it will be published on the Government Statistical Service webiste.  

## Contents 

* Document information
* Images
* Hyperlink text 
* Colour and formatting
* Tables
* Communicating uncertainty in spreadsheets
* Structure
* Cover sheet, notes and table of contents
* Worksheets with multiple tabs
* Accessibility checker
* Saving and publishing your spreadsheet


## Document information 

Make sure you add document information in. The accessibility regulations require the title field and information about document language to be complete ([success criterion 2.4.2 page titled](https://www.w3.org/TR/WCAG21/#page-titled) and [3.1.1 language of page](https://www.w3.org/TR/WCAG21/language-of-page)). It is best practice to also fill in the author and keyword fields, but optional with regards to accessibility regulations.

### Adding document information

Go to ‘File’, then ‘Info’ and fill in the following fields:
* Title

This should replicate the title on the cover sheet (more information on cover sheets can be found in the relevant section of this guidance). Do not use dashes or underscores here.

* Author

Generally this should be the organisation that published the document – avoid using names of individuals.

* Keywords or Tags

Put in a list of terms that someone might use to search for the document, separated by commas. This helps search engines find the document. They also help with finding your document internally.

### Setting the document language

Go to ‘File’ and then ‘Options’ and then ‘Language’. Make sure the document has the correct language(s) selected.

## Images

Avoid the use of any images or charts within a spreadsheet. This includes any departmental logos. 

If you can’t avoid it, make sure all logos, graphics, charts and any other images within the spreadsheet document have alternative text attached to them ([success criterion 1.1.1 non-text content](https://www.w3.org/TR/WCAG21/#non-text-content)) and place them on a separate worksheet to any tables. You also need to ensure charts are accessible – see our ‘[Making analytical publications accessible](https://gss.civilservice.gov.uk/policy-store/making-analytical-publications-accessible/)’ guidance for more information. 

### How to add alt text for charts and images 
1. Right click on the image or chart and select 'Format Picture/Chart Area'.
2. Go to the size and properties box and select ‘Alt text’.
3. Enter a title and description for your alt text in the boxes and select ‘OK’.

On newer versions of Excel you may just need to right click and select 'Edit Alt Text'. 

If an image is just decorative you should mark it as such by ticking the 'Decorative' checkbox (Excel 2013 doesn’t let you do this but later versions do).

## Hyperlink text

Embedding hyperlinks correctly is specifically mentioned in the accessibility guidelines. It comes under [success criterion 2.4.4 link purpose (in context)](https://www.w3.org/TR/WCAG21/#link-purpose-in-context) and [guideline 3.2 predictable](https://www.w3.org/TR/WCAG21/#predictable).

### Making hyperlinks accessible

1. Use specific descriptions 

Hyperlink text should be a specific description of the destination, not just ‘blog post’ or ‘report’ for example. The text should never be directional text like ‘click here’. Bear in mind that screen readers can be programmed to read out a list of links within a document. When link text is not specific, the links will be difficult to tell apart so the person cannot easily find a link they may be interested in.

2. Don't use URLs 

Do not use the [URL](https://techterms.com/definition/url) of a webpage as the hyperlink text, unless it is very short (e.g. www.unsplash.com). Long URLs get read out by a screen reader in full which can be very time consuming and annoying. Also, in most circumstances they do not describe the destination page.

3. Linking to documents 

If you are linking to another document the link text should contain the descriptive text, the type of document and its size, for example: ‘[Template to report breaches of the Code of Practice for Statistics (ODT, 23 KB)](https://gss.civilservice.gov.uk/wp-content/uploads/2020/10/Breach-reporting-template.odt)’.

4. Consistency in signposting  

Make sure that links to the same destination have consistent text and that links with different purposes and destinations have different link text. For example, it is bad practice to provide lots of links to different destinations with non-specific link text like ‘Find out more’.

5. Formatting link text

[Link text should be underlined by default](https://webaim.org/resources/linkcontrastchecker/?fcolor=0000FF&bcolor=FFFFFF). If it is not underlined the regulations say that you have to consider colour contrast with surrounding text and a 'visual cue' that appears on mouse hover and keyboard focus. Bear in mind that, while not a necessity in terms of the regulations, it is best practice for hyperlink text to be both underlined and have the correct amount of colour contrast with the background and the surrounding text. 

## Colour and formatting

Some of the Web Content Accessibility Guidelines (WCAG) 2.1 are generic in nature. The following pointers on colour and formatting have been split into things that must be done in order to meet the legal accessibility regulations at the AA level and things that are considered best practice. Please bear in mind that this is a guide based on our knowledge, research and interpretation and may be subject to change as we learn more.    

Pointers that must be followed: 

* All written content should follow the advice in the [‘Making written content accessible’ section](https://gss.civilservice.gov.uk/policy-store/making-analytical-publications-accessible/#section-4) of our ‘Making analytical publications accessible’ guidance.
* No visual devices such as colour, shading or patterns should be used to divide up data regions ([success criterion 1.4.1 Use of colour](https://www.w3.org/TR/WCAG21/#use-of-color) [success criterion 1.3.3 sensory characteristics](https://www.w3.org/TR/WCAG21/#sensory-characteristics).
* No text is set in a vertical or diagonal direction ([guideline 1. perceivable](https://www.w3.org/TR/WCAG21/#perceivable) and [guideline 4. distinguishable](https://www.w3.org/TR/WCAG21/#distinguishable)).
* No text has spaces between letters in a word for visual effect ([guideline 1. perceivable](https://www.w3.org/TR/WCAG21/#perceivable)) - screen readers will read letters instead of words if text is presented in this way. 
* Colour is never used as the only way to communicate a message ([success criterion 1.4.1 Use of colour](https://www.w3.org/TR/WCAG21/#use-of-color)).
* The minimum font size used is size 12 - in general this will help you meet [success criterion 1.4.4 resize text](https://www.w3.org/TR/WCAG21/#resize-text).

Pointers in terms of accessibility best practice:

* All fonts used are sans serif (for example, Arial or Calibri) - people with dyslexia find serif fonts hard to read. 
* Avoid the use of underline and italic text - people with dyslexia can find italic and underlined tex hard to read, if you need to highlight text it is best to use bold. 
* Avoid changing the colour of text to draw attention to it - if you do this you must check the colour contrast of the text against the background colour (more information on how to do this can be found in the 'checking text colour contrast' section). 
* Aim to use the 'default' or 'automatic' colour settings for all text - doing this will ensure the spreadsheet takes on the specialised colour settings users of assitive technology may have set up on their software.
* Avoid adding a background fill - some users will have settings that automatically change the colour of the background but this doesn't happen if you’ve put a fill colour in – even if it is white. 
* Avoid adding grid lines or cell borders - in general it it better to keep things simple.
* Avoid including images of charts in your spreadsheet, if you do you must carefully consider their accessibility, particularly the colour contrast between chart elements.
* Left align all text in cells outside the table and all row headings within the table 
* Right align all data within a table and all column headings
* Use commas after every three decimal places in numbers of four digits or more, and never spaces (except when writing years - these should have no punctuation).

### Checking text colour contrast  

If colour is used in cells with text, use the [WebAIM colour contrast checker](https://webaim.org/resources/contrastchecker/) to see if the colours meet the accessibility regulations. Remember, legally you need to meet the AA standard. 

Be aware that colours are coded in different ways. To use the WebAIM colour contrast checker you will need to know the hex code of the colours. Excel will give you the Red Green Blue (RGB) codes - you can use this [colour code converter](https://www.webfx.com/web-design/hex-to-rgb/) to get the hex codes.  

### Checking colour contrast in charts 

The use of colours in charts is more complex as you often have to consider colour contrast between different chart elements as well as with the background. Our [data visualisation guidance](https://gss.civilservice.gov.uk/policy-store/introduction-to-data-visualisation/#section-9) and the [style guide from the Office for National Statistics](https://style.ons.gov.uk/category/data-visualisation/using-colours/) both have useful tips on this area but neither have yet been fully updated with regards to the accessibility regulations. We are planning on looking into this in more detail soon. 

### Dates and time periods 
It is best practice to format dates and time periods as advised by the [Office for National Statistics style guide](https://style.ons.gov.uk/house-style/dates/) and [Government Digital Service guidance](https://www.gov.uk/guidance/style-guide/a-to-z-of-gov-uk-style). 

This means: 
* do not use dashes, use ‘to’, for example, don’t use ‘Jan – Mar 2020’ use ‘Jan to Mar 2020’
* it is fine to truncate days and months to save space
* do not truncate years – for example, write: ‘Jan 1931’ not ‘Jan 31’ 
* when referring to quarters of the year, write out the months, for example, “Jan to Mar 2020’ not ‘Q1 2020’
* if your data needs specific dates for example: 01/02/10 you can present them like this but be aware screen readers will read this as ‘01 slash 02 slash 10’ which can be annoying, so it is best practice to write ‘1 Feb 2010’

## Tables

### Merged and split cells
Restructure your tables so there are no split cells or merged cells. This can seem daunting, but it is one of the crucial issues to address as it is key for both machine readability and accessibility. 

Merged and split cells make tables hard to understand for users of assistive technology, removing them helps you to meet [success criterion 1.3.1 info and relationships](https://www.w3.org/TR/WCAG21/#info-and-relationships). 

### Nested tables
Do not nest tables within other tables, this kind of structure is difficult to understand for users of assistive technology, removing them helps you meet ([success criterion 1.3.1 info and relationships](https://www.w3.org/TR/WCAG21/#info-and-relationships)).

### Macros, formulas and application code
We advise you to avoid publishing spreadsheets with macros in. It is difficult to ensure these meet the accessibility regulations and, in general, they are bad for machine readability. 

It is also best practice to remove formulas and any application code contained in your spreadsheet. Formulas and code can cause confusion and they can pose a security risk. If you have to include formulas or code, ensure it is hard coded to avoid accidental errors in use.

### Blank rows and columns
Remove all blank rows and blank columns. Blank rows and columns within the tables themselves may be perceived as the edge of the data area rather than a divider. Removing them will help you meet [success criterion 1.3.1 info and relationships](https://www.w3.org/TR/WCAG21/#info-and-relationships) and [success criterion 1.3.3 sensory characteristics](https://www.w3.org/TR/WCAG21/#sensory-characteristics). If blank rows and columns are used to create space you can adjust column width and row height instead. 

### Mark up tables in spreadsheets
Ensure your table is ‘marked up’ as a table – this is key to meeting [success criterion 1.3.1 info and relationships](https://www.w3.org/TR/WCAG21/#info-and-relationships), [guideline 2.4 navigable](https://www.w3.org/TR/WCAG21/#navigable) and [success criterion 2.4.3 focus order](https://www.w3.org/TR/WCAG21/#focus-order).

Marking up a table:
* allows a header row and table edges to be identified by assistive technology 
* allows your table to be named and appear in the 'go to' tool which is a keyboard shortcut that aids navigation (you can test this out by pressing Ctrl + G when in your spreadsheet).
* means a user will be able to tab through the data in a sensible way – for example when a user tabs to the end of the row, the next tab will take them to the start of the row below	
Note: if you keep tabbing past the end of the last row it does lead to extra rows being added to the table. However, as the table is marked up correctly, users of assistive technology should know when they get to the end of a table, so this isn’t considered an issue.

#### How to manually mark up a table in Excel: 
Be aware these instructions may differ slightly for different versions of Excel. 

* Select the cells you want to include in the table.
* On the ‘Insert’ ribbon, select ‘Table’.
* In the ‘Create table’ dialog box, check the ‘My table has headers’ box
* Select ‘OK’.

Excel will, by default, give you a table with alternating blue colours. It will also make every column a filter. This is not accessible. 

#### Make the Excel default table accessible:
* Click somewhere in the table 
* Click the ‘Design’ ribbon.  
* Select a plain table format in the ‘table styles’ section – scroll right to the top and you’ll see the plainest option with no formatting (you can make this the default table format Excel chooses). 
* Uncheck the ‘Filter Button’ box in the 'Table Style Options' section. 
* Be aware, if you have row labels in the first column, the cell in the header row will automatically be labelled 'Column 1', it is best to replace this with something sensible. 

It is best practice to also:

* highlight column headings and row labels by setting the text to bold
* choose the 'default' or 'automatic' colour for all text (not black)
* left align all text in cells outside the table and all row labels within the table
* right align all data within a table and all column headings

##### Example of a table formatted in a plain way
 <example to be added>

#### Adding headers to a table that is already marked up

If the table is already created and you want to add a header row:
* Place the cursor anywhere in the table
* Click onto the ‘Design’ ribbon 
* Check the ‘Header Row’ box 

### Column headings
Excel will only let you tag one row as the header row.
Consistency is important when it comes to column headings. Clear and consistent headings help usability and machine readability.  
Follow a consistent naming convention - for example: ‘start_date_time’ and ‘end_date_time’ rather than mixing your naming conventions: ‘startdtTime’ and ‘end_date_time’.
If your spreadsheet uses multiple tabs, and the columns in these tabs hold similar or identical data, use the same column names. For example: in a spreadsheet listing employee satisfaction survey results, use ‘department_name’ in all tabs rather than ‘department_name’ in some and ‘name_of_department’ in others - this makes it easier to cross reference, manipulate and merge columns. 

Units
If needed, put the units for your data in rounded brackets after the column heading – for example: ‘Number of people in employment (thousands)’. Ensure it is clearly indicated if your columns use different units. 
It is best to space the information about units so it appears under the column header – you can do this by pressing Alt+Enter when typing in the cell. 
Displaying units in a consistent way is important for usability and machine readability. 

Wrap text 
Use the ‘wrap text’ function and adjust row height and column width to ensure all text you want to appear in cells within a table is visible and clearly spaced out - this is important because: 
•	users with dyslexia can find it difficult to read crowded text
•	a screen reader will repeatedly read out ‘overflowing’ or ‘cropped’ after every cell which contains text that does not fit.
It is OK for text outside a table to overflow the cell – a screen reader will still read out ‘overflowing’ or ‘cropped’ but as this won’t be repetitive it is not a problem. 
Symbols and footnotes 
It is best practise to put as much information as possible at the point of need – for example when data is provisional or revised put the whole word in rounded brackets instead of using ‘p’ or ‘r’.
When needed, using letters to signify notes is generally OK. However, using symbols should be avoided because: 
•	they can be confusing
•	screen readers may not recognise them 
•	users with low vision may not be able to spot them easily
If you need to use letters to signify notes you must provide a key and this key must be placed on the worksheet in a cell in column A, above the table. This ensures a user is made aware of the key before coming to the table – for example: 
 
 
Avoid using footnotes, if it is unavoidable:
•	write out the word ‘note’ in the cell, with the number of the note, and put it in square brackets 
•	put a list of numbers if a cell needs to refer to more than one note – for example, write ‘[note 1,2,3]’ if a cell needs to refer to notes 1, 2 and 3.  
•	If a note is in a column heading, space the text so the note marker sits underneath the column header and any information about units – for example: 
 
•	we advise square brackets for notes and rounded brackets for units to differentiate them in a consistent way
Other uses for symbols 
Symbols may be used in other ways. Be aware that some screen readers will skip over symbols completely. Consider how your text reads if you miss out the symbols, for example ‘Some shorthand is used in this spreadsheet, e = estimated, r = revised’ still makes sense if read out as ‘Some shorthand is used in this spreadsheet, e estimated, r revised’.  
Generally the percentage symbol ‘%’ is well understood by screen readers. We are looking to put together more comprehensive advice for symbols soon.  
Past advice on symbols and footnotes 
In terms of machine readability, the advice on symbols and notes has been to put symbols or footnote markers in separate (very narrow) columns, next to the data. It is OK to do this in terms of accessibility, but you would need to give that column a heading and mark up all the empty cells. This could make a table very wide which is not great for readability. 
Where to place the detailed notes
Do not place notes underneath a table where they can be easily missed, instead - create a worksheet called ‘Notes’ and put a table on this worksheet that lists all the notes for the spreadsheet.
Codes 
In some instances you may need to use codes in your tables. Make sure you are using the correct, nationally recognised classifications and geography codes. These codes are fine as they are normally strings of letters and numbers. If you have a column or row of codes make sure this row or column is labelled clearly. 
It is also best practice to link to any supporting information for any classifications or codes used, either as a note or on the cover sheet. It is important to help users to understand changes in classifications – for example, the Geography Code History Database helps users to track changes in area codes.
Use codes consistently where the codes are not just alpha-numeric values. Dashes and slashes can be used as an exception here as that is how the code is constructed. However, be aware that screen readers will read them out in full as “slash”.
Codes should be in separate cells to the description of the code and the data. For example, country code AD should be in a separate cell to the country name Andorra, and then another cell for the data linked to this.
Empty cells
Do not leave cells empty – empty cells can be confusing because they: 
•	make it difficult for users of assistive technology to work out where the table starts and ends 
•	do not tell a user why there is no data in the cell - a user might assume the data value is zero when this is not the case. 
Give users information about why cells are empty, but do not use symbols like a minus sign (-) or full stops (..). Instead it is best to mark them up descriptively, for example: 
•	if there is no data available, type in ‘no data’
•	if the data is missing, type in ‘missing’
•	if the data is a very small amount (for example a very small percentage change) and you don’t want to publish the exact figure, type in ‘low’ – if you are happy to publish the exact figure it is fine to show a low figure rounded to zero. 
Be aware that sometimes in statistics ‘NA’ can be used to mean Not Available, but many users will assume it means Not Applicable. If you use NA as shorthand you must clearly define what it means, above the table, in a key. 
Naming tables 
If you have a spreadsheet with lots of worksheets and many tables, you should make sure the tables have meaningful names. This will aid navigation for everyone, but particularly for those who use assistive technology. 
Name a table in Excel
•	Click anywhere in the table
•	Click the ‘Design’ ribbon 
•	In the properties section there is a box to edit the table name - to be useful this name must be meaningful and describe the table. 
•	Note that Excel doesn’t allow spaces or dashes in table names, words must be split up with underscores
Check navigation with named tables
If you want to see a list of all the tables in your worksheet go to the ‘Formulas’ ribbon and click ‘Name manager’. 
To test out navigation you can click ‘Ctrl + G’. This brings up a ‘Go to’ tool. You can then click onto one of your tables and select ‘OK’ to be taken directly to that table. 
Adding alt text to tables 
You can add alternative text to your table by right clicking anywhere in the table and selecting ‘Table’ and ‘Alternative text’. However, it is not necessary to do this to pass the accessibility regulations - as long as you have marked your tables up correctly.  
Be aware that despite this, newer versions of Excel have a built-in accessibility checker which will bring up tables without alt text as a fail. You don’t need to worry about this. 
If you save your spreadsheet in the ODS open format (which we advise you to do) alternative text for tables will disappear – but this does not matter as it is not needed to pass the accessibility regulations. 
Adding filters
Filters are not generally accessible as they can obscure data. 
If you do need to use filters it is important to provide signposts or comments to indicate which cells contain the drop-down menus and if any data is hidden. You should also give details of how to turn the filters off. For example: ‘Filters are active in cell C3 and may hide some data. To turn off all filters select the “Data” ribbon then “Filters” button or use [Ctrl, Shift, L]’. This information should be near cell A1, not underneath a table. The placing of information like this should be consistent across the tabs of your spreadsheet, e.g. always in cell A2.  
Adding freeze panes
Freeze panes can make it difficult for screen reader users to find the top left edge of a worksheet which is key to navigation.
If you leave freeze panes active it is best practice to inform users and give a instructions for how to turn them off. For example: ‘Freeze panes are turned on. To turn off freeze panes select the “View” ribbon then “Freeze panes” then “Unfreeze panes” or use [Alt W, F]’. 
As with filters, this information should be placed near cell A1 and this placing should be consistent across the tabs of your spreadsheet, e.g. always in cell A2.  
Be aware that if you save your spreadsheet in the ODS open format (which we advise you to do) freeze panes will disappear. 

Communicating uncertainty in spreadsheets
When designing a statistical spreadsheet, consider how to appropriately communicate any uncertainty to your users. Bear in mind that the user may not read detailed documents, or they may have copied the spreadsheet to use in another context.

Use notes or the cover sheet to: 
•	make it clear if there are any potential sources of bias or uncertainty – users need to know how this impacts on their use of the statistics.
•	highlight relevant information about comparability issues both across time and with equivalent statistics released elsewhere in the UK 
For more information on notes and cover sheets please see the ‘symbols and footnotes’ section and the ‘Metadata worksheets’ section.
Confidence intervals 
When communicating confidence intervals put the higher and lower bounds in separate cells next to the data. Make sure all columns have clearly labelled column headings. 
Example:
 
Statistical significance
Note that the credibility of assessing statistics using significance levels is currently under debate.
If you are communicating statistical significance show where a change is statistically significant in a separate cell to the data, ideally using words, for example: ‘Significant at 0.001 level’.
If it is not possible to use words to describe the statistical significance, you can use shorthand as long as you provide a key, above the table, in a cell in column A (see the section on symbols and footnotes for more information about presenting keys). 
In the past the asterisk symbol (*) has traditionally been used to communicate the level of statistical significance. Not all screen readers can understand the asterisk symbol and many users of assistive technology can find them difficult to see and understand. Therefore, if it is not possible to use words to describe the statistical significance it is better to use some form of shorthand using letters rather than the asterisk symbol. 


Structure

Properly structuring your content is important in order to meet the Success Criterion 1.3.1 Info and Relationships, level A.
Pointers for the spreadsheet as a whole
Provide supporting information 
Statistics should not be completely separated from supporting information. Context and caveats are vital to ensure users have enough information to interpret and make effective use of the data. You should signpost to supporting information if it cannot be easily included within the spreadsheet tabs. 
Cover sheet
Label your first worksheet ‘Cover_sheet’ and use it to provide information about what is in the spreadsheet (more information on this in the ‘Metadata worksheets’ section of this guidance).
Table of contents
If your spreadsheet has many worksheets, create a table of contents that describes the data within each worksheet (more information on this in the ‘Metadata worksheets’ section of this guidance).
Worksheet names
Ideally each worksheet should have a unique name that clearly describes the information found in that sheet. If this is not possible, give each sheet a number and use your table of contents to describe what is in each sheet number. 
To avoid any confusion for users of assistive technology remove extra spaces from the start or end of tab names. 
Keep worksheet tab names as consistent as you can between releases, as changing them limits usability. 
Blank worksheets
Remove any blank worksheets. Blank worksheets can be confusing as it is not clear if they are meant to be blank or if something is missing. 
Other things to avoid 
Headers and footers
Do not use headers and footers to convey important information. 
Floating elements
Do not use floating elements such as text boxes.
Floating toolbars
Deactivate any floating toolbars as screen reader software may not be able to access populated cells behind them - if you do need to leave a floating toolbar active then attach it to the other Excel toolbars at the top of the window.
Pointers for structure within worksheets: 
Information that should go in cells in column A
Column A is very important for users of assistive technology. For example, a screen reader will generally start each tab by reading out the information in cell A1. Similarly, keyboard-only users will also tend to navigate down from cell A1. 
The key thing to ensure is the information a user needs to understand the table is positioned above the table, in a place where users of assistive technology are most likely to see it.    
Cell A1 on each worksheet should tell a user what information is contained on that worksheet. Generally, if there is one table per worksheet, cell A1 contains the title of that table. 
Cell A2 should be used for description – for example: ‘This worksheet contains one table. Some cells refer to notes which can be found on the notes worksheet tab’.  
If relevant, information about frozen panes, filters and any symbols or shorthand used within the table should also be added into a cell in column A. 
If you have several worksheet tabs and they use different sources, a cell in column A should contain information about the source(s) for the table on that sheet. However, if each table in the spreadsheet uses the same source(s), the information about source(s) can go on the cover sheet. 
Positioning tables on worksheets 
Position tables against the left-hand edges of each sheet. Don’t leave a blank column as a gap. As mentioned users of assistive technology tend to navigate down from cell A1, if they hit blank cells it can be very hard to navigate to where the table is. 
Below the table
Don’t put any information below the table. You should put all key information above the table and any detailed notes should live in a table on a ‘Notes’ worksheet tab (more information in the ‘Notes’ section of this guidance). 
Titles of spreadsheets, worksheets and tables
Make sure you have a clear spreadsheet title including time period and geographical region.
Use standard and consistent title formats.
The title of a table should include: 
•	a description of the data,
•	the geography it applies to 
•	whether or not the data is seasonally adjusted
Example: ‘Number and percentage of people aged 16 to 64 in each labour market activity group, UK, seasonally adjusted’ 
It is best practice for a worksheet to only have one table. This means the title of the worksheet should be the title of the table. 
In large spreadsheets where worksheets are numbered instead of named you should include the table number in the title. For example: ‘Table 1: Number of people in different age groups, UK, seasonally adjusted’. 
Where to place and how to tag titles 
The worksheet title should always be in Cell A1 and should be marked up as Headings 1 using the ‘Cell Styles’ tool on the ‘Home’ ribbon. This helps users of assistive technology navigate around the spreadsheet. It is best to simplify the default colour and border settings for text tagged as a heading. Make the text bold, change the colour to black and remove all cell borders. 

Metadata worksheets

Cover sheet
If your data is simple and there is only one table in your spreadsheet, you might not need a cover sheet. However, they are generally useful in most circumstances.  
Use your cover sheet to provide key information about the data in the spreadsheet. But do not put too much information in it. If your cover sheet is starting to look more like a word document, you may need to create a webpage you can link to from the cover sheet instead.
Use subheadings to break up the information. These subheadings should be tagged using the cell styles tool. First level subheadings should be tagged as Headings 2, second level subheadings as Headings 3 and so on.  
Keep all the information in a list in column A and expand this column so the text doesn’t overflow the cells. 
Make sure all the written content follows the advice in the ‘Making written content accessible’ section of the ‘Making analytical publications accessible’ guidance.
Key things to include are: 
•	Information on what the data tables in this spreadsheet are about (a brief description should be in Cell A1 with a more detailed description below if necessary)
•	The statistical release the data relates to (if applicable) with a hyperlink to that release
•	the source for the data - if you have a complex spreadsheet with many different tables and sources you can put source information on each individual worksheet (above the table) or have it as a column in your table of contents.  
•	The date the spreadsheet was published 
•	The date the next update to the spreadsheet will be published (if applicable)
•	Where to find more information about the data (if applicable)
•	Where to find related data or supporting publications(if applicable)
•	Links to supporting metadata and methodology documents
•	Link to a glossary of essential technical terms and acronyms.
•	Contact details for the statisticians responsible for the data
•	Key information users need to know that relates to all (or nearly all) worksheets in the spreadsheet, for example information on weighting
Table of contents 
If you have many worksheets in your spreadsheet you should create a table of contents that describes the data within each worksheet. 
This can live within the cover sheet or on its own worksheet tab, but make sure it is marked up properly as a table and named ‘Table_of_contents’. If it is on its own tab make sure this is named ‘Table_of_contents’
This table of contents can also contain other information such as the source of the data (particularly if several different sources are used throughout the spreadsheet), the date the data in each worksheet was last updated and the date it will be next updated. 
Hyperlinking from the table of contents to cell A1 of each worksheet also aids navigation around a large spreadsheet.  
Notes worksheet 
If certain cells in your spreadsheet refer to notes, it is better for accessibility and machine readability to create a table of notes on its own ‘Notes’ tab than put information underneath each table. 
Remember this table of notes needs to be marked up and named appropriately. 
Worksheets with multiple tables 
When multiple tables do need to be placed on a single worksheet there are a few points to bear in mind.
Worksheet titles 
Pointers: 
•	The worksheet title should be in cell A1
•	The worksheet title should describe the data in the tables, for example ‘Number and percentage of population in each labour market activity group by age band, UK, seasonally adjusted’
•	The worksheet title should be marked up as a Headings 1 using the ‘Cell Styles’ tool on the ‘Home’ ribbon. 
Normally in large spreadsheets where worksheets are numbered instead of named, the title of each worksheet includes the table number, for example ‘Table 1: Number of people resident in each UK country’. When some worksheets have multiple tables, the worksheet titles cannot refer to specific tables. This means it is best to put the worksheet number in the title instead. 
For example: 
‘Worksheet 1: Number and percentage of population in each labour market activity group, UK, seasonally adjusted’
‘Worksheet 2: Number and percentage of population in each labour market activity group by age band, UK, seasonally adjusted’ 
etc. 
Table titles
Each table within the worksheet should have a unique title, for example ‘Table 2a: Number and percentage of people aged 16 and over in each labour market activity group’. 
It is best to have a clear numbering or labelling structure. For example linking the table numbers to the worksheet number, so all the tables on worksheet 2 are table 2a, table 2b, table 2c and so on. 
Each table’s title should be in the leftmost cell directly above the table.
Each table title should be marked up as a ‘Headings 2’ using the ‘Cell Styles’ tool on the ‘Home’ ribbon.
Structure 
•	Cell A2 should describe the number of tables on the sheet and how they are presented, for example ‘This worksheet contains eight tables presented next to each other horizontally with one blank column in between each table. Each table applies to a different age group.’
•	Each table should be marked up and named (more information on this in the tables section of this guidance) 
•	The first table should border the left hand edge of the worksheet
•	Tables should be separated by a single blank row or column - large gaps between tables could be misunderstood by screen reader users

Accessibility checker
Newer versions of Excel have a built-in accessibility checker. You can use this to see what issues it flags up. But be aware that it is a bit like using a spelling and grammar check. It can’t check everything and it is likely to miss some things. 
The checker will also flag up tables that don’t have alt text (as already mentioned). You do not necessarily need to add this in and bear in mind that it will be removed if you save your spreadsheet in an ODT format. 
To run the accessibility checker, go to the ‘Review’ ribbon and select ‘Check Accessibility’.

Saving and publishing your spreadsheet

Pointers: 
•	Generally a spreadsheet will automatically open on the first worksheet, but to ensure this always happens make sure the cursor is in cell A1 of the first worksheet when you save.
•	Zoom should be set to 100% when you save your spreadsheet to ensure no enlargement or reduction is active.
•	Avoid zip files as these can be blocked by organisational policies 
•	Consider using an Application Programming Interface (API) to aid further analysis.

File formats
Whenever possible you should publish your spreadsheet in an open format.
This is not explicitly mentioned in the accessibility regulations, but open formats make outputs more accessible because they do not rely on users having access to specific software.
Furthermore, in June 2012, the Government Open Data White Paper set out a vision for open data that outlined a ranking scheme from 1 to 5 stars. Government data releases should meet the 3 star measure as a minimum. This means make data available in an open, non-proprietary format.
Files published in Excel format (such as .xls and .xlsx) are not open because they rely on users having access to specific software.

The ODS format
For spreadsheets you intend users to read and analyse we advise you use the Open Document Spreadsheet (ODS) format. This is an open format very similar to Excel. 
When you save as an ODS file, Excel will bring up a box to warn you that some features of your spreadsheet may not be compatible with the ODS format. If you want to know more, Microsoft have published information about Excel features that are and aren’t compatible with the ODS format.  

CSV format
The other commonly used open format is Comma-Separated-Values (CSV). 
If you are publishing a CSV file that you intend users to open and read, it must meet the accessibility regulations. This can be a bit tricky as it only allows one tab and will strip out almost all formatting (such as table tags, headings tags, hyperlinks and cell outlines). 
If you are publishing a CSV file solely for machines to read it does not need to meet the accessibility regulations. CSV is the recommended format for machine-readable spreadsheets. 
Publishing alternative versions of same spreadsheet
If you need to, you can publish alternative versions of the same document. As long as one of them meets the accessibility regulations you are meeting the requirements of the accessibility legislation. 

For example, you may publish an accessible ODS version of your spreadsheet for users to open and read themselves, alongside a machine-readable CSV version. 

Software capability 
You should be aware that different spreadsheet tools and software have different capabilities for how they handle data. Check the specifications of your software, particularly around row and column limits, to make sure you are using an appropriate tool. 
For example, older versions of Excel (97-2003) have a row limit of 65,000 rows. You can read more about Excel specifications and limits if you need to. 
If the spreadsheet tool you use cannot hold all your data then you are likely to lose information, which can distort statistics and conclusions.
File names
File names should:
•	be unique, e.g. don’t call all your data downloads ‘Data download’
•	be descriptive and make sense out of context – for example, tell the user what is in a data download, don’t just call it ‘Data download 1’
•	be frontloaded
•	be short – aim for 60 characters including spaces
•	not include acronyms – put these in the document information as keywords or tags
•	be entirely in lowercase
•	use dashes instead of spaces or underscores between words – this makes file names easier to read, for example: ‘a file name.ods’ will end up as: ‘a%20file%20name.ods’ online, which is why it is better to call it  ‘a-file-name.ods’
•	not include a date, unless the date is part of the document title, for example, ‘Business-plan-for-2016-to-2017’
•	be sensible – do not include a version number, names or words like ‘draft’, ‘clean’ or ‘final’, unless those words are part of the document title (for example: ‘guidance-on-how-to-make-documents accessible’ is a more sensible file name than ‘access-guid-final-draft-Han-edit3’)
There isn’t a specific success criterion in the accessibility guidelines for file names but it comes under ensuring content is understandable by making it readable and predictable (guidelines 3.1 and 3.2).

## Basis for this guidance

This guidance is based on the following success criterions in the international [Web Content Accessibility Guidelines 2.1](https://www.w3.org/TR/WCAG21/):
* Success Criterion 1.1.1 Non-text Content, level A
* Success Criterion 1.3.1 Info and Relationships, level A
* Success Criterion 1.3.2 Meaningful Sequence, level A
* Success Criterion 1.3.4 Orientation, level AA
* Success Criterion 1.4.1 Use of Colour, level A
* Success Criterion 1.4.3 Contrast (Minimum), level AA
* Success Criterion 1.4.11 Non-text Contrast, level AA
* Success Criterion 2.1.1 Keyboard, level A
* Success Criterion 2.4.2 Page Titled, level A
* Success Criterion 2.4.3 Focus Order, level A
* Success Criterion 2.4.4 Link Purpose (In Context), level A
* Success Criterion 2.4.6 Headings and Labels, level AA
* Success Criterion 3.1.1 Language of Page, level A
* Success Criterion 3.2.3 Consistent Navigation, level AA
* Success Criterion 3.2.4 Consistent Identification, level AA

## Sources for this guidance

* Royal National Institute for the Blind spreadsheet guidance (Word document)
* Microsoft guidance
* Microsoft video guidance
* SiteImprove guidance
* Guidance from Michigan State University
* Welsh Government guidance
* Information on making tables accessible from Government Digital Service
* Making analytical publications accessible (Government Statistical Service guidance)
* Guidance shared with me by the Northern Irelands Statistics and Research Agency (Nisra).
* Feedback from the Digital Accessibility Centre (DAC) 




