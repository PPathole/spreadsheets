# spreadsheets

- Conditional Formatting
- Data Validation
- Finding Nulls: =ISBLANK(), or =COUNTBLANKS()
- Data Duplicates
- Descriptive Statistics: =AVERAGE(), MAX(), MIN(), MODE(), MEDIAN(), CORREL(), Using the Data Analysis ToolPak to find descriptive Statistics
- Pivot Tables: To analyse data and find insights
- Pivot Charts
- Text Functions: =CONCAT(), =TEXTJOIN(), =LEFT(), =MID(), =RIGHT(), Text Splitting
- Lookups: =VLOOKUP(lookup_value, array, col_index, FALSE-for exact match, TRUE-for approximate match)
  - VLOOKUP goes from LEFT to RIGHT, and if a new column is introduced then the col_index param changes and the lookup function breaks
  - XLOOKUP(lookup_value, lookup_array, return_array, "Not in the list", 0-Exact Match)
  - XLOOKUP solves the limitations of VLOOKUP and is more efficient and is also referred to as VLOOKUP on steroids
  - INDEX MATCH - INDEX(array_to_be_returned, MATCH(lookup_value, lookup_array, 0 - exact Match))
- IF/IFS - =IF(condition, true, false)
- IFS - multiple conditions, AND()/OR()
- SUMIF/SUMIFS: =SUMIF(sum_range, criteria)
- COUNTIF()
- AVERAGEIF()
