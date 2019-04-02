# Testing Techniques

## Acceptance Testing
### White Box Testing
Inputs > (Known code) > Outputs
### Black Box Testing
Inputs > (Unknown code) > Outputs

Calculate Game Rental Price

| Test Case | Unit Price | Duration | Status | Expected Output (Cost) | Actual Output | Pass |
| --------- | ----------:| --------:| ------ | ----------------------:| -------------:| ---- |
| 1 | 2 | 1 | Regular    | 2 | 2 | Pass |
| 2 | 2 | 2 | Off Street | 4 | 4 | Pass |
| 3 | 2 | 2 | Regular    | 3 | 4 | Fail |
| 4 | 2 | 1 | Off Street | 2 | 2 | Pass |
| 5 |   |   |            |   |   |      |
