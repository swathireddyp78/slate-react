In this project, built three separate Web applications using React, Python Flask, and Postgres database. The three applications will interact with each other by providing and consuming RESTful Web Services.

SLATE:

This is an admissions portal for graduate admissions. This website maintains a database slate.sql that records data about departments, programs, applicants, and applications. 

This website has the following functionality:
1. Register with email, fname, lname, and password.
2. Login/Logout
3. Update Profile (update fields except aid and email)
4. Apply for admission
5. Graduate Director should be able to ACCEPT/REJECT applicant (you need not provide a login for the Graduate Director!)


Slate provides the following REST Web services:
1. Given university, return a list of ACCEPTED applicants (only those that have not been sent in the past).
2. Given university, term, and year, return university level statistics of applicants (for each department and program, return number of applicants, number of accepts, number of rejects, and number of pending decisions).
3. Given university, department, term, and year, return department level statistics of applicants (for each program, return number of applicants, number of accepts, number of rejects, and number of pending decisions).
