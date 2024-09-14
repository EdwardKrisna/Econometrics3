# Pension Planning Analysis

This project analyzes retirement planning behaviors using the `PENSION.DTA` dataset. The dataset provides a comprehensive view of individuals' pension participation, financial status, and demographic characteristics.

## Key Variables

The key variables analyzed in this study include:

- **Years in pension plan (`pyears`)**: The number of years the individual has been in a pension plan.
- **Participation in profit-sharing plans (`prftshr`)**: A binary variable indicating whether the individual is part of a profit-sharing plan.
- **Investment choice flexibility (`choice`)**: A binary variable indicating whether the individual can choose their investment method.
- **Demographic factors**: Includes gender (`female`), marital status (`married`), age, education level (`educ`), and race (`black`).
- **Financial indicators**: Family income brackets for 1992 (`finc25` to `finc101`), net worth in 1989 (`wealth89`).
- **Investment behaviors**: Stock ownership (`stckin89`), IRA ownership (`irain89`), and asset allocation (`pctstck`).

## Objective

The study aims to understand how these factors influence pension plan participation and retirement planning decisions. Various statistical methods will be employed to explore the data, identify significant patterns, and uncover correlations between the variables.

## Dataset Overview

| Attribute  | Description                                                                                      |
|------------|--------------------------------------------------------------------------------------------------|
| `id`       | A unique identifier for each family in the dataset.                                               |
| `pyears`   | The number of years the individual has been in a pension plan.                                    |
| `prftshr`  | A dummy variable that equals 1 if the individual is part of a profit-sharing plan, and 0 otherwise.|
| `choice`   | A dummy variable that equals 1 if the individual can choose their investment method, and 0 otherwise.|
| `female`   | A dummy variable that equals 1 if the individual is female, and 0 if male.                        |
| `married`  | A dummy variable that equals 1 if the individual is married, and 0 otherwise.                     |
| `age`      | The age of the individual, measured in years.                                                     |
| `educ`     | The highest grade completed by the individual, representing their education level.                |
| `finc25`   | Equals 1 if family income in 1992 was between $15,000 and $25,000, 0 otherwise.                   |
| `finc35`   | Equals 1 if family income in 1992 was between $25,000 and $35,000, 0 otherwise.                   |
| `finc50`   | Equals 1 if family income in 1992 was between $35,000 and $50,000, 0 otherwise.                   |
| `finc75`   | Equals 1 if family income in 1992 was between $50,000 and $75,000, 0 otherwise.                   |
| `finc100`  | Equals 1 if family income in 1992 was between $75,000 and $100,000, 0 otherwise.                  |
| `finc101`  | Equals 1 if family income in 1992 was over $100,000, 0 otherwise.                                 |
| `wealth89` | The net worth of the individual or family in 1989, measured in thousands of dollars.              |
| `black`    | A dummy variable that equals 1 if the individual is Black, and 0 otherwise.                       |
| `stckin89` | A dummy variable that equals 1 if the individual owned stock in 1989, and 0 otherwise.            |
| `irain89`  | A dummy variable that equals 1 if the individual had an Individual Retirement Account (IRA) in 1989, and 0 otherwise. |
| `pctstck`  | Asset allocation categories: **0** (All assets in bonds), **50** (Mixed allocation), **100** (All assets in stocks). |
