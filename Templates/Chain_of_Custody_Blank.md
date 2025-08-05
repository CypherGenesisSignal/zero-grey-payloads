# Chain of Custody Log

| Entry | Date/Time           | Handler        | Action/Context           | Notes           |
|-------|---------------------|----------------|--------------------------|-----------------|
| 1     | YYYY-MM-DD HH:MM    | [Name/Handle]  | Artifact Created         | Initial event   |
| 2     | YYYY-MM-DD HH:MM    | [Name/Handle]  | Artifact Reviewed        | QA pass/fail    |
| 3     | YYYY-MM-DD HH:MM    | [Name/Handle]  | Artifact Transferred     | To [location]   |
| ...   | ...                 | ...            | ...                      | ...             |

*This log is appended, never overwritten. Critical for audit and Blacklock protocols.*

