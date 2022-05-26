# R4DS Advanced R Book Club

Welcome to the R4DS Advanced R Book Club!

We are working together to read [_Advanced R_](https://adv-r.hadley.nz/) by Hadley Wickham (Chapman & Hall, copyright 2019, [9780815384571](https://www.routledge.com/Advanced-R-Second-Edition/Wickham/p/book/9780815384571)).
Join the #book_club-advr channel on the [R4DS Slack](https://r4ds.io/join) to participate.
As we read, we are producing [notes about the book](https://r4ds.io/advr).

## Meeting Schedule

If you would like to present, please add your name next to a chapter using the [GitHub Web Editor](https://youtu.be/d41oc2OMAuI)!

*Cohort 6: Wednesdays, 13:00 CST/CDT*

<details>
  <summary> Past Meetings </summary>
  (none yet)
</details>

- 2022-05-25: Chapter 1 (Introduction) - Federica Gazzelloni

**Foundations**

- 2022-06-01: Chapter 2 (Names and values) - Lucus Wassira
- 2022-06-08: Chapter 3 (Vectors) - Presenter TBD
- 2022-06-15: Chapter 4 (Subsetting) - Presenter TBD
- 2022-06-22: Chapter 5(Control flow) - Presenter TBD
- 2022-06-29: Chapter 6 (Functions) - Presenter TBD
- 2022-07-06: Chapter 7 (Environments) - Presenter TBD
- 2022-07-13: Chapter 8 (Conditions) - Presenter TBD

**Functional programming**

- 2022-07-20: Chapter 9 (Functionals) - Presenter TBD
- 2022-07-27: NO MEETING
- 2022-08-03: Chapter 10 (Function factories) - Presenter TBD
- 2022-08-10: Chapter 11 (Function operators) - Presenter TBD

**Object-oriented programming**

- 2022-08-17: Chapter 12 (Base types) - Presenter TBD
- 2022-08-24: Chapter 13 (S3) - Presenter TBD
- 2022-08-31: Chapter 14 (R6) - Presenter TBD
- 2022-09-07: Chapter 15 (S4) - Presenter TBD
- 2022-09-14: Chapter 16 (Trade-offs) - Presenter TBD

**Metaprogramming**

- 2022-09-21: Chapter 17 (Big picture) - Presenter TBD
- 2022-09-28: Chapter 18 (Expressions) - Presenter TBD
- 2022-10-05: Chapter 19 (Quasiquotation) - Presenter TBD
- 2022-10-12: Chapter 20 (Evaluation) - Presenter TBD
- 2022-10-19: Chapter 21 (Translating R code) - Presenter TBD

**Techniques**

- 2022-10-26: Chapter 22 (Debugging) - Presenter TBD
- 2022-11-02: Chapter 23 (Measuring performance) - Presenter TBD
- 2022-11-09: Chapter 24 (Improving performance) - Presenter TBD
- 2022-11-16: Chapter 25 (Rewriting R code in C++) - Presenter TBD

[Previous cohorts](https://github.com/r4ds/bookclub-Advanced_R).

<hr>


## How to Present

This repository is structured as a [{bookdown}](https://CRAN.R-project.org/package=bookdown) site.
To present, follow these instructions:

1. [Setup Github Locally](https://www.youtube.com/watch?v=hNUNPkoledI) (also see [_HappyHappy Git and GitHub for the useR_](https://happygitwithr.com/github-acct.html))
2. Install {usethis} `install.packages("usethis")`
3. `usethis::create_from_github("r4ds/bookclub-advr")` (cleanly creates your own copy of this repository).
4. `usethis::pr_init("my-chapter")` (creates a branch for your work, to avoid confusion).
5. Edit the appropriate chapter file, if necessary. Use `##` to indicate new slides (new sections).
7. If you use any packages that are not already in the `DESCRIPTION`, add them. You can use `usethis::use_package("myCoolPackage")` to add them quickly!
8. Build the book! ctrl-shift-b (or command-shift-b) will render the full book, or ctrl-shift-k (command-shift-k) to render just your slide. Please do this to make sure it works before you push your changes up to the main repo!
9. Commit your changes (either through the command line or using Rstudio's Git tab).
10. `usethis::pr_push()` (pushes the changes up to github, and opens a "pull request" (PR) to let us know your work is ready).
11. (If we request changes, make them)
12. When your PR has been accepted ("merged"), `usethis::pr_finish()` to close out your branch and prepare your local repository for future work.

When your PR is checked into the main branch, the bookdown site will rebuild, adding your slides to [this site](https://r4ds.io/advr).
