# about the project:
In this project, we'll work with data from the CIA World Factbook. we'll use SQL in Jupyter Notebook to explore and analyze data from this database. to access sql in Jupyter Notebook you have to install the 'ipyhton-sql' in conda and connect the notebook to our DB file 'factbook.db' by code:
<tr>
<td>
%%capture
</td>
<td>%load_ext sql
</td>
<td>%sql sqlite:///factbook.db
</td>
</tr>

-- we shall find the abnormal data in db
-- we shall find the most dense countries

# about the dataset:
The Factbook.db contains demographic information like:

population - The population as of 2015.
population_growth - The annual population growth rate, as a percentage.
area - The total land and water area.

## find more info in ipynb.