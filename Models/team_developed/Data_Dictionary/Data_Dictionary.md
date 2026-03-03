# Data Dictionary

| Entity            | Attribute            | Data Type | Max Length | Description / Constraints                          |
|-------------------|----------------------|-----------|------------|---------------------------------------------------|
| StaffAccount      | Staff_ID             | Text      | 10         | Alphanumeric unique staff ID                      |
| StaffAccount      | Staff_Name           | Text      | 100        | Full name of staff member                         |
| StaffAccount      | Staff_Role           | Enum      | -          | Values: Admin \| Staff                            |
| StaffAccount      | Account_Status       | Enum      | -          | Values: Active \| Inactive                        |
| Courses           | Course_ID            | Text      | 10         | Unique course identifier                          |
| Courses           | Course_Name          | Text      | 100        | Full name of the course                           |
| Subjects          | Subject_ID           | Text      | 10         | Unique subject identifier                         |
| Subjects          | Subject_Name         | Text      | 100        | Name of the subject                               |
| Subjects          | Assigned_Staff_ID    | Text      | 10         | FK → StaffAccounts.Staff_ID                       |
| Subjects          | Course_ID            | Text      | 10         | FK → Courses.Course_ID                            |
| Timetable         | Slot_ID              | Text      | 10         | Unique timetable slot identifier                  |
| Timetable         | Date / Day           | Date      | -          | Scheduled date or day of week                     |
| Timetable         | Start_Time / End_Time| Time      | -          | Start and end time of the slot                    |
| Timetable         | Location             | Text      | 100        | Room or venue for the slot                        |
| Timetable         | Assigned_Staff       | Text      | 10         | FK → StaffAccounts.Staff_ID                       |
| Timetable         | Approval_Status      | Enum      | -          | Values: Draft \| Approved \| Published            |
| Students          | Student_ID           | Text      | 10         | Unique student identifier                         |
| Students          | Student_Name         | Text      | 100        | Full name of student                              |
| Students          | Course_ID            | Text      | 10         | FK → Courses.Course_ID                            |
| Student_Attendance| Attendance_Record_ID | Text      | 10         | Unique attendance record ID                       |
| Student_Attendance| Student_ID           | Text      | 10         | FK → Students.Student_ID                          |
| Student_Attendance| Slot_ID              | Text      | 10         | FK → Timetable.Slot_ID                            |
| Student_Attendance| Attendance_Status    | Enum      | -          | Values: Present \| Absent \| Excused              |
| AdminAccount      | Admin_ID             | Text      | 10         | Unique admin identifier                           |
| AdminAccount      | Admin_Name           | Text      | 100        | Full name of admin                                |
| Roles             | Role_ID              | Text      | 10         | Unique role identifier                            |
| Roles             | Role_Name            | Enum      | -          | Values: Admin \| Staff                            |