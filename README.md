# Download Tarrant County Medical Examiners' Death Data

Written to support a small project requiring validation of deaths
from the Medical Examiners' Office.  
  
The ipython notebook includes a function that use Selenium (python) to download tabular death data (CSV) reported within
a specified date range from the Tarrant County Medical Examiners' Office. Some of the fields in these tables may contain
commas (,) which throw off attempts to auto-parse the files into pandas dataframes. The notebook also contains an example
"on_bad_lines" function for the pandas.read_csv() function to aid in parsing the files.