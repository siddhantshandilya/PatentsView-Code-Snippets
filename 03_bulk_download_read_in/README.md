# PatentsView-Code-Snippets

# Bulk Download Files: Read-in Scripts

Due to changes in the structure of the Bulk Download files, the PatentsView team has created template scripts in Python and R which demonstrate how to read in these tsv files.

See the file format settings below:  
| Table            | File(s)                       | Data Contains Line Break | Field Separator | Quote Settings            | Quote Character |
|------------------|-------------------------------|--------------------------|-----------------|---------------------------|-----------------|
| claims           | Yearly files from 1976 - 2005 | No                       | \t              | Non Numeric Fields Quoted | "               |
| claims           | Yearly files from 2005 - 2020 | Yes                      | \t              | Non Numeric Fields Quoted | "               |
| brf_sum_text     | Single bulk file              | Yes                      | \t              | Non Numeric Fields Quoted | "               |
| detail_desc_text | 2020 data file                | Yes                      | \t              | Non Numeric Fields Quoted | "               |
| detail_desc_text | 2019 data file                | No                       | \t              | Non Numeric Fields Quoted | "               |
| detail_desc_text | Yearly files from 1976 - 2018 | No                       | \t              | Unquoted                  | N/A             |
| draw_desc_text   | Single bulk file              | No                       | \t              | Non Numeric Fields Quoted | "               |
| all other tables | Single bulk file              | No                       | \t              | Non Numeric Fields Quoted | "               |