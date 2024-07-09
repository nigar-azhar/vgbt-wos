# vgbt-wos
This repository contains the data from our Web of Science query execution and the subsequent filtering process used in context of game bug taxonomy paper. The goal was to determine the relevance and uniqueness of articles retrieved from the Web of Science database in comparison to other included databases [1].

## Summary of Results

The query executed on the Web of Science yielded a total of 324 results. The data filtering process resulted in the following:

- **Total Duplicates:** 20
- **Relevant Duplicates:** 6
- **Unique Relevant Articles:** 0
- **Irrelevant Articles:** 304
- **Total:** 324

## Files Included

- **wos-query-results.xls:** 
  - Contains the initial search results from Web of Science.

- **wos-filtering-process.csv:**
  - Shows data for applying inclusion and exclusion criteria.
  - **Relevant Column:** 
    - **duplicate-yes:** Duplicate with an existing relevant article.
    - **duplicate-no:** Duplicate with an existing irrelevant article.
    - **no:** Not relevant.
    - **yes:** Relevant.
  - **Reason Column:** Provides the focus of the paper if not relevant, highlighting the basis for exclusion.

## Purpose

- This repository provides a comprehensive overview of the Web of Science query and highlights the overlap with other academic databases.


## Conclusion

- The inclusion of Web of Science in our systematic review did not yield any unique relevant articles that were not already identified in other databases.

[1] N. A. Butt, S. Sherin, A. A. Jilani, M. U. Khan, and M. Z. Iqbal, Data for Deriving and Evaluating a Detailed Taxonomy of Game Bugs, version 2.0.0, Oct. 2023. doi: 10.5281/zenodo.8425685. [Online].

