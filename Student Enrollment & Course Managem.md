# **Student Enrollment \& Course Management System (SECMS)**



#### **User Story:**

&#x09;The Student Enrollment \& Course Management System is a comprehensive Salesforce application designed to streamline and automate the academic enrollment operations of an educational institute. This system enables administrators, enrollment officers, and instructors to efficiently manage student records, course offerings, enrollments, instructor assignments, approval processes, payments, and reporting—all within a unified Salesforce environment.



**1. INTRODUCTION**



**1.1 Project Overview :**



&#x09;This project aims to centralize all student, course, and enrollment-related data within a single Salesforce application to ensure easy data access, structured workflows, and accurate reporting. The system allows Enrollment Officers to manage student admissions, course registrations, and communication effectively, while instructors and administrators gain full transparency into course allocations and academic progress. The solution also enables automated instructor assignment, task creation, validation checks, and multi-level approval processes for enrollment management.



&#x09;With Salesforce Flows, Approval Processes, Validation Rules, Reports, and Dashboards, the organization can ensure that all enrollment operations—from admission to course completion—are handled systematically and with continuous monitoring of key performance indicators such as enrollment volume, revenue, student status distribution, and pending approvals.



**1.2 Purpose :**



&#x09;The primary purpose of SECMS is to replace manual and fragmented enrollment processes with a scalable, automated, and secure Salesforce solution that ensures:



&#x09;						1)Accurate student data management



&#x09;						2)Structured enrollment workflows



&#x20;   							3)Automated approvals and validations



&#x20;     							4)Transparent reporting and monitoring



**2. IDEATION PHASE**

**2.1 Problem Statement (Customer Problem Statement Template)**



PS



I am (Customer)



I’m trying to



But



Because



Which makes me feel



**PS-1**



Enrollment Officer



manage student enrollments efficiently



enrollment data is scattered



systems are manual and unintegrated



frustrated and error-prone



**PS-2**



Administrator



track enrollments and revenue



reporting is delayed



data is not centralized



uncertain in decision-making



**2.2 Empathy Map Canvas**

User Persona: Enrollment Officer



**2.3 Brainstorming \& Idea Prioritization**

Step 1 – Brainstormed Ideas



Step 2 – Grouping



Step 3 – Prioritization Salesforce-based SECMS was selected due to high feasibility and high impact.



**3.REQUIREMENT ANALYSIS PHASE**

**3.1 Customer Journey Map**

Stages covered:



**3.2 Solution Requirements**

**Functional Requirements**



FR No



Epic



Description



**FR-1**



Student Management



Manage student records



**FR-2**



Course Management



Create and manage courses



FR-3



Enrollment Processing



Request, approve, reject enrollments



FR-4



Instructor Assignment



Auto-assign instructors



FR-5



Reporting



Dashboards and reports



Non-Functional Requirements



NFR-1: Usability



The system shall provide a simple, intuitive, and user-friendly interface that enables enrollment officers, administrators, instructors, and students to perform operations efficiently with minimal training. Navigation shall be organized through clearly labeled tabs, dashboards, and forms to reduce user effort and errors.



Examples:



NFR-2: Security



The system shall ensure the confidentiality, integrity, and protection of student and institutional data through secure authentication, authorization, and access controls. Sensitive information such as personal data, enrollment history, and academic records shall only be accessible to authorized users.



Examples:



NFR-3: Reliability



The system shall operate consistently and accurately without failures during enrollment processing, approvals, and reporting. Automation logic shall execute correctly to avoid duplicate or incorrect enrollments.



Examples:



NFR-4: Performance



The system shall provide fast response times for all operations to ensure smooth and uninterrupted user experience, especially during peak admission periods.



Examples:



NFR-5: Scalability



The system shall support future growth in the number of students, courses, departments, and users without degradation in performance or functionality. It shall allow easy addition of new modules and features.



Examples:



NFR-6: Availability



The system shall be continuously accessible to users during institutional working hours and must minimize downtime. The platform shall support high availability for academic operations.



Examples:



3.3 Data Flow Diagram

The system processes enrollment requests, validates data, routes approvals, assigns instructors, and generates reports.



3.4 Technology Stack



Layer



Technology



UI



Salesforce Lightning



Logic



Salesforce Flows



Database



Salesforce Objects



Automation



Validation Rules, Approval Process



Reporting



Reports \& Dashboards



4\. PROJECT DESIGN PHASE

4.1 Problem–Solution Fit

SECMS directly addresses fragmented enrollment workflows by aligning user behavior, constraints, and automation using Salesforce-native capabilities.



4.2 Proposed Solution

Functional Requirements



Parameter



Description



Problem



Manual enrollment handling



Solution



Salesforce-based SECMS



Novelty



End-to-end automation



Social Impact



Improved student experience



Revenue Model



Institutional deployment



Scalability



Multi-department support



4.3 Solution Architecture

The architecture integrates Salesforce objects, automation flows, approval processes, dashboards, and security layers.



5\. PROJECT PLANNING \& SCHEDULING

5.1 Project Planning

Product Backlog, Sprint Schedule, and Estimation (4 Marks)



Use the below template to create product backlog and sprint schedule



Sprint



Functional Requirement (Epic)



User Story Number



User Story / Task



Story Points



Priority



Team Members



Sprint-1



Developer Setup



USN-1



As a system administrator, I want to create a Salesforce developer account so that I can configure and deploy the Student Enrollment system..



1



High



Member1



Sprint-1



Data Modeling



USN-2



As an admin, I want to create custom objects for Student, Course, Enrollment, and Instructor so that academic data can be stored and managed efficiently.



3



High



Member2



Sprint-2



Data Modeling



USN-3



As a user, I want dedicated tabs for each object so that I can easily navigate between students, courses, enrollments, and instructors.



3



High



Member3



Sprint-2



Data Modeling



USN-4



As an admin, I want to create relevant fields such as student details, course information, and enrollment status so that complete records can be captured accurately.



5



High



Member4



Sprint-2



Data Modeling



USN-5



As an enrollment officer, I want a centralized Lightning App so that I can access all academic operations from one interface.



3



High



Member4



Sprint-2



Data Modeling



USN-6



As an admin, I want to define relationships between students, courses, and enrollments so that the system can logically link and track academic activities.



5



Medium



Member1



Sprint-2



Data Modeling



USN-7



As a user, I want customized page layouts so that only relevant information is displayed, improving clarity and ease of data entry.



5



High



Member2



Sprint-3



Automation



USN-8



As a system, I want to validate input data such as mandatory fields and enrollment limits so that incorrect or incomplete records are prevented.



3



High



Member4



Sprint-3



Automation



USN-9



As a system, I want automated flows to handle enrollment processing and notifications so that manual effort is reduced and processes become faster.



3



High



Member4



Sprint-3



Automation



USN-10



As an administrator, I want an approval process for enrollment requests so that registrations are verified before confirmation.



5



High



Member1



Sprint-4



Security



USN-11



As an admin, I want to configure role-based security so that users can only access data relevant to their responsibilities.



5



High



Member2



Sprint-5



Reports



USN-12



As a manager, I want reports on student enrollments, course registrations, and instructor assignments so that I can monitor academic operations.



4



High



Member3



Sprint-6



Dashboards



USN-13



As a manager, I want visual dashboards showing enrollment statistics and trends so that I can quickly analyze system performance.



4



Medium



Member4



Project Tracker, Velocity \& Burndown Chart: (4 Marks)



Sprint



Total Story Points



Duration



Sprint Start Date



Sprint End Date (Planned)



Story Points Completed (as on Planned End Date)



Sprint Release Date (Actual)



Sprint-1



20



6 Days



24 Oct 2022



29 Oct 2022



20



29 Oct 2022



Sprint-2



20



6 Days



31 Oct 2022



05 Nov 2022



Sprint-3



20



6 Days



07 Nov 2022



12 Nov 2022



Sprint-4



20



6 Days



14 Nov 2022



19 Nov 2022



6\. Project Development Phase:

Project Flow:

Milestone 1: Salesforce Developer Account Creation



Milestone 2: Custom Object Creation (Student, Course, Enrollment, Instructor)



Milestone 3: Tabs Creation



Milestone 4: Lightning App Creation



Milestone 5: Fields Creation



Milestone 6: Create Relationships



Milestone 7: Page Layout Customization



Milestone 8: Validation Rules



Milestone 9: Flows (Automation)



Milestone 10: Approval Process



Milestone 11: Reports



Milestone 12: Dashboards



Milestone 13: Security Setup



Milestone 14: Conclusion



What you'll learn



Milestone 1-Salesforce :

Introduction:



Are you new to Salesforce? Not sure exactly what it is, or how to use it? Don’t know where you should start on your learning journey? If you’ve answered yes to any of these questions, then you’re in the right place. This module is for you.



Welcome to Salesforce! Salesforce is game-changing technology, with a host of productivity-boosting features, that will help you sell smarter and faster. As you work toward your badge for this module, we’ll take you through these features and answer the question, “What is Salesforce, anyway?”.



What Is Salesforce?



Salesforce is your customer success platform, designed to help you sell, service, market, analyze, and connect with your customers.



Salesforce has everything you need to run your business from anywhere. Using standard products and features, you can manage relationships with prospects and customers, collaborate and engage with employees and partners, and store your data securely in the cloud. So what does that really mean? Well, before Salesforce, your contacts, emails, follow-up tasks, and prospective deals might have been organized something like this:



https://youtu.be/r9EX3lGde5k



Activity 1: Creating Developer Account:

Creating a developer org in salesforce.



Go to https://developer.salesforce.com/signup



On the sign up form, enter the following details :



First name \& Last name



Email



Role : Developer



Company : College Name



County : India



Postal Code : pin code



Username : should be a combination of your name and company



This need not be an actual email id, you can give anything in the format : username@organization.com



Click on sign me up after filling these.



Activity 2: Account Activation:

1\. Go to the inbox of the email that you used while signing up. Click on the verify account to activate your account. The email may take 5-10mins.



2\. Click on Verify Account



3\. Give a password and answer a security question and click on change password.



4\. Then you will redirect to your salesforce setup page.



Milestone 2 – Objects:

Activity 1: Creating Student  Object:

The purpose of creating the Student custom object is to store and manage information about students such as their personal details, contact information, and enrollment status.



To create the Student object:



Go to the Setup page.



Click on Object Manager.



Click on Create → Custom Object.



Enter the details as below:



&#x20;In the same way Create Courses, Instructors, and Enrolments objects



Milestone 3 - Fields:

Table 1: Student Object Fields:

Field Label



Data Type



Student Name



Text (Standard)



Email



Email



Phone



Phone



Date of Birth



Date



Student Status



Picklist



Address



Text Area



Table 2: Course Object Fields:

Field Label



Data Type



Course Name



Text (Standard)



Category



Picklist



Duration



Number/Text



Course Fee



Currency



Description



Text Area



Table 3: Instructor Object Fields:

Field Label



Data Type



Instructor Name



Text (Standard)



Instructor Code



Text



Expertise



Picklist



Phone



Phone



Email



Email



Table 4: Enrollment Object Fields:

Field Label



Data Type



Student



Lookup (Student)



Course



Lookup (Course)



Instructor



Lookup (Instructor)



Enrollment Date



Date



Enrollment Status



Picklist



Fees Paid



Checkbox



Total Amount



Currency



Comments



Text Area



Milestone 4 – Create Relationships:

Activity 1: Create Lookup from Enrollment to Student:

Activity 2: Create Lookup from Enrollment to Course

Purpose:



To link each Enrollment to a Course.



Steps:



Activity 3: Create Lookup from Enrollment to Instructor:

Purpose:



To store which Instructor is assigned to a particular Enrollment.



Steps:



Milestone 5 – Validation Rules:

Activity 1: Student Email Domain Validation

Purpose:



To ensure students use only allowed institutional email addresses.



Steps:



Go to Setup → Object Manager → Student\_\_c.



Click Validation Rules → New.



Rule Name: Student\_Email\_Domain\_Validation.



Error Condition Formula: (example for @student.edu)



Error Message: Email must be a valid student institutional email.



Error Location: Field → Email\_\_c.



Click Save.



Activity 2: Fees Must Be Paid Before Approval

Purpose:



Prevent Enrollment from being approved until fees are paid.



Steps:



AND(



&#x20; ISPICKVAL(Enrollment\_Status\_\_c, "Approved"),



&#x20; Fees\_Paid\_\_c = FALSE



)



5.Error Message: Fees must be paid before approving an enrollment.



6.Error Location: Top of Page (or field as needed).



Click Save.



Milestone 6 – Approval Process

Activity 1: Create Approval Process for Enrollment Requests

Purpose:



Route Enrollment requests to the Training Manager for approval or rejection.



Steps:



Milestone 7- Tabs

Activity 1: Creating a Tab for the Student Object:

Go to Setup.



Activity 2: Creating Remaining Tabs

Now create the Tabs for the remaining Objects, they are “Courses, Instructors, Enrollment”.



Follow the same steps as mentioned in Activity -1



Milestone 8 - The Lightning App

Activity 1: Creating the Lightning Application for the Project

Navigate to Setup.



Enter App Manager in the Quick Find search box.



Click New Lightning App.



Provide the app details:



App Name: Student Enrollment \& Course Management



Developer Name auto-fills



Description: Optional, but can describe the purpose of the app



Click Next and choose the following settings:



App Branding (optional): Add logo or select color theme



Navigation Style: Choose Standard Navigation



Click Next and assign the app to specific profiles (e.g., Admin, Enrollment Officer, Instructor).



Click Next to select the items (tabs) to be included in the app. Add:



Click Next and review the app settings.



Finally, click Save \& Finish.



Milestone 9 – Page Layouts and Record:

Activity 1: Create Record Types for Enrollment:

Purpose:



To separate New Enrollment vs Re-Enrollment processes.



Steps:



1.Go to Setup → Object Manager → Enrollment\_\_c.



2.Click Record Types → New.



3.For the first record type:



4.For the second record type:



Activity 2: Separate Page Layout Creators for Each Enrollment Record Type

Purpose:



To show different fields for New Enrollment vs Re-Enrollment.



Steps:



&#x20;1.Enrollment\_\_c object → click Page Layouts.



2.Click New to create a layout for New Enrollment:



3.Again, click New to create Re-Enrollment Layout:



4.Click Page Layout Assignment → Edit Assignment.



5.For each profile and record type:



6.Re-Enrollment → use Re-Enrollment Layout.



Click Save.



Activity 3: Enrollment R Addelated Lists to Parent Objects:

Purpose:



To see all Enrollments from Student, Course, and Instructor records.



a) Student → Enrollment Related List



Go to Setup → Object Manager → Student\_\_c.



Click Page Layouts → open the main layout.



In the palette, select Related Lists.



Drag Enrollments related list onto the layout.



Customize columns if needed → Save.



b) Course → Enrollment Related List



Go to Object Manager → Course\_\_c → Page Layouts.



Open layout → add Enrollments related list.



Save.



c) Instructor → Enrollment Related List



Go to Object Manager → Instructor\_\_c → Page Layouts.



Open layout → add Enrollments related list.



Save.



Milestone 10 – Automation with Flow

Activity 1: Auto-Populate Enrollment Date (Record-Triggered Flow)

Purpose:



Set Enrollment\_Date\_\_c to today when Enrollment is created.



Steps:



7.Save as SetEnrollmentDate → Activate.



Activity 2: Send Email When Enrollment Approved

Purpose:



When Enrollment\_Status\_\_c = Approved, send email, alert admin, and set Student to Active.



Steps (high level for document):



Activity 3: Auto-Assign Instructor Based on Course Category

Purpose:



Assign Instructor automatically based on Course category.



Rules:



Technical → Instructor A



Language → Instructor B



Non-Technical → Instructor C



Steps:



Activity 4: Auto-Create Task for Follow-Up

Purpose:



When Enrollment is “Requested”, create a follow-up task for Admin.



Steps:



Milestone 11 – Reports:

Activity 1: Create “Students by Status” Report

1.Go to Reports → New Report.2.Report Type: Students.3.Group rows by Status\_\_c.4.Add columns as needed (Name, Email, Phone).5.Save as Students by Status.



Activity 2: Create “Enrollments by Course” Report

1.New Report → Report Type: Enrollments.2.Grouprows by Course\_\_r.Name.3.Show Record  Count per course.4.Save as Enrollments by Course



Activity 3: Create “Pending Enrollment Approvals” Report

Activity 4: Create “Revenue Report (Fees Paid)” Report

1.New Report → Enrollments report type.2.Filter: Fees\_Paid\_\_c = TRUE.3.Group by Course\_\_r.Name.4.Summarize Course\_Fee\_\_c or similar fee field.5.Save as Revenue Report – Fees Paid.



Milestone 12 – Dashboards:

Activity 1: Create “Student Managemet Dnashboard”

Steps:



Add components:



Click Save → Done.



Milestone 13 – Security Setup

Activity 1: Configure Profiles

):



Repeat similarly for Instructor profile with Read-Only on Enrollments



Activity 2: Create Permission Sets

Activity 3: Configure Sharing \& OWD

Steps:



For Instructor access to assigned Enrollments, optionally:



7\. FUNCTIONAL \& PERFORMANCE TESTING

&#x20;



During the testing phase, screenshots were captured from the Salesforce user interface to verify the proper functioning of all implemented features of the Student Enrollment \& Course Management System (SECMS). These include student, course, instructor, and enrollment record creation; validation rule checks for mandatory fields, eligibility, and enrollment constraints; verification of record type behavior for different course categories; flow execution for automated enrollment approvals and seat availability checks; and Apex trigger functionality to ensure automatic confirmation and record updates. Additionally, screenshots of generated reports and dashboards were documented to validate accurate data visualization, enrollment tracking, and performance monitoring. Submit the Screenshots while testing.



8\. ADVANTAGES \& DISADVANTAGES

Advantages

Disadvantages

9\. Conclusion:

&#x20; The Salesforce Student Enrollment \& Course Management System successfully streamlines the entire student academic lifecycle—from student registration and course creation to enrollment management, instructor assignment, approvals, revenue tracking, and reporting. By leveraging Salesforce’s automation tools such as validation rules, flows, approval processes, and dashboards, the system improves data accuracy, operational efficiency, and decision-making. This project demonstrates how Salesforce can transform manual academic processes into a scalable, reliable, and user-friendly digital solution.



10\. FUTURE SCOPE

11\. APPENDIX

&#x20;                                       Thank You

&#x20;

