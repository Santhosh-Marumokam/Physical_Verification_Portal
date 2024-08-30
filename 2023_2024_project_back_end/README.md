# Physical Verification Module

## Description

This module is part of the DSW (Department of Student Welfare) system, designed to verify students following the pre-registration process. It executes after course allotment is completed for all students.

The Physical Verification module transfers allotted courses from `pre_stu_course` to `cbcs_stu_course` upon successful verification of students.

## Tech Stack

- Frontend: Next.js
- Backend: PHP, Laravel
- Database: SQL

## Features

- Automated execution after course allotment completion
- Secure transfer of course data between database tables
- Integration with existing DSW systems
