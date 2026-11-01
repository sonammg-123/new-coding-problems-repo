# 10322. Finding User Purchases

| Field | Value |
|---|---|
| Platform | StrataScratch |
| Difficulty | Unknown |
| Category | SQL |
| Tables | `user_ids` |
| Link | [Finding User Purchases](https://platform.stratascratch.com/coding/10322-finding-user-purchases) |

## Problem Statement

### Finding User Purchases

Last Updated: October 2026

 Medium

ID 10322

710

Identify returning active users by finding users who made a second purchase within 1 to 7 days after their first purchase. Ignore same-day purchases. Output a list of these `user_ids`.

##### Table

amazon\_transactions

##### This question is part of an interview loop

See the full interview round by round, with questions for each stage.

[Amazon · Data Engineer](https://platform.stratascratch.com/interview-loops/amazon/data-engineer)

---

---

##### amazon\_transactions

id:bigintuser\_id:bigintitem:textcreated\_at:daterevenue:bigint

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

| user_id |
| --- |
| 100 |
| 103 |
| 105 |
| 109 |
| 111 |
| 114 |
| 117 |
| 122 |
| 130 |
| 131 |
| 133 |
| 141 |
| 143 |
