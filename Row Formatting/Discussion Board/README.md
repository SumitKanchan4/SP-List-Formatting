# Discussion Board : Row Formatting
-----

## Summary
----

A simple discussion board row formatting using the Site Pages library. It will give the experince of some discussion board with all the pages categorised. No new column needs to be added, only the existing columns needs to be added to the default view.

Please run this PnP powershell, before adding the json to the list 
```powershell
Add-PnPView -List "Site Pages" -Title "Discussion Board" -Fields "Modified","_CommentCount","Description","ID","_LikeCount","BannerImageUrl","_AuthorByline","Title"
```
After the view is created or the columns are added in the existing view, make the view as default

![Discussion Board Row View Formatter](./DiscussionBoard.gif)
 
## View requirements

Following columns will be required in the view

| Column Name    | Column Type            |
|----------------|------------------------|
| Title          | Single line of text    |
| _LikeCount     | Lookup                 |
| _AuthorByline  | Person                 |
| BannerImageUrl | Single line of text    |
| Description    | Multiple lines of text |
| _CommentCount  | Lookup                 |
| Modified       | DateTime               |


## About

| Version | Date | Author|
|-----|-----|-----|
|1.0|08 July 2020 | Sumit Kanchan |

## Disclaimer

THIS CODE IS PROVIDED AS IS WITHOUT WARRANTY OF ANY KIND, EITHER EXPRESS OR IMPLIED, INCLUDING ANY IMPLIED WARRANTIES OF FITNESS FOR A PARTICULAR PURPOSE, MERCHANTABILITY, OR NON-INFRINGEMENT.
