📘 PL/SQL Practice – Blocks & Attribute Data Types
🔹 Overview

This repository contains my practice work on PL/SQL programming focusing on:

PL/SQL Block Structure (Anonymous, Named, and Nested blocks)

%TYPE and %ROWTYPE Attribute Data Types for efficient variable declarations

The aim of this practice is to strengthen my PL/SQL basics and improve my ability to write clean, reusable, and error-free database programs.

🔹 Topics Covered
1️⃣ PL/SQL Block Structure

Anonymous Blocks → For testing quick logic without saving.

Named Blocks → Stored procedures, functions, and packages.

Nested Blocks → Using one block inside another for modular coding.

Sections in a Block

DECLARE → Variable, constants, cursors

BEGIN → Main executable statements

EXCEPTION → Error handling

END → End of block

2️⃣ Attribute Data Types in PL/SQL
🔸 %TYPE

Used to declare a variable with the same datatype as a column.

Helps maintain data integrity and reduces dependency on schema changes.

Example Use Case: Storing salary%TYPE or hiredate%TYPE.

🔸 %ROWTYPE

Used to declare a record variable that can hold an entire row of a table.

Useful for fetching multiple columns from a table into one variable.

Example Use Case: v_emp_record emp%ROWTYPE to hold all employee details.

🔹 Key Learnings

Writing and executing anonymous PL/SQL blocks in SQL*Plus/SQL Developer.

Using substitution variables (&) for dynamic input.

Applying %TYPE and %ROWTYPE to improve flexibility in code.

Handling exceptions (NO_DATA_FOUND, TOO_MANY_ROWS, OTHERS).

Understanding the importance of COMMIT and ROLLBACK.
