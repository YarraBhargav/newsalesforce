# Salesforce Interview Readiness Bootcamp – Day 3 Assignment

## Project Title
Placement Management System – Validation Rules, Flows & Triggers

## Objective
This project demonstrates the implementation of Salesforce declarative automation using Validation Rules and Record-Triggered Flows for a Placement Management System.

## Objects Created
- Student
- Job
- Application

## Fields Created

### Student
- Student Name
- CGPA

### Job
- Job Name
- Minimum CGPA
- Closing Date

### Application
- Application Name
- Student (Lookup)
- Job (Lookup)
- Application Date

---

## Flow Implemented

### Record-Triggered Flow
**Flow Name:** Application Date Flow

### Purpose
- Automatically sets the Application Date when a new Application record is created.
- Uses Record-Triggered Flow for automation.

---

## Validation Rules Implemented

### 1. Student Required
Prevents saving an Application without selecting a Student.

### 2. CGPA Validation
Prevents students from applying if their CGPA is below the Job's Minimum CGPA.

### 3. Application Date Validation
Prevents Application Date from being later than the Job Closing Date.

---

## Why I Used Flow

- Automatically update fields.
- Reduce manual work.
- No Apex code required.
- Easy to maintain.

---

## Why I Used Validation Rules

- Ensure data quality.
- Prevent invalid records.
- Enforce business requirements before saving records.

---

## Apex Requirement

No Apex Trigger was used because the given requirements were achieved using Salesforce declarative tools (Flow and Validation Rules).

---

## Screenshots Included

- Flow Canvas
- Start Element
- Assignment Element
- Successful Flow Execution
- Validation Rules
- Application Record

---

## Tools Used

- Salesforce Trailhead Playground
- Flow Builder
- Validation Rules
- Object Manager

---

## Conclusion

Successfully implemented a Placement Management System using Salesforce Flow and Validation Rules. The project demonstrates declarative automation, data validation, and interview-ready Salesforce development concepts.

