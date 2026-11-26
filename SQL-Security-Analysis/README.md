# SQL Security Analysis – Employee and Login Activity

## Project Overview

In this project, I performed the role of a Security Analyst by using SQL queries to analyze employee and login activity data.

I investigated employee records and login attempts to identify potential security risks, including failed login attempts, after-hours activity, and login attempts from locations outside Mexico.

I used SQL filtering techniques to retrieve relevant information and support security investigations.

## 1. Retrieve After-Hours Failed Login Attempts

I used the Boolean value `FALSE` to filter failed login attempts that occurred after 18:00 (6:00 PM).

**Finding:** I identified a total of 19 failed login attempts.

## 2. Retrieve Login Attempts on Specific Dates

I investigated login activity on the following dates:

- 2022-05-08
- 2022-05-09

I used SQL queries to filter login attempts made on these dates.

**Finding:** A total of 75 login attempts were identified across these two days.

## 3. Retrieve Login Attempts Outside Mexico

I used the `NOT` and `LIKE` operators to identify login attempts originating outside Mexico.

I used the `LIKE` operator because some location values appeared as `Mex` instead of `Mexico`.

**Finding:** I identified 144 login attempts from locations outside Mexico.

## 4. Retrieve Employees in the Marketing Department

I used the `AND` and `LIKE` operators to filter employee records in the Marketing department.

The investigation focused on employees and machines associated with the East-170 and East-320 locations for system updates.

## 5. Retrieve Employees in Finance or Sales

I used the `OR` operator to retrieve employee records from both the Finance and Sales departments.

This information was needed to identify employees whose computers required updates.

## 6. Retrieve All Employees Not in IT

I used the `NOT` operator to filter out employees belonging to the Information Technology (IT) department.

The purpose was to identify employees outside IT whose computers might require updates.

**Finding:** I identified 161 employees who were not part of the IT department.

## Project Summary

Through this project, I gained practical experience using SQL queries to analyze employee and login activity data.

I used operators such as `AND`, `OR`, `NOT`, and `LIKE` to filter database records and investigate failed login attempts, after-hours activity, specific login dates, and login locations.

I also retrieved employee information from different departments to identify computers that required updates.

This project helped me understand how SQL can support security monitoring, data analysis, and the investigation of potentially unauthorized access attempts.

## Skills Demonstrated

- SQL queries and data filtering
- Database analysis
- Boolean values
- AND, OR, and NOT operators
- LIKE operator
- Login activity investigation
- Failed login analysis
- Employee data analysis
- Security monitoring

---

**Project Category:** Cybersecurity

**Project Type:** SQL Security Analysis

**Main Focus:** Login Activity, Database Filtering, and Employee Access Analysis
