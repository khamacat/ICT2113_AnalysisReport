# Requirements

## Registration and Staff Onboarding (BR - L0)
- **BAA - L1.1 Admin Account (Essential)**  
  Administrative staff shall be responsible for managing and maintaining system configuration and access.
- **BSA - L1.2 Staff Access Management (Essential)**  
  The system shall allow administrative staff to manage staff access to academic administration functions.
- **BL - L1.3 Log-in (Essential)**  
  Staff shall be able to access academic administration functions according to their role.
- **BAM - L1.5 Account Management (Essential)**  
  The system shall provide functionality to view all staff accounts and profiles registered.

## Course Administration (BC - L0)
- **BCM - L1.1 Course & Subject Management (Essential)**  
  The system shall support setup and organisation of all courses and their related subjects.
- **BRE - L1.2 Student Registration & Enrollment (Essential)**  
  The system shall register students and assign them to the appropriate courses and subjects.
- **BRS - L1.3 Register Staff (Essential)**  
  The system shall assign registered teaching staff to the appropriate courses and subjects.

## Timetable Scheduling (BT - L0)
- **BC - L1.1 Create Slot (Essential)**  
  The system shall allow creation of timetable slots by specifying course, subject, date/day, start time, end time (or duration), and location.

---

# IRC Checks

| IRC Category | Incongruity Detected | Affected Requirement(s) | IRC Check Type |
|--------------|----------------------|-------------------------|----------------|
| Ambiguous / Not testable | What kind of configuration and access must be done for the requirement to be satisfied? | BAA - L1.1 Admin Account | Contextual |
| Inconsistent with another requirement | Functional overlap with requirement BAA - L1.1 Admin Account | BSA - L1.2 Staff Access Management | Contextual |
| Suspected incompleteness | Assumes that authentication exists and roles and authorisation rules are defined. What are the roles and authorisation rules? | BSA - L1.2 Staff Access Management | Contextual |
| Not testable / Ambiguous | What kind of academic administration functions must the staff access for the log-in requirement to be satisfied? | BL - L1.3 Log-in | Contextual |
| Suspected incompleteness | Automatic scheduling does not define which constraints govern slot generation or how conflicts are prioritized | BAS - L1.2 Automatic Scheduling | Contextual |
| Unseemly Prioritized | Marked desirable however mismatched with description (“The system shall…”) | BAT - L1.4 Approve Timetable | Imperative |
| Unseemly Prioritized | Marked desirable however mismatched with description (“The system shall…”) | BH - L1.2 Track Student Attendance History | Imperative |
| Suspected incompleteness | No backup/alternative suggested in case of QR failure | BRA - L1.1 Record Attendance | Contextual |
| Unseemly Prioritized | Marked desirable however mismatched with description (“The system shall…”) | BAS - L1.1 View Attendance Summaries | Imperative |
| Suspected incompleteness / Not Testable | No business rules defined for conflict resolution when overriding staff availability | BS - L1.3 Assign Staff to Slots | Contextual |
| Suspected incompleteness / Unseemly Prioritized | Requirement doesn’t define what customizations the system should allow. Marked ‘Tolerable’ but mismatched with description (“The system shall…”) | BP - L1.4 Customise Profile | Imperative / Continuance |
| Ambiguous / Inconsistent | Different terminologies used for roles (Administrative staff, Admin, Staff, Teaching Staff). Which terms refer to the same roles? | BRS - L1.3 Register Staff, BC - L1.1 Create Slot, BRA - L1.1 Record Attendance, BAS - L1.1 View Attendance Summaries | Contextual |