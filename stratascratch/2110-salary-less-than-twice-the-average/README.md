# 2110. Salary Less Than Twice The Average

| Field | Value |
|---|---|
| Platform | StrataScratch |
| Difficulty | Unknown |
| Category | SQL |
| Link | [Salary Less Than Twice The Average](https://platform.stratascratch.com/coding/2110-salary-less-than-twice-the-average) |

## Problem Statement

### Salary Less Than Twice The Average

Last Updated: November 2026

 Medium

ID 2110

120

Write a query to get the list of managers whose salary is less than twice the average salary of employees reporting to them. For these managers, output their ID, salary and the average salary of employees reporting to them.

##### Tables

map\_employee\_hierarchy

dim\_employee

##### This question is part of an interview loop

See the full interview round by round, with questions for each stage.

[Amazon · Data Scientist](https://platform.stratascratch.com/interview-loops/amazon/data-scientist)[E-commerce & retail · Data Scientist](https://platform.stratascratch.com/interview-loops/e-commerce-and-retail/data-scientist)

---

---

##### map\_employee\_hierarchy

empl\_id:textmanager\_empl\_id:text

##### dim\_employee

empl\_id:textempl\_name:textempl\_city:textempl\_dob:dateempl\_pin:bigintsalary:bigint

---

##### Recommended Medium Interview Questions

- ID 515[City With the Biggest Growth and Drop](https://platform.stratascratch.com/coding/10554-biggest-drop)
- ID 2000[Variable vs Fixed Rates](https://platform.stratascratch.com/coding/2000-variable-vs-fixed-rates)
- ID 2001[Share of Loan Balance](https://platform.stratascratch.com/coding/2001-share-of-loan-balance)

##### Recommended Questions from the Same Companies

- ID 2171[Customer Order Summary](https://platform.stratascratch.com/coding/2171-customer-order-summary)
- ID 2169[Contact Information Completeness](https://platform.stratascratch.com/coding/2169-contact-information-completeness)
- ID 2167[High Earners in Support Departments](https://platform.stratascratch.com/coding/2167-high-earners-in-support-departments)

## Expected Output

| manager_id | salary | empl_avg_salary |
| --- | --- | --- |
| E850 | 30000 | 20000 |
| E854 | 18000 | 16000 |
