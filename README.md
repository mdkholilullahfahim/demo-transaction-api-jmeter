# demo-transaction-api-jmeter

## This repository contains a JMeter test plan (test_plan.jmx) to simulate the following positive test scenario:
 - Admin creates an agent and a customer.
 - Deposit 2000 TK to the agent from the system account.
 - Deposit 1000 TK to the customer from the agent account.
 - Check balance from the customer account.
 - Withdraw 500 TK from the customer account.
 - Payment of 200 TK from the customer account to a merchant account.

## Prerequisites
- Apache JMeter 5.4.1 or later
- Java 8 or later

  
## Test Plan Structure
The test plan is structured as follows:

Admin Actions
- Create Agent
- Create Customer

Transactions
- Deposit 2000 TK to Agent from System Account
- Deposit 1000 TK to Customer from Agent Account

Customer Actions
- Check Balance
- Withdraw 500 TK
- Payment of 200 TK to Merchant

  ## Setup Instructions
  Clone the Repository
  - git clone https://github.com/your-username/your-repo.git cd your-repo



