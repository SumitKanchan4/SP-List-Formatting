# Issue Tracking Row formatter
-----

## Summary
----

Simple 'Issue Tracking' view, with the focus to track the comments against each issue in a single view. This view helps in displaying all the required infromation in an efficient way. All the parameters are clickable and results in the filter of the value, like Subcategory, Status, Reported On, Assigned to, Reported By all these fields are clickable and on click it filters the list with that value.

> Currently it filters on the default view (AllItems.aspx), if implementing on custom view, need to update the values in the json file.

[![Issue Tracking Row View Formatter](/issue tracking row view.gif?raw=true "Issue Tracking Row View Formatter" )]()
 
## View requirements

Following columns will be required in the list and in the view

| Column Name      | Column Type            |
|------------------|------------------------|
| Title            | Single line of text    |
| Subcategory      | Choice                 |
| Shortdescription | Multiple lines of text |
| Status           | Choice                 |
| Owner            | Person                 |
| Comments         | Multiple lines of text |
| ReportedBy       | Person                 |


## Sample

| Version | Date | Author|
|-----|-----|-----|
|1.0|03 July 2020 | Sumit Kanchan |

## Disclaimer

THIS CODE IS PROVIDED AS IS WITHOUT WARRANTY OF ANY KIND, EITHER EXPRESS OR IMPLIED, INCLUDING ANY IMPLIED WARRANTIES OF FITNESS FOR A PARTICULAR PURPOSE, MERCHANTABILITY, OR NON-INFRINGEMENT.
