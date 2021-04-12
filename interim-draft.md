# Releasing statistics in spreadsheets (draft version of update)

This guidance aims to help you improve the usability, accessibility and machine readability of any statistics you publish in spreadsheet format. 

## Draft status 
This guidance is an update to the ['Releasing statistics in spreadsheets' guidance](https://gss.civilservice.gov.uk/policy-store/releasing-statistics-in-spreadsheets/) on the [Government Statistical Service (GSS) website](https://gss.civilservice.gov.uk/). It is still under review. We are publishing it in a draft state to give people information on what they need to implement and to collate feedback. We continue to carry out research and testing. Once this information is finalised, the guidance will be updated on the GSS website.  

If you have any questions or feedback, please email [gsshelp@statistics.gov.uk](mailto:gsshelp@statistics.gov.uk).  

## Accessibility, usability and machine readability 

### Accessibility 
Spreadsheets published online are covered by the [Web Content Accessibility Guidelines (WCAG) 2.1](https://www.w3.org/TR/WCAG21/). Spreadsheets published online by the public sector must meet the AA level of the WCAG 2.1 by law ([The Public Sector Bodies (Websites and Mobile Applications) Accessibility Regulations 2018](https://www.legislation.gov.uk/uksi/2018/852/contents/made)). 

Some of the Web Content Accessibility Guidelines (WCAG) 2.1 are generic in nature. Throughout this guidance, using our knowledge, research and interpretation of WCAG 2.1, we have tried to make a clear distinction between things we feel must be done in order to meet the legal accessibility regulations and things that are considered accessibility best practice.

### Usability 
Some of our advice is based on best practice for improving the usability of spreadsheets. This often overlaps with our advice for accessibility. We outline when a piece of advice relates to usability but is not covered by the legal accessibility regulations. 

### Machine readability 
Some sections mention best practice for machine readability. Often this overlaps with our advice for accessibility and usability. Sometimes it contradicts it. Depending on the complexity of your spreadsheets and your user needs you may need to publish two separate products, one for users who wish to download, read and analyse your spreadsheet and one for users who need your data to be optimsed for machine readability. 

We outline when the advice relates to machine readability and when there are possible clashes with the accessibility advice. 

We are planning to publish a checklist for making spreadsheets machine readable in the future.

## Example of an accessible spreadsheet

> [Labour market overview data tables, UK, December 2020: accessibility example (ODS, 664KB)](https://gss.civilservice.gov.uk/wp-content/uploads/2021/03/Labour-market-overview-data-tables-UK-December-2020-accessibility-example.ods)

We have applied our accessibility guidance to the summary of labour market statistics spreadsheet published in December 2020 by the Office for National Statistics (ONS). We hope this example will help you understand and apply this guidance. We have addressed four of the worksheets in this large and complex spreadsheet. The Digital Accessibility Centre (DAC) have audited this edited version and are happy that it meets all the accessibility guidelines. The feedback from DAC's accessibility tester illustrates the frustrations many users of assistive technology normally have with spreadsheets: 

> “When using the spreadsheet with [screen reader software] JAWS and NVDA I found it to be a pleasant experience. In the past I have found spreadsheets to be extremely confusing, disorientating and stressful. In part this stress came from having to make the document partially accessible for my own needs. If all spreadsheets were created with as much care and attention to detail, I may not be as reluctant to work with them as I am today."

The [ONS labour market summary datasets webpage](https://www.ons.gov.uk/employmentandlabourmarket/peopleinwork/employmentandemployeetypes/datasets/summaryoflabourmarketstatistics/current) has a link to the summary of labour market statistics spreadsheet as it was published by ONS in December 2020. 

## Contents 

* [Engage with users before making changes](#Engage-with-users-before-making-changes)
* [Document information](#Document-information)
* [Tables](#Tables)
* [Cells with no data](#Cells-with-no-data)
* [Formatting and use of colour](#Formatting-and-use-of-colour)
* [Images](#Images) 
* [Symbols, footnotes and codes](#Symbols-footnotes-and-codes)
* [Structure](#Structure)
* [Titles of spreadsheets, worksheets and tables](#Titles-of-spreadsheets-worksheets-and-tables)
* [Metadata worksheets](#metadata-worksheets)
* [Communicating uncertainty in spreadsheets](#Communicating-uncertainty-in-spreadsheets)
* [Worksheets with multiple tables](#Worksheets-with-multiple-tables)
* [Macros, formulas and application code](#Macros-formulas-and-application-code)
* [Accessibility checker](#Accessibility-checker)
* [Saving and publishing spreadsheets](#Saving-and-publishing-spreadsheets)


## Engage with users before making changes
Before making any big changes to your spreadsheets you should consult with your users, to warn them of any changes and to find out more about their needs. 

Some questions you might want to ask: 
* What are the statistics used for?
* What questions do they answer? 
* What problem is this solving?
* How do users access and view the statistics?
* What questions do users ask about the statistics?
* What information do users need to make use of the statistics?
* What tools do your users use?
* Are the statistics re-used in other analysis and outputs?
* Do your statistics meet the needs of your users?
* Do your users have new requirements or suggestions about how to present the statistics differently?
* Are all of your statistics still needed and used?
* What additional information is needed to support your users in their use and re-use of the statistics?
* Are your statistics presented in ways which are simple and convenient for your users?


## Document information 
Providing clear and useful document information improves usability. 

The accessibility guidelines require the title field and information about document language to be complete ([success criterion 2.4.2 page titled](https://www.w3.org/TR/WCAG21/#page-titled) and [3.1.1 language of page](https://www.w3.org/TR/WCAG21/language-of-page)). It is usability best practice to also fill in the author and keyword fields. 

### Adding document information
Go to ‘File’, then ‘Info’ and fill in the following fields:
* Title

Type in the title of the spreadsheet (more information about titles can be found in the 'Titles of spreadsheets, worksheets and tables' section of this guidance). 

Do not use dashes or underscores here.

* Author

Generally this should be the organisation that published the document – avoid using names of individuals.

* Keywords or Tags

Put in a list of terms that someone might use to search for the document, separated by commas. This helps search engines find the document. It also helps with finding your document internally.

### Setting the document language
Go to ‘File’, then ‘Options’, then ‘Language’. Make sure the document has the correct language(s) selected.

## Tables

In statistics we generally deal with two types of tables - demonstration tables and reference tables. 

If we are using a table to demonstrate a point that we are making in the text, we create a demonstration table. These lay out statistics to quickly reinforce the point.

Generally these should be published within the statistical report, ideally in the HTML of the webpage the report sits on. You should not publish images of tables as these are likely to fail accessibility [success criterion 1.4.5 images of text](https://www.w3.org/TR/WCAG21/#images-of-text). 

You can find out more about best practice for demonstration tables in our ['Introduction to data visualisation' guidance](https://gss.civilservice.gov.uk/policy-store/introduction-to-data-visualisation/#section-7) and our [‘Making analytical publications accessible’ guidance](https://gss.civilservice.gov.uk/policy-store/making-analytical-publications-accessible/#section-6).

Reference tables usually have lots of rows and columns of data and are aimed at users who need or want detailed data. There may be a wide variety of statistics broken down into different categories.

Reference tables are generally supplied in an spreadsheet document. It is these types of tables this guidance focuses on. 

### Marking up tables in spreadsheets
Ensure all tables in your spreadsheet are ‘marked up’ as a table – this is key to meeting accessibility [success criterion 1.3.1 info and relationships](https://www.w3.org/TR/WCAG21/#info-and-relationships), [guideline 2.4 navigable](https://www.w3.org/TR/WCAG21/#navigable) and [success criterion 2.4.3 focus order](https://www.w3.org/TR/WCAG21/#focus-order).

Marking up a table:
* allows a header row and table edges to be identified by assistive technology 
* allows your table to be named and appear in the 'go to' tool which is a keyboard shortcut that aids navigation (more information about this in the 'Naming tables' section)
* means a user will be able to tab through the data in a sensible way – for example when a user tabs to the end of the row, the next tab will take them to the start of the row below	
Note: if you keep tabbing past the end of the last row it does lead to extra rows being added to the table. However, as the table is marked up correctly, users of assistive technology should know when they get to the end of a table, so this isn’t considered an issue.

#### How to mark up a table in Excel: 
Be aware these instructions may differ slightly for different versions of Excel. 

At the moment this is a manual process, but we are researching ways to automate it. 

1. Select the cells you want to include in the table.
2. On the ‘Insert’ ribbon, select ‘Table’.
3. In the ‘Create table’ dialog box, check the ‘My table has headers’ box
4. Select ‘OK’.

Excel will, by default, give you a table with alternating blue colours. It will also make every column a filter. This is not accessible. 

#### Make the Excel default table accessible:
1. Click somewhere in the table 
2. Click the ‘Design’ ribbon.  
3. Select a plain table format in the ‘table styles’ section – go right to the top and you’ll see the plainest option with no formatting (you can make this the default table format by right clicking on it and selecting 'Set As Default'). 
4. Uncheck the ‘Filter Button’ box in the 'Table Style Options' section. 
5. If you have row labels in the first column, the cell in the header row will automatically be labelled 'Column 1' - you need to replace this with something sensible, it cannot be left blank. 

It is best practice to also:

* highlight column headings and row labels by setting the text to bold
* ensure the 'default' or 'automatic' colour is selected for all text (see the section on 'Colour and formatting' for more information on why this is important)
* left align all text in cells outside the table and all row labels within the table
* right align all data within a table and all column headings (except the one above the row labels - this should be left aligned)

> [Example of a table with accessible formatting (ODS, 5.73KB)](https://gss.civilservice.gov.uk/wp-content/uploads/2021/03/Example-of-a-table-formatted-in-a-plain-way.ods)

### Adding headers to a table that is already marked up
If the table is already created and you want to tag the header row:
1. Place the cursor anywhere in the table
2. Click onto the ‘Design’ ribbon 
3. Check the ‘Header Row’ box 

### Naming tables 
Make sure all tables in your spreadsheets have meaningful names. This will aid navigation for everyone. It will also help you pass accessibility [success criterion 2.4.6 headings and labels](https://www.w3.org/TR/WCAG21/#headings-and-labels) and [guideline 2.4 navigable](https://www.w3.org/TR/WCAG21/#navigable).

#### Name a table in Excel
1. Click anywhere in a marked-up table
2. Click the ‘Design’ ribbon 
3. In the 'Properties' section there is a box to edit the table name 
4. Type the table name in - note that Excel doesn’t allow spaces or dashes in table names, words must be split up with underscores

#### Check navigation with named tables
If you want to see a list of all the tables in your worksheet go to the ‘Formulas’ ribbon and click ‘Name manager’. 

To test out navigation you can click ‘Ctrl + G’. This brings up a ‘Go to’ tool. You can then click onto one of your tables and select ‘OK’ to be taken directly to that table. 

### Merged and split cells and nested tables
Restructure your tables so there are no split cells or merged cells or nested tables. This is a crucial issue to address as it is key for both machine readability and accessibility. 

Merged cells, split cells and nested tables make table structure hard to understand for assistive technology like screen reader software. Removing these elements is key to meeting accessibility [success criterion 1.3.1 info and relationships](https://www.w3.org/TR/WCAG21/#info-and-relationships). 

### Blank rows and columns within tables
Remove all blank rows and blank columns within tables. These may be perceived as the edge of the data area rather than a divider. Removing them is key to meeting accessibility [success criterion 1.3.1 info and relationships](https://www.w3.org/TR/WCAG21/#info-and-relationships) and [success criterion 1.3.3 sensory characteristics](https://www.w3.org/TR/WCAG21/#sensory-characteristics). 

If blank rows and columns are used to create space you can do this by adjusting column width and row height instead. 

### Column headings
Every table in your spreadsheet must have a correctly tagged header row, as described in the 'Mark up tables in spreadsheets' section. This is key to passing accessibility [success criterion 1.3.1 info and relationships](https://www.w3.org/TR/WCAG21/#info-and-relationships). 

Bear in mind that Excel can only tag one row as the header row. It is not necessarily a fail if you have subheading rows but as they can't be tagged as headers it may make the table confusing - so whenever possible, it is best avoided. 

You can put information about units or notes in the column heading cell (more information on how to do this in the 'Units' section).

#### Consistency in column headings
Consistency is important when it comes to column headings. Clear and consistent headings help accessibility, usability and machine readability. We advise you to follow a consistent naming convention within your spreadsheets and across your publications. 

If your spreadsheet uses multiple worksheets and the columns in these worksheets hold similar or identical data, use the same column names. For example: in a spreadsheet listing employee satisfaction survey results, use ‘department name’ in all tabs rather than ‘department name’ in some and ‘name of department’ in others. This makes it easier to cross reference and understand your tables and how they relate to one another. It also helps with machine readability and further analysis.

### Units
Displaying units in a consistent way is important for usability and machine readability.

Ensure it is clearly indicated if your columns use different units. If needed, put the units for your data in rounded brackets after the column heading – for example: ‘Number of people in employment (thousands)’. 

It is best to space the information about units so it appears under the column heading text – you can do this by pressing 'Alt + Enter' when typing in a cell. 

### Wrap text 
It is important to ensure all text in cells within a table is visible and clearly spaced out. This  will help you to pass accessibility [guideline 1.4 distinguishable](https://www.w3.org/TR/WCAG21/#distinguishable). You can do this by using the wrap text function and adjusting row height and column width. 

This is important because users with dyslexia can find it difficult to read crowded text. It is also important because a screen reader will repeatedly read out ‘overflowing’ or ‘cropped’ after every cell which contains text that does not fit. This causes 'auditory clutter' and can make tables difficult to understand. 

It is OK if there are a few sentences outside a table that overflow their cells – a screen reader will still read out ‘overflowing’ or ‘cropped’ but as this won’t be repetitive it is not a problem.

### Comparing numbers
If you are inviting users to compare numbers, it is best practice to:

* present the numbers close together, in columns - it is easier to make comparisons and determine patterns when numbers are arranged near each other and in columns instead of rows
* use the same level of precision in each column
* use commas to separate thousands
* right align the figures and the column headings
* start numbers of less than one with a zero, not a point

### Rounding
Presenting too much detail can make things harder for users. Simplifying numbers by rounding makes numbers easier to read and remember. This improves usability. 

The extent of rounding will depend on the intended use. A journalist may be happy to report that the population of the UK is 66 million, or that the population has changed from 64.1 million to 66.4 million. An analyst performing further calculations will want to work with more precise figures. Think about what your users may need. Consider leaving the underlying figures unrounded.

Rounding does reduce precision. This usually means that the reported totals no longer equal the sum of the component parts. If this is the case it should be communicated clearly. 

When rounding you should ensure all figures in a category are rounded to the same level of precision (for example one decimal point) and that any numbers less than one start with a zero, not a point (for example, 0.56 not .56). 

### Grouping
Objects grouped together are assumed to be associated. When used appropriately grouping may help users understand the data better. We advise that you group different measures in rows and different types of estimate in columns.

White space can be used to separate the data into groups. You can do this by adjusting column width and row height. Do not use blank rows or columns as this may fail accessibility [success criterion 1.3.1 info and relationships](https://www.w3.org/TR/WCAG21/#info-and-relationships) and [success criterion 1.3.3 sensory characteristics](https://www.w3.org/TR/WCAG21/#sensory-characteristics).  

> [Example of using white space to split data into groups (ODS, 5KB)](https://gss.civilservice.gov.uk/wp-content/uploads/2021/02/Labour-market-rates-by-UK-region-Aug-to-Oct-2019.ods) 

### Ordering categories
Ordering the categories in a table can make it easier for users to see patterns and groups in the data. This improves usability. 

For some categorical variables, like month of the year or age group, there is a natural order for presentation. Other variables may have harmonised ordering, such as areas of the UK. More information on how to order UK areas can be found on the [Open Geography Portal](https://geoportal.statistics.gov.uk/) under 'General principles'.

We have published several [harmonisation standards](https://gss.civilservice.gov.uk/policy-store/?keyword=&area=harmonisation&doctype=&submit=Go) which may help you when ordering categories. An appropriate order may also be obvious from knowledge of the subject matter.

Alternatively, consider ordering categories according to the statistics in one of the columns, for example put the largest value at the top. This shows the rankings of the categories on that statistic. Ranking the categories in this way emphasises the relative positions of the categories. It may also show where some statistics differ from the overall pattern. Be aware that in some cases, the relative positions may be determined by random variation.

### Summary rows and columns
Summary rows and columns, for example for totals, should always be at the edge of a table. Traditionally they are placed at the bottom or right. If it’s important for users to see the summaries first, it may be helpful to place the them at the top or left. 

### Adding filters
We advise you to avoid adding filters. They may fail the accessibility guidelines if they obscure data. 

If you do need to use filters it is important to provide signposts or comments to indicate which cells contain the drop-down menus and if any data is hidden. You should also give details of how to turn the filters off. For example: "Filters are active in cell C3 and may hide some data. To turn off all filters select the 'Data' ribbon then 'Filters' button or use [Ctrl, Shift, L]". 

This information should be in a cell in column A, above the table so users come across it before getting to the data. 

### Adding freeze panes
We advise you to avoid adding freeze panes. They may fail accessibility [guideline 2.4 navigable](https://www.w3.org/TR/WCAG21/#navigable) as they can make it difficult for screen reader users to find the top left edge of a worksheet, which is key to navigation. 

If you do leave freeze panes active it is best practice to inform users and give a instructions for how to turn them off. For example: "Freeze panes are turned on. To turn off freeze panes select the 'View' ribbon then 'Freeze Panes' then 'Unfreeze Panes' or use [Alt W, F]". As with filters, this information should be in a cell in column A, above the table so users come across it before getting to the data. 

Be aware that if you save your spreadsheet in the Open Document Spreadsheet (ODS) format (which we advise you to do) freeze panes will disappear. 

### Adding alt text to tables 
In Excel, you can add alternative text to your table by right clicking anywhere in the table and selecting ‘Table’ and ‘Alternative text’. However, if your tables are marked up correctly it is not necessary to do this to pass the accessibility guidelines.

Be aware that despite this, newer versions of Excel have a built-in accessibility checker which may bring up tables without alt text as a fail. You don’t need to worry about this. 

If you save your spreadsheet in the ODS format (which we advise you to do) alternative text for tables will disappear – but this does not matter as it is not needed to pass the accessibility guidelines. 

Note: it is necessary to provide alternative text for images and charts and this does not disappear when you save in the ODS format. 

## Cells with no data

### Accessibility and usability for cells with no data
When cells with no data are left blank it can cause confusion for users of assistive technology because it makes it difficult for their technology to work out where the table starts and ends. Therefore, blank cells could be considered a fail of accessibility [success criterion 1.3.1 info and relationships](https://www.w3.org/TR/WCAG21/#info-and-relationships) and [guideline 2.4 navigable](https://www.w3.org/TR/WCAG21/#navigable).

However, we are carrying out research into this, it may be the case that as long as a table is marked up correctly, blank cells within a table do not cause a problem for navigation with assistive technology. 

In terms of usability, blank cells may be considered bad practice as they do not tell a user why there is no data in the cell - a user might incorrectly assume the data value is zero or that there has been a mistake and data is missing. 

Therefore our current advice for cells with no data is to give users information about why there is no data, without using symbols like full stops (..) or dashes (-). Instead, cells with no data should be marked up descriptively (more information on the use of symbols can be found in the [Symbols, footnotes and codes](#symbols-footnotes-and-codes) section).  

Here are some examples of descriptions you may want to use: 
* If there is no data available, type in ‘no data’.
* If the data is missing, type in ‘missing’.
* If the data would be disclosive, type in 'disclosive'.

If you wish to expand on any of your descriptions you should present the information above the table, in a cell in column A so the information is available before a user comes to the table itself. If the information is lengthy, you can say the full explanation is available on the cover sheet or in the notes table (more information on the cover sheet and notes table can be found in the [Structure](#Structure) and [Metadata worksheets](#Metadata-worksheets) sections). 

You can also use shorthand such as 'm' for missing or 'd' for disclosive. As long as you outline what this shorthand means above the table in a cell in column A. This will ensure a user comes across this guidance before they get to the table itself.  

We advise against using 'NA' to describe cells with no data. While in statistics this often means Not Available, many users will assume it means Not Applicable. If you want to use NA as shorthand you must clearly define what it means, above the table, in a cell in column A.  

We are looking into drafting guidance on what words or letters to use for different circumstances so that empty cells are marked up in a consistent way across government statistics and analysis. 

> [Example of blank cells marked up descriptively (ODS, 3.96KB)](https://gss.civilservice.gov.uk/wp-content/uploads/2021/03/Example-of-a-table-with-empty-cells.ods)

Please note - we are aware that leaving cells with no data blank may make it easier for users to perform further analysis, but this feature of usability has to be balanced against the accessibility guidelines and the importance of a user understanding why a cell has no data. As mentioned, our advice on cells with no data may change as we do further research.

### Machine readability for cells with no data  
In terms of machine readability, leaving cells with no data blank is best practice. Therefore if you are making a spreadsheet solely for machine reading purposes, it is best practice to leave cells with no data blank. 

## Formatting and use of colour

### Written content
Written content in your spreadsheets should be treated in the same way as written content in a statistical report. For example, if you use a style guide for your reports, you should use this for any written content in your spreadsheets.  

In terms of accessibility, all written content in your spreadsheet should follow the advice in the [‘Making written content accessible’ section](https://gss.civilservice.gov.uk/policy-store/making-analytical-publications-accessible/#section-4) of our ‘Making analytical publications accessible’ guidance. 

A key part of this is tagging headings and subheadings correctly (more information on doing this in spreadsheets can be found in the [Titles of spreadsheets, worksheets and tables](#Titles-of-spreadsheets-worksheets-and-tables) and the [Metadata worksheets](#Metadata-worksheets) sections). 

### Hyperlink text
It is often helpful to link to extra information or related statistics. 

When it comes to accessibility, embedding hyperlinks correctly is specifically mentioned in the accessibility guidelines. It comes under accessibility [success criterion 2.4.4 link purpose (in context)](https://www.w3.org/TR/WCAG21/#link-purpose-in-context) and [guideline 3.2 predictable](https://www.w3.org/TR/WCAG21/#predictable).

#### Making hyperlinks accessible
1. Use specific descriptions 

Hyperlink text should be a specific description of the destination, not just ‘blog post’ or ‘report’ and never directional text like ‘click here’. Bear in mind that screen readers can be programmed to read out a list of links within a document (much like a sighted user would scan a page for links). When link text is not specific, a sighted user can read the surrounding text, a screen reader cannot. This means the links will be difficult to tell apart so the screen reader user will not be able to easily find a link they may be interested in.

2. Don't use URLs 

Do not use the [URL](https://techterms.com/definition/url) of a webpage as the hyperlink text, unless it is very short (e.g. www.unsplash.com). Screen readers read out long URLs in full, letter by letter. This can be very time consuming and annoying. Also, in most circumstances they do not describe the destination page.

3. Linking to documents 

If you are linking to another document the link text should contain the descriptive text, the type of document and its size, for example: ‘[Template to report breaches of the Code of Practice for Statistics (ODT, 23 KB)](https://gss.civilservice.gov.uk/wp-content/uploads/2020/10/Breach-reporting-template.odt)’.

4. Consistency in signposting  

Make sure that links to the same destination have consistent text and that links with different purposes and destinations have different link text. For example, it is bad practice to provide lots of links to different destinations with non-specific link text like ‘Find out more’.

5. Formatting link text

[Link text should be underlined by default](https://webaim.org/resources/linkcontrastchecker/?fcolor=0000FF&bcolor=FFFFFF). If it is not underlined the accessibility guidelines say that you have to consider colour contrast with surrounding text and a 'visual cue' that appears on mouse hover and keyboard focus. Bear in mind that, while not a necessity in terms of the accessibility guidelines, it is best practice for hyperlink text to be both underlined and have the correct amount of colour contrast with the background and the surrounding text.

### Dates and time periods 
It is best practice to format dates and time periods as advised by the [Office for National Statistics style guide](https://style.ons.gov.uk/house-style/dates/) and [Government Digital Service guidance](https://www.gov.uk/guidance/style-guide/a-to-z-of-gov-uk-style). 

This means: 
* do not use dashes, use ‘to’, for example, don’t use ‘Jan – Mar 2020’ use ‘Jan to Mar 2020’
* it is fine to truncate days and months to save space
* do not truncate years, for example, write: ‘Jan 1931’ not ‘Jan 31’ 
* when referring to quarters of the year, write out the months, for example, 'Jan to Mar 2020’ not ‘Q1 2020’
* if your data needs specific dates for example: 01/02/10 you can present them like this but be aware screen readers will read this as ‘01 slash 02 slash 10’ which can be annoying and cause auditory clutter, so it is best practice to write ‘1 Feb 2010’

### Other pointers for formatting that must be followed to meet the accessibility guidelines: 
* No visual devices such as colour, shading or patterns should be used to divide up data regions ([success criterion 1.4.1 Use of colour](https://www.w3.org/TR/WCAG21/#use-of-color) and [success criterion 1.3.3 sensory characteristics](https://www.w3.org/TR/WCAG21/#sensory-characteristics).
* No text is set in a vertical or diagonal direction - this is not mentioned specifically in the accessibility guidelines but it may be considered necessary to pass [guideline 1. perceivable](https://www.w3.org/TR/WCAG21/#perceivable) and [guideline 4. distinguishable](https://www.w3.org/TR/WCAG21/#distinguishable).
* No text has spaces between letters in a word for visual effect as this can be difficult to read and screen readers will read the letters out one by one - this is not mentioned specifically in the accessibility guidelines but it may be considered necessary to pass [guideline 1. perceivable](https://www.w3.org/TR/WCAG21/#perceivable)
* Colour is never used as the only way to communicate a message - this fails accessibility [success criterion 1.4.1 Use of colour](https://www.w3.org/TR/WCAG21/#use-of-color) and complicates machine readability.
* The minimum font size used is size 12 - in general this will help you meet [success criterion 1.4.4 resize text](https://www.w3.org/TR/WCAG21/#resize-text).
* Make sure there are no spelling or grammatical mistakes - this will ensure you meet accessibility [guideline 3.1 readable](https://www.w3.org/TR/WCAG21/#readable) - you can run a spelling and grammar check in Excel – in newer versions it is on the ‘Review’ ribbon. 
* No columns or rows are hidden from view ([guideline 1. perceivable](https://www.w3.org/TR/WCAG21/#perceivable)) - if this is needed you will need to give guidance in a cell in column A, above any tables, on what rows or columns are hidden and how to unhide them. 

### Other pointers for formatting that should be followed in terms of best practice 

* Consider how your tables are structured - remember it is easier to read down a list than across a table so you may want to think about transposing your data.
* Only use sans serif fonts like Arial or Calibri as people with dyslexia find serif fonts hard to read.
* Avoid the use of underline and italic text - people with dyslexia can find italic and underlined text hard to read, if you need to highlight text it is best to use bold.
* Avoid changing the colour of text to draw attention to it - if you do this you must check the colour contrast of the text against the background colour (more information on how to do this can be found in the 'Checking text colour contrast' sub-section). 
* Use the 'default' or 'automatic' colour settings for all text - doing this will ensure the spreadsheet takes on the specialised colour settings users of assitive technology may have set up on their software
* Don't add a background fill - some users will have settings that automatically change the colour of the background to make the content easier for them to read, but this doesn't happen if you have added a fill colour – even if it is white. 
* Avoid adding grid lines or cell borders - in general it it better to keep things simple.
* Avoid including images of charts in your spreadsheet, if you do you must carefully consider their accessibility, particularly the colour contrast between chart elements (more information on how to do this can be found in the 'Checking colour contrast in charts' sub-section). .
* Left align all text in cells outside the table and all row labels within the table.
* Right align all data within a table and all column headings (except the column of row labels). 
* Use commas after every three decimal places in numbers of four digits or more, and never spaces (except when writing years - these should have no punctuation)
* Set sensible zoom levels before you save your spreadsheet. 

In terms of machine readability you should also: 

* avoid using indentation to indicate subsections (for example indenting a list of regions under a row for ‘England’) or hierarchies 
* ensure no cells with text have ‘hidden’ spaces at the start or end
* check there are no spaces at the start or end of worksheet names
* consider using an Application Programming Interface (API) to aid further analysis

### Checking text colour contrast  
If colour is used in cells with text, use the [WebAIM colour contrast checker](https://webaim.org/resources/contrastchecker/) to see if the colours meet the accessibility regulations. Remember, legally you need to meet the AA standard. 

Be aware that colours are coded in different ways. To use the WebAIM colour contrast checker you will need to know the hex code of the colours. Excel will give you the Red Green Blue (RGB) codes - you can use this [colour code converter](https://www.webfx.com/web-design/hex-to-rgb/) to get the hex codes.  

### Checking colour contrast in charts 
The use of colours in charts is more complex as you often have to consider colour contrast between different chart elements as well as with the background. Our [data visualisation guidance](https://gss.civilservice.gov.uk/policy-store/introduction-to-data-visualisation/#section-9) and the [style guide from the Office for National Statistics](https://style.ons.gov.uk/category/data-visualisation/using-colours/) both have useful tips on this area but neither have yet been fully updated with regards to the accessibility guidelines. We are planning on looking into this in more detail soon. 

## Images
Images within spreadsheets should be avoided. 

This includes any departmental logos. Placing a departmental logo on a cover sheet may fail accessibility [guideline 2.4 navigable](https://www.w3.org/TR/WCAG21/#navigable) as these images can make it difficult for users of assistive technology to work out where they are on a worksheet. It is better to write out the name of the government department rather than have it in a logo. 

If you can’t avoid it, make sure all logos, graphics, charts and any other images within the spreadsheet document have alternative text attached to them (accessibility [success criterion 1.1.1 non-text content](https://www.w3.org/TR/WCAG21/#non-text-content)). 

On a cover sheet, all the text should be in column A (as disabled users normally navigate down from cell A1). Any images of logos should be placed to the right of this text so they don't disrupt navigation. More information on what a cover sheet should look like can be found in the in the [Metadata worksheets](## Metadata worksheets) section.

If you include images of charts, you will need to ensure they are accessible. You will need to consider the colour contrast of chart elements with each other and the background (see the sub section called 'Checking colour contrast in charts'). You will also need to consider any text on the chart. Ideally this will be minimum size 12, in a sans serif font with no use of italics or underline. Images of charts should be placed on a separate worksheet to any tables. 

Wherever you publish charts, you should aim to follow best practice guidance. See our [guidance on data visualisation](https://gss.civilservice.gov.uk/policy-store/introduction-to-data-visualisation/) and the [Office for National Statistics' style guide](https://style.ons.gov.uk/).

You should also check your specific departmental guidance on including images in spreadsheets. Some departments may not allow you to publish any images within a spreadsheet document. 

### How to add alt text for charts and images 
1. Right click on the image or chart and select 'Format Picture/Chart Area'.
2. Go to the size and properties box and select ‘Alt text’.
3. Enter a title and description for your alt text in the boxes and select ‘OK’.

On newer versions of Excel you may just need to right click and select 'Edit Alt Text'. 

If an image is just decorative you should mark it as such by ticking the 'Decorative' checkbox (Excel 2013 doesn’t let you do this but later versions do).

## Symbols, footnotes and codes 
### Short footnotes 
It is best practise in terms of accessibility (and arguably, usability) to put as much information as possible at the point of need – for example when data is provisional or revised put the whole word in rounded brackets instead of using ‘p’ or ‘r’. 

However, when needed, using letters to signify notes is generally OK as long as the key to what these letters mean is clearly laid out above the table in a cell in column A. This ensures a user is made aware of the key before coming to the table. However, you should not use superscript text as this can be difficult to see for users with low vision and screen reader software does not differentiate superscript text from non-superscript text. You should also avoid using symbols to signpost to notes (see the sub section 'Use of symbols'). 

### Detailed footnotes
When signposting to detailed footnotes we advise you to: 
* write out the word ‘note’ in the cell, with the number of the note you need to refer to, and put it in square brackets (we advise square brackets for notes and rounded brackets for units to differentiate them in a consistent way), for example 'Number of people in employment [note 1]'
* put a list of numbers if a cell needs to refer to more than one note – for example, write ‘[note 1,2,3]’ if a cell needs to refer to notes 1, 2 and 3. 
* try to always put notes in table titles, column headings or row labels - putting them in specific cells may not fail accessibility but it does cause problems for machine readability and usability 
* if a note is in a column heading, space the text so the note marker sits underneath the column header text and any information about units (you can do this by pressing 'Alt and Enter')
* mention that notes are used, in a cell in column A above the table and say where the notes can be found (more information about use of cells in column A can be found in the [Structure](#Structure) section)

When displaying the content of detailed notes it is common practice for them to be placed underneath the table. However there are several issues with this: 
1. It can take lots of scrolling to get to notes placed under very long tables, particularly for some disabled users - this is bad practice for usability and accessibility. 
2. Notes placed under tables may be missed by some disabled users who aren't expecting them to be there. It is possible to combat this by mentioning that notes sit underneath the table, in a cell in column A above the table (more information about use of cells in column A can be found in the [Structure](#Structure) section).
3. Notes placed underneath a table need careful (and mostly manual) formatting to be made accessible (see the section on [Structure](#Structure) and [Metadata worksheets](#metadata-worksheets) for more information on how written content should be formatted). Without this formatting you may fail accessibility [guideline 2.4 navigable](https://www.w3.org/TR/WCAG21/#navigable).
4. Long detailed notes may result in a need for horizontal scrolling which is bad practice for usability and accessibility. This may happen because the note will need to be displayed in one cell - you shouldn't use merged cells to present long notes as merged cells fail accessibility guidelines (see the section on [Tables](#tables)).
5. In complex spreadsheets, identical notes are often placed under several tables across many worksheets - this can mean, when certain notes are updated or changed, some are accidentally missed out.

For these reasons we advise you to create a worksheet called ‘Notes’ which contains a table that lists all the detailed notes for the spreadsheet. 
Notes placed underneath a table will not necessarily fail the accessibility guidelines but they will need careful consideration and, depending on the size of the table and how they are laid out, they may be considered bad practice. 

> [Example of presenting a key for shorthand and notes (ODS, 4.4KB)](https://gss.civilservice.gov.uk/wp-content/uploads/2021/03/Example-of-a-table-with-notes-and-a-key.ods)
> See the labour market [example spreadsheet](#example-spreadsheet) also. 

### Use of symbols 
You should not use symbols to signpost footnotes because: 
* they can be confusing
* screen readers may not recognise them 
* users with low vision may not be able to see them

Therefore, if you use symbols to signify notes it may lead to a fail of accessibility [guideline 1 perceivable](https://www.w3.org/TR/WCAG21/#perceivable) and [success criterion 1.3.1 info and relationships](https://www.w3.org/TR/WCAG21/#info-and-relationships).
 
However, use of symbols is not always a fail of the accessibility guidelines. You just need to be aware that some screen reader software will not recognise symbols and some screen reader users may have changed their settings to ignore symbols to avoid auditory clutter. This means you should consider how your text reads if you miss out the symbols. For example the sentence ‘Some shorthand is used in this spreadsheet, e = estimated, r = revised' still makes sense if read out as ‘Some shorthand is used in this spreadsheet, e estimated, r revised’.  

Deque (a company that helps businesses make their websites and mobile applications accessible) has published [research into how different screen reader software deals with symbols](https://www.deque.com/blog/dont-screen-readers-read-whats-screen-part-1-punctuation-typographic-symbols/) when using their default settings. They list 17 characters considered 'safe' to use. These include £, %, & and /. But, as mentioned, some users may have changed their settings from the default so in general it is best to use words instead of symbols wherever possible. 

It is OK to use dashes and slashes in classifications and geography codes as these are needed for consistency.  

### Classifications and geography codes 
You may need to use classifications or [geography codes](https://www.ons.gov.uk/methodology/geography/geographicalproducts/namescodesandlookups/namesandcodeslistings/namesandcodesforadministrativegeography) in your tables.

Some pointers:

1. Use the right codes
Make sure you are using the correct, nationally recognised codes. If you need any help in this area the harmonisation leads in the [Best Practice and Impact team](https://gss.civilservice.gov.uk/about-us/support-for-the-gss/) can provide advice. This is important for usability and machine readability. 

2. Classifications, codes and accessibility 
Classifications and geography codes are generally fine in terms of accessibility as they are usually strings of letters and numbers. When codes are not just strings of letters and numbers, you should still use them consistently. It is OK to use symbols such as dashes and slashes here as that is how the code is constructed.

3. Help users understand codes
It is best practice to link to supporting information for any codes used, either as a note or on the cover sheet (more information on notes and cover sheets can be found in the [metadata worksheets](#metadata-worksheets) section). 

You should also help users understand any changes in codes or classifications – for example, the [Geography Code History Database](https://www.ons.gov.uk/methodology/geography/geographicalproducts/namescodesandlookups/codehistorydatabasechd) helps users track changes in area codes.

4. Presenting codes in tables
In terms of usability, machine readability and accessibility ([success criterion 1.3.1 info and relationships](https://www.w3.org/TR/WCAG21/#info-and-relationships)), codes should be in separate cells to the description of the code and the data. For example, country code AD should be in a separate cell to the country name Andorra, and then there should be another cell for the data linked to this country. The row or column containing the codes must be labelled clearly. 

> [Example of presenting country codes (ODS, 6.31KB)](https://gss.civilservice.gov.uk/wp-content/uploads/2021/03/Example-presenting-country-codes.ods)

### Machine readability - differences in best practice for symbols, footnotes and codes
If you are making a spreadsheet solely for machines to read you can use symbols but you must provide information on what those symbols mean via the metadata. More information on how to best supply metadata for machine readability can be found in the [Metadata worksheets](#metadata-worksheets) section. 

In terms of presenting symbols and footnote markers it is best practice for machine readability to put the symbols or footnote markers in separate (very narrow) columns, next to the data. This approach does not fail any accessibility guidelines in itself, but you would need to give that column a heading and you might also need to mark up all the empty cells (we are still researching what needs to be done to make empty cells accessible). This could make a table very wide which is not great for readability. 

## Structure
Properly structuring your content is important to meet accessibility [success criterion 1.3.1 info and relationships](https://www.w3.org/TR/WCAG21/#info-and-relationships).

### Pointers for the spreadsheet as a whole

#### Provide supporting information 
From a usability point of view, statistics should not be completely separated from supporting information. Context and caveats are vital to ensure users have enough information to interpret and make effective use of the data. You should hyperlink to supporting information if it cannot be easily included within the spreadsheet tabs (more information on how to use hyperlinks can be found in the [Formatting and use of colour](#formatting-and-use-of-colour) section). 

#### Cover sheet and table of contents 
For most spreadsheets it is useful if the first worksheet is a cover sheet which provides information about the data. If your spreadsheet has many worksheets, it is also a good idea to create a table of contents that describes the data within each worksheet. 

Simpler spreadsheets may not need a cover sheet or table of contents. 

Including a cover sheet and table of contents in  more complex spreadsheets will help you to pass accessibility [success criterion 1.3.1 info and relationships](https://www.w3.org/TR/WCAG21/#info-and-relationships) and [success criterion 1.3.2 meaningful sequence](https://www.w3.org/TR/WCAG21/#meaningful-sequence).

More guidance on cover sheets and the table of contents can be found in the [Metadata worksheets](#metadata-worksheets) section.

#### Worksheet names
Ideally each worksheet should have a unique name that clearly describes the information found in that sheet. If this is not possible, give each sheet a number and use your table of contents to describe what is in each worksheet. 

To avoid any confusion for assistive technology and to improve usability and machine readability you should: 

* remove extra spaces from the start or end of worksheet names
* keep worksheet names as consistent as you can between releases

#### Blank worksheets
Remove any blank worksheets. Blank worksheets can be confusing as it is not clear if they are meant to be blank or if something is missing. They may also make navigation confusing for disabled users leading to a fail of accessibility [guideline 2.4 navigable](https://www.w3.org/TR/WCAG21/#navigable).

#### Other things to avoid 
* Do not use headers and footers to convey important information - this will fail accessibility as screen readers often can't find the information displayed in spreadsheet headers and footers.
* Do not use floating elements such as text boxes - these will fail accessibility as screen readers often can't 'see' inside text boxes.
* Deactivate any floating toolbars - these may fail accessibility as screen reader software may not be able to access populated cells behind them - if you do need to leave a floating toolbar active then attach it to the other Excel toolbars at the top of the window.

### Pointers for structure within worksheets: 

#### Information in column A
Column A is very important for disabled users. For example, a screen reader will generally start each worksheet by reading out the information in cell A1. Similarly, keyboard-only users will also tend to navigate down from cell A1. Using column A in the following way will make it easier for you to meet accessibility [success criterion 1.3.1 info and relationships](https://www.w3.org/TR/WCAG21/#info-and-relationships) and [success criterion 1.3.2 meaningful sequence](https://www.w3.org/TR/WCAG21/#meaningful-sequence).

The key thing to ensure is that the information a user needs to understand the table is positioned above the table, in a place where disabled users are most likely to read it. It is useful to remember that many disabled users cannot scan content in the way other users can.     

Cell A1 on each worksheet should tell a user what information is contained on that worksheet. Generally, if there is one table per worksheet, cell A1 contains the title of that table. 

Cell A2 should be used for description – for example: ‘This worksheet contains one table. Some cells refer to notes which can be found on the notes worksheet’.  

If relevant, information about frozen panes, filters and any symbols or shorthand used within the table should also be presented in column A. 

If you have several worksheets and they use different sources, a cell in column A should contain information about the source for the table on that sheet. However, if each table in the spreadsheet uses the same source, the information about sources can go on the cover sheet. 

#### Positioning tables on worksheets 
Position tables against the left-hand edges of each sheet. Don’t leave a blank column as a gap. As mentioned disabled users tend to navigate down from cell A1, if they hit blank cells it can be very hard to navigate to where the table is and your spreadsheet may fail accessibility [guideline 2.4 navigable](https://www.w3.org/TR/WCAG21/#navigable).

#### Below the table
It is best practice to avoid putting any information below a table. It can be difficult to navigate to and may be missed by disabled users. It will also require mostly manual formatting to ensure it meets accessibility guidelines, which can be time consuming. More information on formatting text in spreadsheets can be found in the [Titles of spreadsheets, worksheets and tables](#titles-of-spreadsheets-worksheets-and-tables) and the [Metadata worksheets](#metadata-worksheets) sections. 

If a user needs to access information below the table in order to understand the data within the table, it may lead to a fail of accessibility [success criterion 1.3.2 meaningful sequence](https://www.w3.org/TR/WCAG21/#meaningful-sequence). For example, if you have used some shorthand in your table such as 'e' for 'estimated' and you only mention what 'e' signifies below the table, this could be considered a fail.

Therefore, you should put all information a person needs to know in order to understand the table, in column A, above the table. 

When it comes to more detailed notes referring to context and caveats we advise that these should live in a table on a ‘Notes’ worksheet (more information on how to present notes can be found in the [Symbols, footnotes and codes](#Symbols-footnotes-and-codes) section). 

## Titles of spreadsheets, worksheets and tables

Titles and headings affect usability, accessibility and machine readability. 

Titles and labels are important parts of table design. They help users understand the data. They are particularly important if the table is copied and placed into another context.

In terms of accessibility, if users cannot find or understand the data they need, your spreadsheet may fail accessibility [guideline 2.4 navigable](https://www.w3.org/TR/WCAG21/#navigable) and [3.1 readable](https://www.w3.org/TR/WCAG21/#readable). It may also fail accessibility [success criterion 2.4.6 headings and labels](https://www.w3.org/TR/WCAG21/#headings-and-labels).

It is also important to be consistent when writing titles for spreadsheets, worksheets, tables and column headings. A lack of consistency within a publication and between different releases, limits machine readability. 

Pointers: 
* Make sure the overall title for your spreadsheet gives a clear description of the data and includes the time period and geographical region the data applies to.
* Use standard and consistent title formats across your publication porfolios and within your spreadsheets.
* It is best practice to have one table per worksheet - this means the title of the worksheet should be the title of the table. 
* In large spreadsheets it is a good idea to number your tables, for example: ‘Table 1: Number of people in different age groups, UK, seasonally adjusted’. 
* In general the titles of tables should include a description of the data and the geography it applies to, for example: ‘Number and percentage of people aged 16 to 64 in each labour market activity group, UK'

### Where to place and how to tag titles 
To meet accessibility [success criterion 1.3.1 info and relationships](https://www.w3.org/TR/WCAG21/#info-and-relationships) and [success criterion 2.4.6 headings and labels](https://www.w3.org/TR/WCAG21/#headings-and-labels) the worksheet title should be in Cell A1 and should be marked up as Headings 1 using the ‘Cell Styles’ tool on the ‘Home’ ribbon. This 'marks up' the heading which helps assistive technology navigate around the spreadsheet. 

### Formatting cells tagged as headings
The Excel default formatting for headings is not accessible. We advise you to modify the default formatting rather than to simply edit the text colour and cell borders as this is better for accessibility. See the [Formatting and use of colour](#formatting-and-use-of-colour) section for more information. 

#### How to modify the default formatting of headings
1. Select the cell the heading text is in
2. Select 'Cell Styles' in the 'Styles' section of the 'Home' ribbon 
3. Go to the headings style you want to modify (the title of a worksheet should be 'Headings 1')
4. Right click and select 'Modify'
5. Select 'Format'
6. Make sure you choose a sans serif font and at least size 12 (although for headings we would suggest a slightly larger font) 
7. Make sure you select the 'automatic' colour setting (see the [Formatting and use of colour](#formatting-and-use-of-colour) section for more information on why this is important)
8. We would also suggest you go to 'Borders' and select 'None' as underlined text can be hard to read for people with low vision or dyslexia 

Note: these instructions may differ for different versions of Excel

## Metadata worksheets
It is best practice for spreadsheets inteded for people to open, read and analyse, to include worksheets with information about the data (metadata).

### Cover sheet

If your data is simple and there is only one table in your spreadsheet, you might not need a cover sheet. However, they are generally useful in most circumstances. 

#### Information to include on your cover sheet 
Decisions on what information should go into a cover sheet will vary from one statistical release to the next. 
It is best practice to include the following information (if applicable to your data): 
* The title of the spreadsheet - this should briefly describe the data, the time period covered and the geographical region the data tables refer to. 
* A brief summary of what the data tables are about.
* The name of the statistical release the data relates to with a hyperlink to that release.
* The source for the data - if you have a complex spreadsheet with many different tables and sources you can put source information on each individual worksheet (above the table) or have it in a column in your table of contents.  
* The date the spreadsheet was published.
* The date the next update to the spreadsheet will be published.
* Information on whether data are provisional or revised. 
* Key information users need to know that relates to all (or nearly all) worksheets in the spreadsheet, for example information on weighting.
* Contact details for the statisticians responsible for the data and for media enquiries 

You might also want to include: 

* information on where to find related data or supporting publications.
* links to a wider data series - although we would advise, wherever possible, to keep time series or historical data in the same spreadsheet
* links to supporting information about the data and methodology documents.
* information on the quality of the statistics
* link to a glossary of essential technical terms and acronyms.

However, if your cover sheet is starting to look like a text document it is best practice to publish this extra information on a webpage instead and link to it. Ideally this will be the webpage where the spreadsheet lives. For more information on this see the [Saving and publishing spreadsheets](#saving-and-publishing-spreadsheets) section.

#### Making cover sheets accessible
To meet accessibility [success criterion 2.4.2 page titled](https://www.w3.org/TR/WCAG21/#page-titled) the title of the spreadsheet should be in cell A1 of the cover sheet. This title should be tagged as 'Headings 1' using the cell styles tool (more information on tagging headings can be found in the [Titles of spreadsheets, worksheets and tables](#titles-of-spreadsheets-worksheets-and-tables) section).

To meet accessibility [success criterion 1.3.1 info and relationships](https://www.w3.org/TR/WCAG21/#info-and-relationships) and [success criterion 2.4.6 headings and labels](https://www.w3.org/TR/WCAG21/#headings-and-labels) you should use subheadings to break up the information. These subheadings should be tagged using the cell styles tool. First level subheadings should be tagged as Headings 2, second level subheadings as Headings 3 and so on.  

Make sure all the written content follows the advice in the [‘Making written content accessible’ section](https://gss.civilservice.gov.uk/policy-store/making-analytical-publications-accessible/#section-4) of our ‘Making analytical publications accessible’ guidance.

### Table of contents 

If you have a lot of worksheets in your spreadsheet you should create a table of contents that describes the data within each worksheet. This will ensure you meet accessibility [guideline 2.4 navigable](https://www.w3.org/TR/WCAG21/#navigable).

This can live within the cover sheet or on its own worksheet, but make sure it is marked up properly as a table and named ‘Table_of_contents’ (more information on marking up and naming tables can be found in the [Tables](#tables) section. If it is on its own worksheet make sure this is named ‘Table of contents’.

This table of contents can also contain other information such as the source of the data (particularly if several different sources are used throughout the spreadsheet), the date of the last update and the date of the next update. 

Hyperlinking from the table of contents to cell A1 of each worksheet also aids navigation around a large spreadsheet but is not strictly necessary if all tables are marked up and named consistently. We wouldn't suggest linking to the tables directly as this may mean users will miss information presented above the table that they need to understand. 

### Notes worksheet 

If certain cells in your spreadsheet refer to notes, it is better for usability and accessibility to create a table of notes that lives in a ‘Notes’ worksheet than to put information underneath each table. More information on this can be found in the [Symbols, footnotes and codes](#symbols-footnotes-and-code)' section of this guidance. 

Remember that the table of notes will need to be marked up and named appropriately. 

### How to supply metadata if optimising for machine readability

If you are publishing a spreadsheet optimised for machine readability it is best to remove all information about the data (metadata) from the spreadsheet file. This includes information in the cover sheet, table of contents and any notes. Metadata should instead be provided via an associated metadata file. For example, metadata for statistics.csv should be provided in the statistics.csv-metadata.json file. See [CSVW (CSV on the web)]( https://www.w3.org/TR/tabular-data-primer/#metadata) for an appropriate metadata file specification.

## Communicating uncertainty in spreadsheets

When designing a statistical spreadsheet, it is best practice to consider how to appropriately communicate any uncertainty to your users. Bear in mind that the user may not read detailed documents, or they may have copied the spreadsheet to use in another context.

Use the notes worksheet or the cover sheet to: 
* make it clear if there are any potential sources of bias or uncertainty – users need to know how this impacts on their use of the statistics
* highlight relevant information about comparability issues both across time and with equivalent statistics released elsewhere in the UK 

For more information on the notes worksheet and cover sheet please see the [Symbols footnotes and codes](#symbols-footnotes-and-codes) and the [Metadata worksheets](#metadata-worksheets) sections.

### Confidence intervals 

When communicating confidence intervals it is best practice in terms of usability, accessibility and machine readability to put the higher and lower bounds in separate cells next to the data. Make sure all columns have clearly labelled column headings - this is good for usability and essential to meet accessibility [success criterion 1.3.1 info and relationships](https://www.w3.org/TR/WCAG21/#info-and-relationships).

[Example of how to present confidence intervals (ODS, 4.19KB)](https://gss.civilservice.gov.uk/wp-content/uploads/2021/03/Example-of-how-to-present-confidence-intervals.ods)

### Statistical significance

Note that the [credibility of assessing statistics using significance levels is currently under debate](https://www.nature.com/articles/d41586-019-00874-8).

If you are communicating statistical significance show where a change is statistically significant in a separate cell to the data. In terms of accessibility it is best to do this using words, for example: ‘Significant at 0.001 level’. You must also give the column or row holding the significance information a clear heading.  

If it is not possible to use words (for example, if it would take up too much room), you can use letters as shorthand (do not use symbols). To make this accessible you must also provide a key, above the table, in a cell in column A so the user sees this information before getting to the table. See the section on [Symbols, footnotes and codes](#symbols-footnotes-and-codes)' for more information. 

The asterisk symbol (*) has traditionally been used to communicate the level of statistical significance. Not all screen readers can understand the asterisk symbol and many disabled users can find them difficult to see and understand. Using them is likely to fail accessibility [guideline 3.1 readable](https://www.w3.org/TR/WCAG21/#readable). However, if you a creating a spreadsheet solely for machines to read it is OK to use the asterisk symbol, but you should still communicate what this means in a metadata file accompanying the spreadsheet. 

## Worksheets with multiple tables 

In general you should avoid publishing worksheets with multiple tables. These worksheets can be difficult to navigate and are bad pratice in terms of machine readability. However, if you have to do this there are a few points to bear in mind to meet accessibility [guideline 2.4 navigable](https://www.w3.org/TR/WCAG21/#navigable) and [success criterion 1.3.2 meaningful sequence](https://www.w3.org/TR/WCAG21/#meaningful-sequence).

### Worksheet titles when there are multiple tables
Pointers: 
* The worksheet title should be in cell A1
* The worksheet title should describe the data in the tables, for example ‘Number and percentage of population in each labour market activity group by age band, UK, seasonally adjusted’
* The worksheet title should be marked up as a Headings 1 using the ‘Cell Styles’ tool on the ‘Home’ ribbon. Find out more about marking up headings in the [Titles of spreadsheets, worksheets and tables](titles-of-spreadsheets-worksheets-and-tables) section of this guidance.  

Normally in large spreadsheets where worksheets are numbered instead of named, the title of each worksheet includes the table number, for example ‘Table 1: Number of people resident in each UK country’. When some worksheets have multiple tables, the worksheet titles cannot refer to specific tables. This means it is best to put the worksheet number in the title instead. For example: 
‘Worksheet 1: Number and percentage of population in each labour market activity group, UK, seasonally adjusted’
‘Worksheet 2: Number and percentage of population in each labour market activity group by age band, UK, seasonally adjusted’ 
and so on. 

### Table titles when there are multiple tables
Each table within the worksheet should have a unique title, for example ‘Table 2a: Number and percentage of people aged 16 and over in each labour market activity group’. 
It is best to have a clear numbering or labelling structure. For example linking the table numbers to the worksheet number, so all the tables on worksheet 2 are table 2a, table 2b, table 2c and so on. 

Each table’s title should be in the leftmost cell directly above the table.

Each table title should be marked up as a ‘Headings 2’ using the ‘Cell Styles’ tool on the ‘Home’ ribbon.

### Presentation in worksheets with multiple tables 
Cell A2 should describe the number of tables on the sheet and how they are presented, for example ‘This worksheet contains eight tables presented next to each other horizontally with one blank column in between each table. Each table applies to a different age group’.

Each table should be marked up and named (more information on this in the [Tables](#Tables) section). 

The first table on the worksheet should border the left hand edge of the worksheet.

Tables should be separated by a single blank row or column - large gaps between tables could be misunderstood by screen reader users.

## Macros, formulas and application code
We advise you to avoid publishing spreadsheets with macros in. It is difficult to ensure these meet the accessibility regulations and, in general, they are bad for machine readability. 

It is also best practice to remove formulas and any application code contained in your spreadsheet. Formulas and code can cause confusion and they can pose a security risk. 

If you have to include formulas or code, ensure they are hard coded to avoid accidental errors in use.

## Accessibility checker
Newer versions of Excel have a built-in accessibility checker. You can use this to see what issues it flags up. But remember it is a bit like using a spelling and grammar check. It is likely to miss some things and it may bring up things that are not relevant.  

For example, the checker will flag up tables that don’t have alt text. As long as your tables are marked up and named correctly you do not need to add this in. In any case, it will be removed if you save your spreadsheet in an Open Document Spreadsheet (ODS) format (which we recommend you do if the website you publish on supports this file type). 

To run the accessibility checker, go to the ‘Review’ ribbon and select ‘Check Accessibility’.

## Saving and publishing spreadsheets
Pointers for usability and accessibility: 
* Ensure the spreadsheet itself and all worksheets within it, open in a sensible place by placing the cursor in cell A1 on each of the worksheets before you save.
* Zoom should be set to 100% when you save your spreadsheet to ensure no enlargement or reduction is active.
* Avoid zip files as these can be blocked by organisational policies 

### Information to put on the webpage where the link to the spreadsheet lives
Ensure the webpage that houses the link to your spreadsheet contains a clear description of your data and has clear signposts to supporting information. This will help users find, understand and use your data.

The landing page for [Conception statistics, England and Wales](https://www.ons.gov.uk/peoplepopulationandcommunity/birthsdeathsandmarriages/conceptionandfertilityrates/datasets/conceptionstatisticsenglandandwalesreferencetables) is a good example of a webpage that hosts links to spreadsheets. It contains: 

* a summary of the data 
* contact details for the responsible statistician 
* a link to the publication that uses this data 
* links to methodology information
* a list of spreadsheets split by year 

Also, at the bottom of the page it has a section for 'Important notes and usage information' which contains related statistics, a user guide and links to statistics for other UK countries. 

You may repeat some of this information on the cover sheet of your spreadsheet. This is OK as people may find their way to your spreadsheet in different ways. Some may be sent the document directly, some may go to the webpage and download it from there. For more information on what to put in your cover sheet and how to format it, see the [Metadata worksheets](#metadata-worksheets) section. 

### File formats
Whenever possible you should publish your spreadsheet in an [open format](https://en.wikipedia.org/wiki/Open_format).

This is not explicitly mentioned in the accessibility regulations, but generally, open formats make outputs more accessible because they do not rely on users having access to specific software.

Furthermore, in June 2012, the [Government Open Data White Paper](https://www.gov.uk/government/publications/open-data-white-paper-unleashing-the-potential) set out a vision for open data that outlined a ranking scheme from 1 to 5 stars. Government data releases should meet the 3 star measure as a minimum. This means data should be made available in an open, non-proprietary format.

Spreadsheet files published in Excel format (such as .xls and .xlsx) are not open because they rely on users having access to specific software.

#### ODS format
For spreadsheets you intend users to read and analyse themselves we advise you use the Open Document Spreadsheet (ODS) format. This is an open format very similar to Excel. 

When you save as an ODS file, Excel will bring up a box to warn you that some features of your spreadsheet may not be compatible with the ODS format. If you want to know more, Microsoft have published [information about Excel features that are and aren’t compatible with the ODS format](https://support.microsoft.com/en-us/office/differences-between-the-opendocument-spreadsheet-ods-format-and-the-excel-for-windows-xlsx-format-3db958c8-e0ac-49a5-9965-2c2f8afbd960?ns=excel&version=90&syslcid=1033&uilcid=1033&appver=zxl900&helpid=191589&ui=en-us&rs=en-us&ad=us).  

Make sure you are aware of the formats the website you publish on allows you to upload. Some websites do not yet support the ODS format. However, GOV.UK does support the ODS format and the Government Digital Service recommends it. 

#### CSV format
The other commonly used open format is Comma-Separated-Values (CSV). 

If you are publishing a CSV file that you intend users to read and analyse themselves, it must meet the accessibility regulations. It can be a bit tricky to do this with CSV files as they only allow one tab and will strip out almost all formatting (such as table tags, headings tags and hyperlinks). If you have a very simple spreadsheet it may be possible to make a CSV version meet the accessibility regulations, but for anything slightly complex, we advise you to use a different format.  

If you are publishing a CSV file solely for machines to read it does not need to meet the accessibility regulations. CSV is the recommended format for spreadsheets optimised for machine readability. 

You should be aware of government data standards that may relate to your CSV files. The [tabular data standard](https://www.gov.uk/government/publications/recommended-open-standards-for-government/tabular-data-standard) published by the Government Digital Service in June 2018 was updated in August 2020. 

### Publishing alternative versions of same spreadsheet

If you need to, you can publish alternative versions of the same document. As long as one of them meets the accessibility regulations you are meeting the requirements of the accessibility legislation. 

For example, you may want to publish an accessible ODS version of your spreadsheet for users to read themselves, alongside a machine-readable CSV version. 

### Software capability 

In terms of usability, you should be aware that different spreadsheet tools and software have different capabilities for how they handle data. Check the specifications of your software, particularly around row and column limits, to make sure you are using an appropriate tool. 

For example, older versions of Excel (97-2003) have a row limit of 65,000 rows. You can read more about [Excel specifications and limits](https://support.microsoft.com/en-us/office/excel-specifications-and-limits-1672b34d-7043-467e-8e27-269d656771c3) if you need to. 

If the spreadsheet tool you use cannot hold all your data then you are likely to lose information, which can distort statistics and conclusions.

### File names
In terms of usability it is best practice for file names to:
* be unique, for example don’t call all your data downloads ‘Data download’
* be descriptive and make sense out of context – for example, tell the user what is in a data download, don’t just call it ‘Data download 1’
* be [frontloaded](https://digitalcommunications.wp.st-andrews.ac.uk/2017/03/15/web-writing-basics-frontloading/)
* be short – aim for 60 characters including spaces
* not include acronyms – put these in the document information as keywords or tags
* be entirely lowercase
* [use dashes instead of spaces or underscores between words](https://x-equals.com/dashes-versus-underscores/) – this makes file names easier to read, for example: ‘a file name.ods’ will end up as: ‘a%20file%20name.ods’ online, which is why it is better to call it  ‘a-file-name.ods’
* not include a date, unless the date is part of the document title, for example, ‘Business-plan-for-2016-to-2017’
* be sensible – do not include a version number, names or words like ‘draft’, ‘clean’ or ‘final’, unless those words are part of the document title (for example: ‘guidance-on-making-documents-accessible’ is a more sensible file name than ‘access-guid-final-draft-Han-edit3’)

In terms of accessibility there isn’t a specific success criterion for file names but following this best practice will help you meet accessibility [guideline 3.1 readable](https://www.w3.org/TR/WCAG21/#readable) and [3.2 predictable](https://www.w3.org/TR/WCAG21/#predictable).


## Sources for this guidance

* [Royal National Institute for the Blind spreadsheet guidance (doc, 191KB)](https://www.rnib.org.uk/sites/default/files/Creating%20accessible%20Excel%20spreadsheets.docx)
* [Microsoft guidance](https://support.microsoft.com/en-us/office/make-your-excel-documents-accessible-to-people-with-disabilities-6cc05fc5-1314-48b5-8eb3-683e49b3e593?ui=en-us&rs=en-us&ad=us#bkmk_wintableheaders)
* [Microsoft video guidance](https://support.microsoft.com/en-us/office/video-create-more-accessible-tables-in-excel-86e50f77-0f15-4537-ab1d-62d0e4cd5645)
* [SiteImprove guidance](https://siteimprove.com/en-us/blog/are-your-excel-spreadsheets-accessible/)
* [Guidance from Michigan State University](https://webaccess.msu.edu/Tutorials/excel.html)
* [Welsh Government guidance](https://gov.wales/how-create-accessible-excel-spreadsheets)
* [Information on making tables accessible from Government Digital Service](https://www.gov.uk/guidance/content-design/tables)
* [Making analytical publications accessible (Government Statistical Service guidance)](https://gss.civilservice.gov.uk/policy-store/making-analytical-publications-accessible/)
* Guidance shared with me by the Northern Irelands Statistics and Research Agency (Nisra)
* [Feedback from the Digital Accessibility Centre (DAC)](https://digitalaccessibilitycentre.org/)




