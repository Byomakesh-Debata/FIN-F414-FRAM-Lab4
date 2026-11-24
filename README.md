# Lab 4 (Optional): Building a Credit Rating

## Overview

In this optional lab, you will attempt to assign and justify a credit rating for a company of your choice using publicly available information. The exercise explores how quantitative models and qualitative judgement can be combined to assess creditworthiness.

Sections 1 to 4 provide the background for the exercise, while Section 5 presents the problem statement. There is no prescribed format, and the lab will not be graded.

**Note on sources.** The sources linked in this lab are indicative starting points only. They are neither exhaustive nor prescriptive, and you are encouraged to explore other relevant sources.

## 1. Altman's Z-score models

Read [Altman, Iwanicz-Drozdowska, Laitinen and Suvas (2017), *Financial Distress Prediction in an International Context: A Review and Empirical Analysis of Altman's Z-Score Model*](https://doi.org/10.1111/jifm.12053). The paper reviews the development of the Z-score model since its introduction in 1968.

The aim is to understand the different variants of the Z-score model, their applicability and limitations, rather than the detailed empirical results of the paper. Consider the following:

- How do the Z, Z' and Z'' models differ, and under what circumstances is each appropriate?
- Which variables differ between the models, and why?
- What are the limitations of applying these models across countries, industries and time periods?
- Can the Z-score be used directly to assign a credit rating? What aspects of credit risk might it fail to capture?

## 2. The credit rating process

A credit rating is an opinion on the creditworthiness of an issuer or a financial obligation. Unlike the Z-score, a credit rating is not the output of a single formula. It involves an assessment of financial risk, business risk and other relevant factors using both quantitative evidence and qualitative judgement.

Review how one or more agencies describe their ratings and the process behind them, for example [S&P Global](https://www.spglobal.com/ratings/en/credit-ratings/about/understanding-credit-ratings), [ICRA](https://www.icra.in/Rating/Methodology?Page=GuideToCreditRatings) or [CRISIL](https://www.crisilratings.com/en/home/our-business/ratings/understanding-rating.html). Consider the following:

- What does a credit rating convey, and what does it not convey?
- What is the difference between rating an issuer and rating a specific debt instrument?
- How is a rating assigned, and how is it monitored and revised over time?
- What information might rating agencies have access to beyond what is publicly available?

## 3. Point-in-time and through-the-cycle ratings

Credit risk assessments may focus on current economic conditions (point-in-time) or take a longer-term view across economic cycles (through-the-cycle). This choice affects how stable a rating is and how quickly it responds to new information.

Agencies also publish data on how their ratings have performed over time. [ICRA's rating performance page](https://www.icra.in/Rating/Methodology?Page=RatingPerformance), for example, includes transition and default studies. These studies help us understand how ratings change over time and how default rates vary across rating categories. Consider the following:

- What are the advantages and disadvantages of each approach, and for which users is each more suitable?
- Which approach do rating agencies generally follow, and how might this be reflected in their rating transition matrices?
- Does the behaviour of the Z-score more closely resemble a point-in-time or through-the-cycle assessment? Why?
- What can historical default rates across rating categories tell us about a rating system?

## 4. Rating rationales and methodologies

Agencies often publish a rationale with a rating. Reading a few of these shows how quantitative and qualitative factors are combined in practice. Published rationales are available through, for example, [ICRA's ratings coverage](https://www.icra.in/Rating#ratingscoverage) and [CRISIL's rating rationales](https://www.crisilratings.com/en/home/our-business/ratings/rating-rationale.html). It is useful to compare companies from the same industry that hold different ratings.

Many rating agencies also publish general and sector-specific rating methodologies. [ICRA's rating methodologies](https://www.icra.in/Rating/Methodology?Page=RatingMethodology) illustrate how the factors considered in a credit assessment may differ across industries. Reading the methodology for your chosen industry is good preparation for Section 5. Consider the following:

- Which financial metrics appear most relevant to the credit assessment, and how do they differ across industries?
- Which qualitative factors are considered, and how do they appear to influence the rating?
- Why might two companies in the same industry with similar financial ratios receive different credit ratings?

## 5. Problem statement

Select a company in an industry of your choice and attempt to assign an indicative credit rating using publicly available information. Credit rating involves both quantitative analysis and qualitative judgement. Given the limitations of publicly available information, clearly explain your approach, assumptions and reasoning.

You may wish to consider the following:

- **Agency framework.** Explore how a rating agency's methodology for your chosen industry could provide a framework for your assessment.
- **Quantitative models.** Consider whether Altman's Z-score, its variants or other quantitative models are appropriate for your chosen company and how they could contribute to your assessment.
- **Use of LLMs.** Explore how LLMs could assist in the credit assessment process, such as extracting financial information, identifying risk factors or analysing annual reports. Consider their limitations and verify their outputs against original sources.
- **Comparison.** Where a comparable published rating exists, compare it with your own assessment and explore possible reasons for any differences. Where possible, form your own assessment before consulting the company's published rating.

The objective is not necessarily to arrive at the same rating as an agency, but to develop a well-reasoned assessment. Reflect on the evidence, judgement and limitations underlying your rating.
