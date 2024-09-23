# Rice_repeats

Files oriza_rep_chr<n>.csv, where n=1,..,12 – chromosome number contain data on dispersed repeats in the Oryza sativa genome. Files have the delimited text format and can be exported to the internal format of spreadsheets and DBMS. The first line shows headers indicating the data structure. Each line contains data fields for one repeat separated by semicolons. The order of  fields:

family – repeats family number (from 1 to 79)
j0 – left coordinate of the repeat in the chromosome
jm – right coordinate of the repeat in the chromosome 
dir – DNA strand: forward (+) and reverse (-) strands
z – statistical significance
v1 – family profile sequence; the insertion corresponds to digit 0
v2 – aligned repeat sequence; insertions are marked by asterisks.
