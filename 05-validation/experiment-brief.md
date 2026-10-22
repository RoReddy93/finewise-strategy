# The Validation · FinWise

> Module 5 · Experimentation Methods. The experiment brief that tests the bet.

## Method

**Method:** Multi-Armed Bandit

**Why:** We are optimizing for trial to paid conversion while improving retention. So splitting traffic equally for a certain duration and waiting to optimize is a potential churn event. Hence, we use MAB to dynamically shift the traffic to the better performing experience and continue optimizing the traffic to the best performing variant against the metrics

_____

## Hypothesis + primary metric

If we can get the new users to generate financial insights from the product faster, then we expect to see improved trial to paid conversion and also better retention

**Primary metric:** Weekly active sessions per user, target: A 15% increase in weekly active sessions within two weeks

_Experiment: Improving existing user retention, Improve trial to paid conversion for new users while improving retention amongst existing users_

_Testing Allow users to confirm the transactions and identify the highest spend category based on the confirmed transactions for users to set budgets accordingly. This will happen through weekly streak reminder notification, no reminder, and reminder sent via an email on Users who have imported their financial data but haven't completed the audit of their transactions. Current experience: Users only see a list of transactions after they import their financial data._

_Predicted outcome: Weekly active sessions increase as MAB identifies and scales the highest-performing prompt variant within two weeks.. If successful: Lock in the winning prompt variant and test new variables such as timing and frequency.. If unsuccessful: Review if the reminders created friction. Test a different re-engagement mechanism entirely.._

_____

## Guardrail + read date

- **Guardrail:** Product CSAT shouldn't drop by more than 5pp
- **Read date:** 14 days after launch, on the 15th, no earlier

_____
