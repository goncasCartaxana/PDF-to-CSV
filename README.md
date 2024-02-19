# PDF-to-CSV
## What does it do?
Self-evidently, is converts PDFs into CSVs.

Found the solution here:
https://stackoverflow.com/questions/58690461/how-to-convert-pdf-file-to-excel-file-using-python
Now just want to add extra features to make it friendly to use.



### I'll be using existing Libraries: 
- tabula-py: Extracts tables from PDF files
- pandas: Data manipulation
* (Its meant to be used in PDFs that have tables, otherwise might not work (or make sense to use))


### How can i improve it?
- Choosing which page is turning into a csv file.
- Batch Processing:: Automating the conversion of multiple PDF files.(by providing a directory as input )
- Error Handling: provide info messages with issues such as: missing input files, invalid page numbers, or failed conversions.
- Documentation: With examples and troubleshooting tips.
- Customizable Output: Allow users to to customize the output according to their needs. Such as:
    - delimiter: to separate individual fields. Common ones are: commas (,), semicolons (;), tabs (\t), or pipes (|).
    -  encoding: Different encodings support different sets of characters. ???
    -  Header/footer exclusion: Exclude the name of columns
    -  Column removal: maybe certain columns are not desirable in the output.
    -  costum header names: We can change the names of the variables to ones that make more sense.

## Why I created this Project?
I wanted to manage my spendings and plan my financial life as a responsible indiviudal.
My bank has the possibility of retrieving PDFs of previous months (indefinitely).
So I wanted to check how much money I spent and in what.
That requires labeling it, manually, but thats manageable.
What wasn't manageable was copying all the transactions... 
That's when i looked for libraries to solve this. I FOUND tabula-py !!!
Now I just wanted to make it easy to use.
