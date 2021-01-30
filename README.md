# osu-bootcamp-homework-1

## Summary 
For this assignment I refactored the code and improved the accessibility. Both the html and CSS files were refactored. Before the accessibility was improved only `<div>` was being used instead of any semantic html. I also consolidated multiple blocks of CSS into single blocks. 

For example:

`.benefit-lead {
    margin-bottom: 32px;
    color: #ffffff;
}`

`.benefit-brand {
    margin-bottom: 32px;
    color: #ffffff;
}`

`.benefit-cost {
    margin-bottom: 32px;
    color: #ffffff;`

Was consolidated into:

`.benefit-lead, .benefit-brand, .benefit-cost { 
      margin-bottom: 32px;      
      color: #ffffff;      
}`    

## List of Corrections to Code
- Added name to `<title>`
- Added id tag to `<section>` "search-engine-optimization" to resolve link from `<nav>` bar
- Consolidated multiple duplicated lines in CSS into single line 
- Added semantic html throughout 
- Added alt tags to images 
- Removed unnecessary `/img>` closing tag on `<img src="./assets/images/cost-management.png" alt=""/>`
- Added comments to the more complex CSS blocks 
