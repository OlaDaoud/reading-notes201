# Reading07 
## Domain modeling

* Since you'll be modeling the popularity of many types of videos—parkour epic fails, corgi epic fails, etc.—you'll want to build self-contained objects with the same attributes and behaviors.
* A model describes the various entities, their attributes and behaviors, as well as the constraints that govern the problem domain.
* Domain modeling is the process of creating a conceptual model in code for a specific problem.
* A domain model that's articulated well can verify and validate the understanding of a specific problem among various stakeholders.

### Define a constructor and initialize properties

Property  |	Data	|   Type
----------|--------|----------
epicRating |	1 to 10  |  	Number
hasAnimals |	true or false |	Boolean


## HTML - tables 

* The contents
of the table are written out row by row.

<table>
The <table> element is used
to create a table. 
<tr>
(table row.)
At the end of the row you use a closing </tr> tag.
<td>
It is followed by one or more <td> elements (one for each cell in that row).
 (The td stands for table data.)

#### (The <th> stands for table heading.) 
* Even if a cell has no content, you should still use a <th> or <td> element to represent the presence of an empty cell otherwise the table will not render correctly.
* Using elements for headings helps people who use screen readers, improves the ability for search engines to index your pages, and also enables you to control the appearance of tables better when you start to use CSS.

* When we need entries in a table to stretch across more than one column in the same row we can use The **colspan** attribute  on a <th> or <td> element 
* it indicates how many columns that cell should run across.

#### EX : 
<td colspan="2">Geography</td> 
this will extend to 2 cells in the same row 

 <td rowspan="2">Movie</td>
 this will extend to 2 rows in the same column 


## JavaScript - creating an object : constructor notation 
![](/mnt/c/Users/LTUC/Desktop/LTUC/201/reading-notes201/images/methods1.PNG)

