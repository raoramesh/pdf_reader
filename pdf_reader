# pdf table to xl
# Import Module
import tabula
import openpyxl
import pandas as pd

df = tabula.read_pdf("/home/username/Downloads/Jan2021.pdf", pages = "all")
tabula.convert_into("/home/username/Downloads/Report_JAN2021.pdf", "/home/usernames/Downloads/ReportJan21.xlsx", output_format="xls", pages='all')

from tabula import read_pdf
from tabulate import tabulate

#reads table from pdf file
df = read_pdf("/home/username/Downloads/Jan2021.pdf",pages="all") #address of pdf file
print(tabulate(df))
