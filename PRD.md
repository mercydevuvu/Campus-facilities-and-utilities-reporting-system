PRODUCT REQUIREMENTS DOCUMENT (PRD)

Campus Electricity Monitoring and Reporting System

 1. Product Overview

What is the product?

The Campus Electricity Monitoring and Reporting System is a proposed digital platform designed to help students and other members of the university community report electricity outages and access information about electricity availability across different campus locations.

The platform will provide a centralized system where users can submit outage reports, view reports submitted by others, and check the latest reported electricity status for selected locations.

The main purpose of the product is to improve communication about electricity interruptions and make electricity-related information easier to access within the university community.

Background and Research

Electricity plays an important role in students' academic and daily activities. Students depend on electricity to charge their laptops and phones, study at night, complete assignments, and access online learning resources.

To understand the problem better, three students were interviewed about their experiences with electricity interruptions.

Interview 1:
Question: How does poor electricity supply affect your studies?
Response: Sometimes, the student cannot charge their laptop or read comfortably at night especially during exam periods because there is no electricity. Power interruptions affect their studies.

Interview 2:
Question: What do you normally do when electricity goes off?
Response: Ask roommates if information was passed earlier or contacts friends in other hostels to find out whether they are experiencing the same issue.

Interview 3:
Question: Would a platform for reporting electricity outages be useful?
Response: Yes. It would make it easier to check the electricity situation instead of asking different people. It could also help students receive information earlier.

Initial Research Findings:

- Electricity interruptions can affect students' academic activities.
- Students depend on informal communication to obtain information about electricity availability.
- The students interviewed expressed interest in a centralized reporting platform.
- A reporting system could reduce the need to repeatedly ask different people for updates.

These findings are preliminary because only three interviews have been conducted. More interviews and surveys are needed to understand the experiences of a wider group of students.

 Existing Solutions and Their Limitations

Students currently cope with electricity interruptions through:

- Asking roommates and hostel neighbours.
- Using rechargeable fans and torch
- Contacting friends in other hostels.
- Waiting for electricity to return.
- Using power banks and alternative charging options.
- Moving to locations where electricity is available.

Limitations of these methods:

- Information may not reach everyone.
- Updates may be delayed or inaccurate.
- There is no centralized place to view outage reports.
- Students may need to contact several people before receiving useful information.
- The batteries of the rechargeable appliances can run out
- Information can become outdated.

2. Problem Statement

What problem are we solving?

Unreliable electricity supply can affect students' academic activities and daily routines on campus.

Students may experience difficulties charging laptops and mobile phones, studying at night, completing assignments, and carrying out other activities that depend on electricity.

Currently, students often depend on informal communication methods, such as asking roommates, classmates, or friends in other hostels to find out whether electricity is available.

These methods can be inconvenient because information may be delayed, incomplete, or unavailable.

The main problem is the absence of a centralized platform where students can report electricity interruptions and access information about reported electricity conditions across different campus locations.

The proposed system aims to address this communication gap by providing a shared platform for electricity outage reporting and status updates.

3. Business Objectives

 What does the business want?

Although this is an academic project rather than an established commercial business, the product has the following objectives:

1. Improve access to information about electricity availability across campus.
2. Reduce dependence on informal communication for electricity updates.
3. Make reporting electricity outages easier and more organized.
4. Encourage information sharing among students and other members of the university community.
5. Provide a reliable starting point for managing electricity-related reports.
6. Create a foundation for future improvements in campus communication.

 4. Target Users

 Who will use the product?

1. Students

Students who need electricity information to plan their academic and personal activities. They will be able to submit outage reports and view information about electricity availability.

2. Hostel Residents

Students living in university hostels who experience electricity interruptions and need information about the electricity situation in their locations.

3. Lecturers

Academic staff who may need electricity information when planning activities that depend on electricity.

The primary target users for the first version will be students and hostel residents.

 5. Stakeholders

 Who is involved or affected?

1. Students: Primary users who submit reports and check electricity updates.

2. Hostel Residents: Users who may frequently need information about electricity availability in their residential locations.

3. Lecturers: Members of the university community who may benefit from electricity-related updates.

4. University Management: A potentially important stakeholder because electricity supply and campus infrastructure affect the university community.

5. Project Development Team: Responsible for researching, designing, developing, testing, and maintaining the system.

6. System Administrators: Responsible for reviewing reports, managing submitted information, and updating report statuses if administrative functionality is implemented.

 6. User Stories

 What do users want to accomplish?

User stories describe what different users want to achieve through the platform.

Student:

- As a student, I want to report an electricity outage so that other students can be aware of the situation.
- As a student, I want to select my campus location so that my report identifies where the outage occurred.
- As a student, I want to view existing outage reports so that I can understand the reported electricity situation.
- As a student, I want to check the latest reported status of a location so that I can plan my activities.

Hostel Resident:

- As a hostel resident, I want to see reports from my location so that I can know whether other residents have reported an outage.
- As a hostel resident, I want to see when a report was submitted so that I can judge how recent the information is.

System Administrator:

- As an administrator, I want to review submitted reports so that inaccurate information can be identified.
- As an administrator, I want to update report statuses so that users can see the latest available information.

7. Functional Requirements

What must the system do?

The system should provide the following functions:

1. Outage Reporting: Allow users to submit electricity outage reports.
2. Location Selection: Allow users to select the campus location affected by an outage.
3. Report Description: Allow users to provide a short description of the electricity problem.
4. Date and Time Recording: Automatically record the date and time when a report is submitted.
5. Report Storage: Store submitted reports in the system.
6. Report Viewing: Allow users to view previously submitted reports.
7. Location-Based Reports: Allow users to view reports according to selected campus locations.
8. Electricity Status: Display the latest available reported electricity status for a selected location.
9. Report Updates: Allow authorized users to update the status of reports.
10. Report Status Identification: Distinguish between active, resolved, and unverified reports.

8. Non-Functional Requirements

 How well must it operate?

1. Usability

The platform should be simple, understandable, and easy to navigate, even for users with limited technical knowledge.

2. Performance

The system should load reports and display electricity information within a reasonable time.

3. Reliability

Submitted reports should be stored correctly and remain accessible to users.

4. Security

The system should protect user information and prevent unauthorized modification of reports.

5. Scalability

The system should be designed to support additional users and campus locations in the future.

6. Availability

The platform should be accessible whenever users need it, subject to internet availability and system maintenance.

7. Maintainability

The system should be structured so that developers can identify problems, fix errors, and introduce improvements without unnecessarily affecting existing features.

 9. Scope and Priorities (MVP)

 What is included in the MVP?

The Minimum Viable Product (MVP) is the first version of the system. It will focus on the most important features needed to address the identified problem.

 High Priority — Initial Version

- Submitting electricity outage reports.
- Selecting the affected campus location.
- Adding descriptions to reports.
- Recording report dates and times.
- Viewing existing outage reports.
- Checking the latest reported electricity status.
- Updating report statuses through authorized users.

 Medium Priority — Future Improvements

- User account registration and login.
- Notifications for new outage reports.
- Location-based filtering.
- An administrator dashboard.
- Report history and statistics.

 Low Priority — Long-Term Improvements

- Integration with official university electricity systems, if access is available.
- Automated electricity monitoring.
- Advanced outage analytics.
- Predictive electricity availability information.

These future improvements will not be included in the initial MVP.

 Out of Scope

The first version will not directly control electricity supply, repair electrical infrastructure, or guarantee that electricity will be restored.

Its purpose is to provide information through user-submitted reports and authorized status updates.

 10. Acceptance Criteria

 How do we verify features?

A feature will be considered acceptable when it meets its defined conditions.

1. Outage Reporting

- A user can select a campus location.
- A user can enter a description of the outage.
- The system records the date and time.
- The report is successfully saved.

2. Viewing Reports

- Users can access previously submitted reports.
- Each report displays its location and submission time.
- Reports can be identified by their status.

3. Checking Electricity Status

- Users can select a campus location.
- The system displays available reports for that location.
- The latest available reported status is clearly displayed.

4. Updating Reports

- Authorized users can update a report's status.
- The updated status is saved.
- Other users can view the updated information.

5. Report Identification

- Reports marked as unverified are distinguishable from reviewed reports.
- Resolved reports are distinguishable from active reports.

 11. Assumptions and Open Questions

 What remains unconfirmed?

The proposed system is based on the assumption that students would find a centralized electricity reporting platform useful.

However, some questions still require further investigation:

1. Which specific campus locations should be supported in the first version?
2. Will users need to create accounts before submitting reports?
3. Who will be responsible for reviewing and verifying submitted reports?
4. How will the system prevent false or duplicate reports?
5. Should students be allowed to report when electricity has been restored?
6. Will university management participate in providing official electricity updates?
7. How frequently should outdated reports be reviewed or marked as resolved?
8. Should the system support anonymous reports?

 Risks and Limitations

**Inaccurate Reports:** Users may submit incorrect or misleading information. Report review and verification procedures may help reduce this problem.

**Outdated Information:** Reports may remain visible after electricity has returned. Timestamps and status updates will help users understand how recent the information is.

**Limited Participation:** The system may not be useful if very few students participate. Reporting should be simple and accessible.

**Internet Access:** Users need an internet connection to access the platform.

**Verification Challenges:** Without official electricity information, the system may not always be able to confirm whether a report is accurate.

 Conclusion

The Campus Electricity Monitoring and Reporting System aims to address the difficulty students experience when trying to obtain information about electricity availability across campus.

Initial interviews suggest that students rely on informal communication to understand electricity conditions and that a centralized reporting platform could make this process easier.

By focusing on outage reporting, location selection, report viewing, and status updates, the proposed MVP provides a practical starting point for addressing the identified problem.

Further research, interviews, and user feedback will help validate the proposed features and guide future development.
