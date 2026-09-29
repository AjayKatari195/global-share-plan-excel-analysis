# Data Dictionary

## Employee Master
| Field | Description |
|---|---|
| Employee_ID | Unique employee identifier |
| Country | Country of employment |
| Department | Employee business function |
| Plan_Type | Share-plan type |
| Employment_Status | Current simulated employment status |
| Grant_Date | Simulated grant date |
| Vesting_Date | Simulated vesting date |

## Share Transactions
| Field | Description |
|---|---|
| Transaction_ID | Unique transaction identifier |
| Employee_ID | Employee linked to transaction |
| Transaction_Type | Grant, vesting, exercise, sale or cancellation |
| Transaction_Date | Transaction date |
| Shares | Number of shares |
| Share_Price_GBP | Simulated share price |
| Gross_Value_GBP | Shares × share price |
| Expected_Tax_GBP | Simulated expected tax |
| Approval_Status | Simulated approval control |

## Payroll
| Field | Description |
|---|---|
| Transaction_ID | Transaction being reconciled |
| Employee_ID | Employee linked to payroll record |
| Payroll_Tax_GBP | Simulated payroll tax deduction |
