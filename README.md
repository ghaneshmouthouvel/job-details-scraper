# job-details-scraper

### PageExtracter.py
Regarding to this program , It extracts the content from the **parsed data** .
It returns the field entities like **jobtitle** , **institution name** , **location** , **jobtype** , **salary** , **summary** , **posted on** , **key term data** .
 
### MergeData.py
The program just merges all `.xlsx` files in **datasets folder** and remove duplication of records and export it as `mergedata.xlsx`.

### WordFrequency.py
The program is basically designed to find the **word count** of the **summary field** in the extracted data and export it as `wordfrequency.xlsx` file with fields **words**, **count**, **per-word**, **post-word**.
