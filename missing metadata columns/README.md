### Find and add missing/deleted metadata columns in Nuxeo metadata TSV files.

*Requires Python 3 and pandas*

1. Add "columns.txt" file to the directory with your TSV files
2. Run "nuxeo_headers.py": `python3 nuxeo_headers.py`
3. This will prompt for the path to the **directory** with the TSV and columns.txt files
4. That's it! It should print any columns that were missing and added.
