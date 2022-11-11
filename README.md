# Git log analysis with Python and PySpark

## How to use

There are 2 ways run these program: on Colab or local
I recommend to use Colab

|              | Run on Colab            | Run on local      |
| ------------ | ----------------------- | ----------------- |
| Prerequisite | Nope                    | PySpark installed |
| Download     | No need, use this link: |                   |

---

## Contents

1. Gathering the data:
   1. Clone git respository
   2. Create git log
   3. Understand features of data
2. Data cleaning
3. Interpreting the data
   1. Q. Who has the most commit in 2021?
   2. Q. Last commit that change the file "nbdime/webapp/templates/difftool.html"?

---

## Features

| Column name  | Note                                                             |
| ------------ | ---------------------------------------------------------------- |
| Id           | Abbreviated commit hash                                          |
| ParentIds    | Abbreviated parent hashes                                        |
| AuthorName   |                                                                  |
| AuthorEmail  |                                                                  |
| AuthorDate   |                                                                  |
| Subject      |                                                                  |
| ChangedFiles | If there are many changes, the files will be separated by commas |
