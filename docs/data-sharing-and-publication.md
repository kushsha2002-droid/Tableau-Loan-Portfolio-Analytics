# Data sharing and publication check

The Tableau `.twbx` files embed `Loan_Cleaned_ISOM845.xlsx`, containing 42,535 loan-level records and fields such as `Company_name`, `Emp_ID`, `Annual_income`, financial amounts, credit metrics, and loan status. Assignment 6 also includes a third-party image embedded inside its packaged workbook. We cannot verify dataset licensing, privacy clearance, or image redistribution permissions from these files alone.

**Recommended approach**

1. Put the **full** repository in **Private** visibility while reviewing rights.
2. Ask the course instructor or original data publisher whether you may redistribute the loan dataset and bundled imagery in a public portfolio.
3. If not approved, publish the public-safe version with authorized dashboard screenshots and high-level, non-identifying summaries only.
4. Do not rely on `.gitignore` or deleting a file in a later commit to protect data already published: Git history may retain it.
5. If you later approve public publication, you can create a fresh public repository from the safe version to avoid exposing private history.

We have **not** asserted that this loan-level dataset is free for redistribution.
