# Educational-Organizations-using-Servicenow
Educational Organisation Management System
Project Overview

The Educational Organisation Management System is developed using ServiceNow to automate student admission management and academic progress tracking. The system replaces manual record handling with a centralized digital platform that improves accuracy, efficiency, and transparency in managing student data.

Problem Statement

Educational institutions often manage student admissions and academic records manually, which leads to data redundancy, calculation errors, and difficulty in tracking student performance. This project provides an automated solution to manage admissions and academic progress efficiently.

Solution

The system automates admission entry, subject marks management, total and percentage calculation, and result generation using ServiceNow forms, client scripts, and business logic. It ensures accurate data storage and easy retrieval of student records.

Features

Student admission management

Unique admission number generation

Student progress tracking

Automatic total calculation

Automatic percentage calculation

Result generation (Pass/Fail)

Reference-based data fetching

Centralized data storage

Role-based access control

System Modules
Admission Module

Creation of student admission records

Storage of personal and academic details

Database record management

Student Progress Module

Subject-wise marks entry

Automatic calculation of total and percentage

Automatic result generation

Subjects Included

Hindi

English

Telugu

Science

Social

Maths

Technology Stack
Component	Technology
Platform	ServiceNow
Database	ServiceNow Tables
Scripting	Client Scripts
Automation	Business Rules
UI	ServiceNow Forms
System Architecture (Simple Flow)

User → Admission Form → Database Storage → Student Progress Form → Marks Entry → Calculation Logic → Result Generation → Record Storage

Business Logic

Total = Hindi + English + Telugu + Science + Social + Maths

Percentage = (Total / 600) × 100

Result:

Pass if Percentage ≥ 35

Fail if Percentage < 35

Installation and Setup

Login to ServiceNow Developer Instance

Create Admission and Student Progress tables

Configure fields and reference relationships

Design forms

Implement client scripts and business rules

Test application functionality

Usage

Login to ServiceNow

Create a new admission record

Save student details

Open student progress module

Enter subject marks

System automatically calculates total, percentage, and result

Testing

Functional testing

Form validation testing

Business logic testing

Calculation accuracy testing

Data reference validation

Screenshots

(Add screenshots of Admission Form, Student Progress Form, and Result Output here.)

Demo Video

(Add project demo video link or file reference here.)

Future Enhancements

Attendance tracking module

Teacher dashboard

Report generation (PDF/Excel)

Parent portal access

Performance analytics dashboard

Project Team

Rushitha Konangi

C Prathyusha

C Sai Prathyusha Reddy

Guduru Saritha
