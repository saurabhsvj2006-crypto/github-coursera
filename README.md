# Simple Interest Calculator

A simple program that calculates simple interest from a principal amount, an annual interest rate and a time period.

## What is Simple Interest?

Simple interest is interest calculated only on the original amount (the principal), not on interest already earned.

## Formula

```
Simple Interest (SI) = (P × R × T) / 100
Total Amount (A)     = P + SI
```

| Symbol | Meaning |
|--------|---------|
| P | Principal amount (the money borrowed or invested) |
| R | Annual rate of interest, in percent |
| T | Time period, in years |

## Example

| Input | Value |
|-------|-------|
| Principal (P) | 10,000 |
| Rate (R) | 5% per year |
| Time (T) | 3 years |

```
SI = (10000 × 5 × 3) / 100 = 1,500
Total Amount = 10000 + 1500 = 11,500
```

## How to Use

1. Enter the principal amount.
2. Enter the annual rate of interest (%).
3. Enter the time period in years.
4. The calculator displays the simple interest and the total amount.

## Sample Code (Python)

```python
principal = float(input("Enter principal amount: "))
rate = float(input("Enter annual rate of interest (%): "))
time = float(input("Enter time in years: "))

interest = (principal * rate * time) / 100
total = principal + interest

print("Simple Interest:", interest)
print("Total Amount:", total)
```

## Author

Saurabh Jagdale, Information Technology, Vishwakarma Institute of Technology (VIT), Pune
