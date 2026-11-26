# Membership metrics: core definitions

State the definition and period every time. Use a 12-month period unless the user says otherwise.

| Metric | Formula | Notes |
| --- | --- | --- |
| Renewal rate | members who renewed ÷ members due to renew in the period | "Due to renew" = membership expired inside the period. Exclude people who died, were expelled or upgraded to life membership, and say so. |
| Lapse rate (some say "churn") | 1 − renewal rate | Some organisations use leavers ÷ members at start; say which one you used. |
| First-year retention | first-year members who renewed ÷ first-year members due for their first renewal | Usually lower than the overall renewal rate. Report it separately. |

## Edge cases to check
- **Duplicates**: de-duplicate on member ID first, then email, before counting.
- **Deaths and life members**: leave them out of "due to renew" and say how many.
- **Grace periods**: a member 30 days past expiry may still renew. Decide whether to count them as lapsed, and say so.
