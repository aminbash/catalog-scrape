# Catalog-scrape



## Author
```
Amin Karabash
```
### Program Description
This python script scrapes UTEP's course catalog webpage using a word bank.
From each course that is output, it extracts five fields: 
```
- CRN
- Class Title
- Course Description
- Department
- Prerequisite
```
These five fields are transformed into a dataframe, manipulated (sorted and duplicates removed), and converted to a .csv file.
