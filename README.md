# DMoney Performance Testing

## Tool
Apache JMeter 5.6.3

## Scenario

### Deposit
- 5 Agents perform deposits for customers

### Send Money
- 5 Customers send money to other customers

### Payment
- 5 Customers make payments to merchants

## Configuration

- Threads: 5
- Ramp-Up Time: 120 seconds
- Loop Count: 1

## Files

- dmoney.jmx
- deposit.csv
- sendMoney.csv
- payment.csv

## Request Summary

![Request Summary](screenshots/request_summary.png)

## Statistics

![Statistics](screenshots/statistics.png)