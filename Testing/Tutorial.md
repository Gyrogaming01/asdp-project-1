# Acceptance Testing

## Example 1

| Test Case | Marital Status | Carer | PAYE | Expected Output (Tax Credits) | Actual Output | Pass |
| --------- | -------------- | ----- | ---- | -----------------------------:| -------------:| ---- |
| 1 | Single  | No  | No  | 1830 |  |  |
| 2 | Single  | No  | Yes | 3660 |  |  |
| 3 | Single  | Yes | No  | 2730 |  |  |
| 4 | Single  | Yes | Yes | 4560 |  |  |
| 5 | Married | No  | No  | 3660 |  |  |
| 6 | Married | No  | Yes | 5490 |  |  |
| 7 | Married | Yes | No  | 4560 |  |  |
| 8 | Married | Yes | Yes | 6390 |  |  |

## Example 2

Calculate PRSI & Health Contributions

| Test Case | Income | Expected Output (Tax) | Actual Output | Pass |
| --------- | ------:| ---------------------:| -------------:| ---- |
| 1 | 0      | 0       |  |  |
| 2 | 10000  | 600     |  |  |
| 3 | 40000  | 2400    |  |  |
| 4 | 50000  | 3000    |  |  |
| 5 | 50001  | 3000.02 |  |  |
| 6 | 75000  | 3500    |  |  |
| 7 | 100000 | 4000    |  |  |
| 8 | 100001 | 4000.25 |  |  |
| 9 | 150000 | 5250    |  |  |
