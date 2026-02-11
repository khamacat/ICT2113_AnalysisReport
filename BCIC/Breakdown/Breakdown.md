# Breakdown of Biz-Ops Requirements

| IRC Category                | Incongruity Detected                                                                 | Affected Reqr(s)                                | IRC Check Type       |
|-----------------------------|---------------------------------------------------------------------------------------|-------------------------------------------------|----------------------|
| Ambiguous / Not testable    | What kind of configuration and access must be done for the requirement to be satisfied? | BAA - L1.1 Admin Account                        | Contextual           |
| Inconsistent with another   | Functional overlap with requirement BAA - L1.1 Admin Account                           | BSA - L1.2 Staff Access Management              | Contextual           |
| Suspected incompleteness    | Assumes authentication exists and roles are defined. What are the roles and rules?     | BSA - L1.2 Staff Access Management              | Contextual           |
| Not testable / Ambiguous    | What academic administration functions must staff access for log-in to be satisfied?   | BL - L1.3 Log-in                                | Contextual           |
| Suspected incompleteness    | Automatic scheduling does not define constraints or conflict priorities                | BAS - L1.2 Automatic scheduling                 | Contextual           |
| Unseemly Prioritized        | Marked desirable, but mismatched with description (“The system shall…”)                | BAT - L1.4 Approve Timetable                    | Imperative           |
| Unseemly Prioritized        | Marked desirable, but mismatched with description (“The system shall…”)                | BH - L1.2 Track student attendance history      | Imperative           |
| Suspected incompleteness    | No backup/alternative suggested in case of QR failure. Business constraints unclear. Are there any business constraints when taking attendance to ensure verifiability?    | BRA - L1.1 Record Attendance                    | Contextual           |
| Unseemly Prioritized        | Marked desirable, but mismatched with description (“The system shall…”)                | BAS - L1.1 View attendance summaries            | Imperative           |
| Suspected incompleteness    | No business rules defined for conflict resolution when overriding staff availability   | BS - L1.3 Assign staff to slots                 | Contextual           |
| Suspected incompleteness / Unseemly Prioritized | Requirement doesn’t define allowed customisations. Marked ‘Tolerable’, mismatched with description. | BP - L1.4 Customise Profile | Imperative / Continuance |
| Ambiguous / Inconsistent    | Different terminologies used for roles (Admin, Staff, Teaching Staff). Which terms align? | BRS - L1.3 Register staff, BC - L1.1 Create slot, BRA - L1.1 Record Attendance, BAS - L1.1 View attendance summaries | Contextual |
| Ambiguous / Not Testable    | Requirements describe what the admin must do, not what the system must enforce.        | All requirements                                | Contextual           |
