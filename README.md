# FitRITE Life – Database Design Project

This repository contains a database design project for **FitRITE Life**, a fitness and wellness center. The project was completed as part of a database systems course and includes data modeling, relational schema, data dictionary, sample data, and SQL query development.

---

## Project Overview

FitRITE Life is a fitness organization that requires a well-structured relational database to manage members, employees, classes, equipment, and membership plans. The goal of this project is to create a normalized and scalable database that supports administrative operations, class scheduling, and member tracking.

---

## Part A – Entity Relationship Diagram

An **ER diagram using Crow’s Foot Notation** was developed to show relationships between:
- Members and Membership Plans (1:M)
- Employees and Classes (1:M)
- Members and Classes (M:N, via bridge table)
- Equipment and Facility locations

---

## Part B – Relational Schema

The schema includes the following core tables:

- `MEMBERS(Member_ID, CusName, Customer_Phone, Cust_Address, MembType, EnrollDate)`
- `EMPLOYEES(Employee_ID, EmployeeName, ContactInfo, Position, HiringDate)`
- `CLASSES(Class_ID, Class_Name, Description, Instructor, Schedule, Capacity)`
- `EQUIPMENT(Equipment_ID, Equipment_Type, Condition, Date_Purchased, Location)`
- `MEMBERSHIP_PLAN(Plan_ID, Plan_Name, Plan_Description, Plan_Cost, Plan_Benefits)`

---

## Part C – Data Dictionary

Each table was documented with:
- Field names, types, formats, and constraints
- Primary and foreign keys
- Acceptable value ranges
- Referential integrity notes

The design follows normalization principles to minimize redundancy and enhance consistency across related records.

---

## Part D – SQL Query Demonstrations

Sample SQL queries were written to retrieve information such as:
- Member enrollment data
- Class schedules and instructors
- Equipment inventory and conditions
- Employee contact details
- Membership plan benefits

(SQL screenshots included in the original PDF.)

---

## Part E – Scenario-Based Recommendations

One scenario involved recommending an upgrade for a **gold-tier member** who had earned points and preferences for equipment use. Based on system logic, a path to **platinum-tier eligibility** was described by enhancing engagement metrics such as equipment preference scores.

---

## File Structure

**Jeremiah Mendoza**  
Database Design Project Contributor  
University of Texas at Arlington  
GitHub: (https://github.com/JeremiahMcode)) 
