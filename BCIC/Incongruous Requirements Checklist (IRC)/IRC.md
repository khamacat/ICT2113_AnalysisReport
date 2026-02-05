# Incongruous Requirements Checklist (IRC)

The IRC is a structured tool used to classify and review requirements that may be problematic. Each column represents a dimension of analysis, with categories that can be applied during requirement review.

---

## Checklist Framework

| Column              | Possible Categories / Values                                                                 |
|---------------------|-----------------------------------------------------------------------------------------------|
| **IRC Category**    | Ambiguous, Not Testable, Inconsistent, Suspected Incompleteness, Unseemly Prioritized, Continuance |
| **Incongruity Type**| Contextual, Imperative, Functional Overlap, Terminology Conflict, Missing Business Rules       |
| **Affected Reqr(s)**| Requirement ID(s) flagged (e.g., BAA - L1.1, BSA - L1.2, BL - L1.3)                           |
| **Check Type**      | Contextual Review, Imperative Review, Continuance Review, Consistency Check, Testability Check |

---

## Usage Notes
- **Step 1:** During requirement elicitation, reviewers select the appropriate **IRC Category** (e.g., Ambiguous).  
- **Step 2:** Record the **Incongruity Type** (e.g., Functional Overlap).  
- **Step 3:** Link the **Affected Requirement(s)** by ID.  
- **Step 4:** Specify the **Check Type** used (e.g., Contextual Review).  
- **Step 5:** Discuss and resolve incongruities before requirements are finalized in the SRS.  

---

## Example Entry
| IRC Category | Incongruity Type | Affected Reqr(s) | Check Type |
|--------------|------------------|------------------|------------|
| Ambiguous    | Missing detail on configuration and access | BAA - L1.1 Admin Account | Contextual Review |