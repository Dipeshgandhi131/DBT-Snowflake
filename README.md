# DBT-Snowflake
This is repo for exploring DBT with snowflake

| CheckName           | CheckOnColumn   | Outcome   |   CurrentValue | PassRule            | Severity   |
|:--------------------|:----------------|:----------|---------------:|:--------------------|:-----------|
| max_loan_term_check | loanTerm        | FAIL      |             60 | max(loanTerm) <= 10 | high       |
