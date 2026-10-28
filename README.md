# Employee Payroll & Payslip Calculator (Oracle APEX & PL/SQL)

An automated web-based payroll management system built using **Oracle APEX** and procedural **PL/SQL**.

## 📌 Features
- **Employee Directory:** Full CRUD management for employee records and department assignments.
- **Automated Payroll Engine:** PL/SQL package processing salary allowances (20% HRA/DA) and dynamic income tax slabs.
- **Transaction Safety:** Idempotent `MERGE` statements preventing duplicate monthly pay runs.
- **Interactive Reports:** Formatted payroll summaries with real-time net salary calculations.

## 🛠️ Tech Stack
- **Database:** Oracle Database
- **Backend Logic:** PL/SQL Packages, Procedures, Functions, Merges
- **Frontend / UI:** Oracle APEX (Universal Theme, Interactive Reports, Page Designer)

## 🗂️ Project Structure
- `schema_and_logic.sql` - Table definitions, foreign key constraints, and PL/SQL package body.
- `f200090.sql` - Exported Oracle APEX application source file.
