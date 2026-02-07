# Incongruous Requirements Checklist (IRC)

The IRC is a structured tool used to classify and review requirements that may be problematic. Each column represents a dimension of analysis, with categories that can be applied during requirement review.

---

## Checklist Framework

| Column                | Possible Categories / Values                                                                       |
|-----------------------|----------------------------------------------------------------------------------------------------|
| **Priority Keywords** | Shall (strongest), Must/ Must not, Required to, Applicable, Responsible, Will, Should (weakest)    |
| **Continuance**       | Below, As follows , Following, Listed, In particular, Supported by                                 |
| **IRC Category**      | Inconsistent, Not testable, Unseemly prioritized, Ambiguous, Unverifiable with customer policy, Unrealistic, Suspected incompleteness |
| **Check Type**        | Contextual Review, Imperative Review, Continuance Review, Consistency Check, Testability Check     |
| **Affected Reqr(s)**  | Requirement ID(s) flagged (e.g., BAA - L1.1, BSA - L1.2, BL - L1.3)                                |  |

---

## Usage Notes
- **Step 1:** During requirement elicitation, reviewers select the appropriate **IRC Category** (e.g., Ambiguous).  
- **Step 2:** Identify the **Incongruity Type**, then record the description. 
- **Step 3:** Link the **Affected Requirement(s)** by ID.  
- **Step 4:** Specify the **Check Type** used (e.g., Contextual).  
- **Step 5:** Discuss and resolve incongruities before requirements are finalized in the SRS.  

---

## Example Entry
| IRC Category | Incongruity Type | Affected Reqr(s) | Check Type |
|--------------|------------------|------------------|------------|
| Ambiguous    | What kind of...  | BAA - L1.1 Admin Account | Contextual Review |