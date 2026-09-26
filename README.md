# Faculty Salaries Analysis

Python Analytics Class (LaGuardia) — Salaries dataset assignment.

I analyze the **Salaries** dataset (397 college professors: rank, discipline, years since PhD, years of service, sex, and salary) with pandas and matplotlib:

- **Data exploration** — `head()`, `info()`, `describe()`, mean vs. median salary, and median salary by sex, by rank, and by rank + sex
- **Data wrangling** — renaming the unnamed ID column and the dotted column names, checking for missing data, subsetting to the columns I need, and filtering rows
- **Data visualizations** — bar chart of median salary by rank, box plot of salary by sex, scatter plot of salary vs. years of service
- **Conclusions** — rank drives salary the most (median ≈ $79.8k → $95.6k → $123.3k), women are only 39 of 397 professors and earn $3k–$5k less at every rank, and years of service alone does not predict pay

📓 Notebook: [faculty_salaries_analysis.ipynb](faculty_salaries_analysis.ipynb)
