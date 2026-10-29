# Expected outputs and logical test scenarios

These are **illustrative logical walkthroughs**, not executed software tests. For TC01, assume an empty complaint list and counter = 0. For TC08/TC11, assume WSR0001 exists.

| ID | Scenario | Input | Expected result |
|---|---|---|---|
| TC01 | Valid complaint | Name Mohamed Kamara; Wellington; broken tap; severity 3 | WSR0001, High, Pending |
| TC02 | Missing required field | Blank name | Reject and repeat entry |
| TC03 | Out-of-range severity | 4 | Reject and repeat entry |
| TC04 | Non-integer severity | High | Reject and repeat entry |
| TC05 | Low severity | 1 | Low priority |
| TC06 | Medium severity | 2 | Medium priority |
| TC07 | High severity | 3 | High priority |
| TC08 | Existing report | WSR0001 | Display type, priority, status |
| TC09 | Missing report | WSR9999 | Report Not Found |
| TC10 | Unauthorized update | Invalid credentials | Access Denied |
| TC11 | Authorized update | Valid staff, WSR0001, Resolved | Status Updated Successfully |
| TC12 | Invalid new status | Completed | Reject and repeat status input |
| TC13 | Summary | 2 Pending, 1 In Progress, 2 Resolved | Total 5; correct subtotals |
| TC14 | Invalid menu | 8 | Invalid Selection; redisplay menu |
| TC15 | Exit | 5 | Goodbye; terminate |

**Limitations:** Authentication is conceptual; stored records are in memory. No program was executed.
