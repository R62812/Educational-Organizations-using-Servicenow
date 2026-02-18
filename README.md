EDUCATIONAL ORGANISATION MANAGEMENT SYSTEM
PROJECT OVERVIEW

The Educational Organisation Management System is developed using ServiceNow to automate student admission management and academic progress tracking.

The system replaces manual record handling with a centralized digital platform that improves accuracy, efficiency, and transparency in managing student data.

PROBLEM STATEMENT

Educational institutions often manage student admissions and academic records manually, which leads to:

Data redundancy

Calculation errors

Manual workload

Difficulty in tracking student performance

This project provides an automated solution using ServiceNow.

SOLUTION

The system automates:

Admission record creation

Subject marks entry

Automatic total calculation

Automatic percentage calculation

Result generation (Pass/Fail)

Using:

ServiceNow Forms

Client Scripts

Business Rules

Reference Fields

FEATURES

Student Admission Management

Unique Admission Number Generation

Student Progress Tracking

Automatic Total Calculation

Automatic Percentage Calculation

Automatic Result Generation

Centralized Data Storage

Role-Based Access Control

SYSTEM MODULES
1. ADMISSION MODULE

Creation of student admission records

Storage of personal and academic details

Database record management

Unique admission number generation

2. STUDENT PROGRESS MODULE

Subject-wise marks entry

Automatic total calculation

Automatic percentage calculation

Automatic result generation

Reference-based student data fetching

SUBJECTS INCLUDED

Hindi

English

Telugu

Science

Social

Maths

TECHNOLOGY STACK
Component	Technology
Platform	ServiceNow
Database	ServiceNow Tables
Scripting	Client Scripts
Automation	Business Rules
UI	ServiceNow Forms
SYSTEM ARCHITECTURE

User → Admission Form → Database Storage → Student Progress Form → Marks Entry → Calculation Logic → Result Generation → Record Storage

BUSINESS LOGIC

Total = Hindi + English + Telugu + Science + Social + Maths

Percentage = (Total / 600) × 100

Result:

Pass if Percentage ≥ 35

Fail if Percentage < 35

RESULTS AND OUTPUTS

The system was successfully implemented and tested in the ServiceNow Developer Instance environment.

ADMISSION MODULE RESULTS

Student admission records created successfully

Unique admission numbers generated automatically

Student details stored without duplication

Records saved and retrieved correctly

Reference relationship established with Student Progress module

STUDENT PROGRESS MODULE RESULTS

Subject-wise marks entered successfully

Total marks calculated automatically

Percentage calculated accurately

Result (Pass/Fail) generated based on percentage

Real-time updates using client scripts and business rules

FUNCTIONAL TESTING RESULTS
Valid Data Entry Testing

Accurate total calculation

Correct percentage display

Proper result generation

Boundary Testing

Percentage below 35 → Result shows Fail

Percentage ≥ 35 → Result shows Pass

Automation Testing

Client scripts executed correctly

Business rules triggered automatically

No manual calculation required

PERFORMANCE OUTCOME

100% calculation accuracy

Reduced manual workload

Elimination of calculation errors

Improved efficiency

Faster result processing

FUTURE ENHANCEMENTS

Attendance Tracking Module

Teacher Dashboard

Report Generation (PDF/Excel)

Parent Portal Access

Performance Analytics Dashboard

PROJECT TEAM:

> Rushitha Konangi
> C Prathyusha
> C Sai Prathyusha Reddy
> Guduru Saritha



github link:
https://github.com/R62812/Educational-Organizations-using-Servicenow




