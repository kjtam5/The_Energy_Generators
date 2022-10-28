# The_Energy_Generators
Group Project Repo for BUS235A

- The link to your data set

https://www.kaggle.com/datasets/kevinmorgado/us-energy-generation-2001-2022


- The code that you used to load your data into R

  energy <- read_csv("organised_Gen.csv")


- A bullet-point list or table with an entry for each column in your data. For each column, explain in plain English what the data in the column represents (including units, if it is a numeric column).


  # : Row count (numeric) per year
  YEAR : Year (Numeric) energy was generated
  MONTH : Month (Numeric 2001-2022) energy was generated
  STATE : US State (abbreviated) energy was generated
  TYPE OF PRODUCER : List of types of energy producers
  ENERGY SOURCE : List of energy sources
  GENERATION (megawatthours) : Energy generated in megawatthours (Numeric)




- The output of running a skim() on your data.

```{r}
skim(energy)
```
── Data Summary ────────────────────────
                           Values
Name                       energy
Number of rows             496774
Number of columns          7     
_______________________          
Column type frequency:           
  character                3     
  numeric                  4     
________________________         
Group variables            None  





- A discussion of the skim output. Do the values seem reasonable or are there some that aren't what you expected or that don't make sense?





- Any code that you used to check and clean up your data after loading it, such as checking the types of the columns, converting data to the proper type if needed, naming columns, etc.




- A discussion of any problems that you encountered during the loading, checking, and cleaning process. Include how you handled any problems and what problems are unresolved.



