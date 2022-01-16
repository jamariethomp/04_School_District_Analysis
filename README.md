# School District Analysis

## Overview of School District Data

The Chief Data Scientist at a local school district has tasked me with assisting her in determining insights provided by standardized test scores; namely, how size, funding, and school type affect the outcome of standardized test scores. This analysis will assist the school board and superintendent in making decisions regarding the schools budgets and priorities.

## Results

The orginial dataset provided offered some key insights about how spending per student, size, and school type affect the outcomes of standardized test scores. It was initially found that higher scores are associated with less spending, smaller size, and charter type schools:

*Performance by spending prior to changes:*
![budget data 1](https://user-images.githubusercontent.com/94264643/149648018-2f070975-c62b-470b-85e5-4ea1341419e7.png)

*Performance by size prior to changes:*
![size data 1](https://user-images.githubusercontent.com/94264643/149648020-54673b98-d2e6-418b-a99a-8787f65fbd5b.png)

*Performance by type prior to changes:*
![type data 1](https://user-images.githubusercontent.com/94264643/149648026-a53d9e0b-de72-47e7-8890-e2b39d6796e0.png)


After an inital pass through the dataset, the school board identified potential academic dishonesty affecting the reading and math scores of 9th grade students at Thomas High School; to maintain the integrity of the dataset, reading and math scores of 9th graders at Thomas High School were removed and the analysis was recalibrated.

The change in data affected several key elements of the analysis:

-**The overall summary of district data was minimally affected:**

*Performance of whole district prior to changes:*
![district summary 1](https://user-images.githubusercontent.com/94264643/149648994-ae157395-b857-47f8-87d4-56ed8f623823.png)

*Performance of whole district after changes:*
![district summary 2](https://user-images.githubusercontent.com/94264643/149648124-506ce538-e219-44e6-a55b-ddc9a7028623.png)


-In the per schoool summary, it is clear that reading and math scores at Thomas High School decreased, though within a percentage point for each:

*Performance of math and reading scores at Thomas High School prior to changes:*
![thomas high school 1](https://user-images.githubusercontent.com/94264643/149648360-aea2be36-69dd-4a95-8bea-d65d8c93b5d4.png)

*Performance of math and reading scores at Thomas High School after changes:*
![thomas high school 2](https://user-images.githubusercontent.com/94264643/149648363-32df7ee8-5ba9-42ba-b2fc-0bb64be5c2ce.png)

-**Thomas High School maintains it's standing of having the second highest reading and math scores in the district, even after removing potentially inflated 9th grade scores.**

-Removing the ninth-grade scores also affects the following metrics:

--**Math and reading scores by grade:** By grade, only 9th grade reading and math scores at Thomas High School were removed. No other metrics were affected.

--**Scores by school spending:** The percentage of overall passing scores decreased by a tenth of a percentage point:
*Performance by spending after changes:*
![budget data 2](https://user-images.githubusercontent.com/94264643/149648677-3fe12019-d76d-4fc9-8cb4-ac56f9b462e9.png)

--**Scores by school size:** Scores by school size were not affected by the change:
*Performance by size after changes:*
![size data 2](https://user-images.githubusercontent.com/94264643/149648756-4c13982d-fc5e-4620-a7b0-9774ff300e52.png)

--**Scores by school type:** Scores by school type were not affected by the change:
*Performance by type after changes:*
![type data 2](https://user-images.githubusercontent.com/94264643/149648796-996bf226-a2df-42a1-94d5-dca99a378673.png)

## Summary

While the removed data clearly results in a decrease in overall performance, there is no evidence that any widespread academic dishonesty should affect the decision-making outcomes of the school board or district superintendent. The results still indicate that higher scores are associated with less spending, smaller size, and charter type schools.
