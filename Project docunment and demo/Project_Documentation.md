Educational Organization Management System
1. Project Overview

The Educational Organization Management System is developed using ServiceNow to automate and manage student admission and academic progress tracking.

The system replaces manual processes involved in student admission, subject marks recording, result calculation, and progress monitoring. By digitizing these activities, the system improves accuracy, reduces paperwork, and provides centralized access to student information.

2. Objectives

The main objectives of this project are:

To automate the student admission process

To track academic performance efficiently

To reduce manual errors in result calculation

To provide centralized student data management

To improve operational efficiency and transparency

3. System Modules
3.1 Admission Module
Description

The Admission Module is responsible for storing student basic details at the time of admission.

Features

Unique Admission Number (Auto Generated)

Student Name

Grade

Father Name

Mother Name

Contact Details

Secure record storage in database

Functional Flow

User → Fill Admission Form → Submit → Record Stored in Database

3.2 Student Progress Module
Description

This module tracks the academic performance of students based on subject-wise marks.

Features

Reference to Admission Table

Automatic fetching of student details

Subject marks entry

Automatic total calculation

Automatic percentage calculation

Result generation (Pass/Fail)

4. Subjects Included

The following subjects are considered for academic evaluation:

Hindi

English

Telugu

Science

Social

Mathematics

5. Technical Implementation
Platform Used

ServiceNow

Components Used

Custom Tables

Forms

Reference Fields

Business Rules

Client Scripts

UI Policies

Calculated Fields

6. Business Logic
Total Calculation
Total = Hindi + English + Telugu + Science + Social + Maths

Percentage Calculation
Percentage = (Total / 600) * 100

Result Logic
If Percentage >= 35
    Result = Pass
Else
    Result = Fail

7. Database Structure
Admission Table

Admission Number (Primary Key)

Student Name

Grade

Father Name

Mother Name

Father Contact Number

Mother Contact Number

Student Progress Table

Admission Number (Reference Field)

Subject Marks

Total Marks

Percentage

Result

8. System Workflow

Admin creates an admission record.

Student progress record is created.

Admission details are automatically populated.

Subject marks are entered.

System automatically calculates:

Total marks

Percentage

Result

Data is saved and stored in the system database.

9. Testing Performed

The following testing activities were carried out:

Functional Testing

Form Validation Testing

Business Rule Testing

Calculation Accuracy Testing

Data Reference Validation

10. Expected Output

Accurate academic performance tracking

Automated result generation

Reduced paperwork

Easy retrieval of student records

Centralized student database management

11. Advantages

User-friendly interface

Automated calculations

Secure data storage

Scalable for multiple classes

Real-time data updates

12. Future Enhancements

Attendance Tracking Module

Teacher Dashboard

Report Generation (PDF/Excel)

Parent Portal Access

Performance Analytics Dashboard
