The study utilized a weighted additive scoring model to transform categorical survey data into continuous variables. By aggregating specific pain points into the OBVI and risk factors into the CREI, we were able to perform a Pearson correlation analysis. 
The resulting r = 0.48 demonstrates that as organizational friction (OBVI) increases, the likelihood of contractual failure (CREI) rises significantly. 
The ARDI was used to validate that the highest-burden organizations are also those most in need of the proposed Agentic BPM framework.

**1. Contractual Risk Exposure Index (CREI)**
Measures the legal and financial vulnerability of the organization

| Variable            | Category / Condition | Score                                        | Notes                 |
| ------------------- | -------------------- | -------------------------------------------- | --------------------- |
|Deadline Miss Score  | Never                | 0                                            |                       |
|                     | Once / Twice         | 1                                            |                       |
|                     | Regularly            | 2                                            |                       |
|Dispute Loss Score   | No                   | 0                                            |                       |
|                     | Yes                  | 1                                            |                       |
| Total Score         | —                    | = (Deadline Miss Score + Dispute Loss Score) | Sum of both variables |
Formula: CREI = {Deadline Miss Score} + {Dispute Loss Score}
**2. Operational Burden & Visibility Index (OBVI)**
Quantifies "Enterprise Friction" and process inefficiency

| Source Variable / Question  | Value Assignment (Points)                                | Logic / Calculation                               |
| --------------------------- | -------------------------------------------------------- | ------------------------------------------------- |
| License Tracking Difficulty | Raw Likert Scale: 1 to 5                                 | Directly use the Likert value                     |
| Cost Visibility Gap         | Clear overview: 0; Partially complete: 1; No analysis: 2 | Assign based on visibility level                  |
| Admin Burden Score          | Not burdensome: 0; Somewhat: 1; Quite: 2; Extremely: 3   | Assign based on perceived administrative workload |
| SLA Compliance (Difficulty) | Likert Scale: 1 to 5                                     | Directly use the Likert value                     |
| Total Score                 | —                                                        | Sum of all four variables                         |
OBVI = {Tracking Difficulty} + {Cost Visibility} + {Admin Burden} + {SLA Difficulty}

**3. Automation Readiness & Demand Index (ARDI)**
Measures the potential impact of Agentic BPM implementation

| Aspect Selected    | Points                  | Calculation                  |
| ------------------ | ----------------------- | ---------------------------- |
| Renewal Reminders  | 1 if selected; 0 if not |                              |
| Usage vs. Contract | 1 if selected; 0 if not |                              |
| SLA Tracking       | 1 if selected; 0 if not |                              |
| GDPR Checks        | 1 if selected; 0 if not |                              |
| Total Score        | —                       | Sum of all binary selections |

ARDI = \sum ({Selected Aspects})


