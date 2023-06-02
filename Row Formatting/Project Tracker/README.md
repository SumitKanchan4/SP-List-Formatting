# Project Tracker
-----

## Summary
----

Though we have got lot of tools to track the project, but still many don't want to go for any paid tool and want to record in SharePoint as it is easy, convinient and user friendly. 

This Project tracker is to help understand the current status of the project along with other details like, estimation, business users, technical team involved etc...

## Features
 - "Comments" is made the inline-editable. So you now don't have to edit the item and find the field.
 - View all the technical team involved with respective roles. If left blank then it does not pops up
 - View all the business stakeholders, with highlighting primary business for contacts.
 - Status color to identify the Project Status without looking into the values


__NOTE__ : For implementation of Project Folder, update the Library name in the json file and create the folder with the name as Title of the project. (ref - line 99 in json file)

![Issue tracking row formatter](./ProjectTracking.gif)

 
## View requirements

Following columns will be required in the list and in the view

| Column Name              | Column Type               |
| ------------------------ | ------------------------- |
| Title                    | Single line of text       |
| ProjectStatus            | Choice                    |
| ProjectedStartDate       | DateTime                  |
| ResourceCount            | Number                    |
| Comments                 | Multiple lines of text    |
| EstimatedEfforts         | Number                    |
| TechnicalArchitect       | Person (Single Selection) |
| BA                       | Person (Single Selection) |
| Developers               | Person (Multi Selection)  |
| Tester                   | Person (Multi Selection)  |
| PrimaryBusinessOwner     | Person (Single Selection) |
| OtherBusinessStakeholder | Person (Multi Selection)  |

- ProjectStatus: `Initiated`, `Proposal - In Progress`, `Proposal - Submitted`, `Proposal - Approved` ,`Development - In Progress`,`Development - Completed`,`UAT - In Progress`,`UAT - Completed`,`Deployment - In Progress`,`Completed`

## About

| Version | Date         | Author        |
| ------- | ------------ | ------------- |
| 1.0     | 02 June 2023 | Sumit Kanchan |

## Disclaimer

THIS CODE IS PROVIDED AS IS WITHOUT WARRANTY OF ANY KIND, EITHER EXPRESS OR IMPLIED, INCLUDING ANY IMPLIED WARRANTIES OF FITNESS FOR A PARTICULAR PURPOSE, MERCHANTABILITY, OR NON-INFRINGEMENT.
