# Week 0 — Billing and Architecture

## Lucid Chart

### Conceptual Diagram

[Link](https://lucid.app/documents/view/0af05386-47f0-4388-9e1a-4c6b165cc717)

![](week0_files/0_Conceptual_diagram.png)

### Logical Architectual Diagram

[Link](https://lucid.app/documents/view/c56dae33-e3ea-41e1-b356-f1f7e46b8f5f)

![](week0_files/1_Lucid_chart.png)

---

## Create a Budget

1. Go to the link below and click `Create Budget`.

   https://us-east-1.console.aws.amazon.com/billing/home#/budgets#/home

2. Enter the following Setup:

   1. Budget Setup - `Use a template (simplified)` 
   
   2. Templates - `Monthly cost budget`
   
   3. Enter the budget name
   
   4. Enter your budgeted amount
   
   5. Enter the email recipients
   
   ![](week0_files/2_budget.png)
   
   ![](week0_files/3_budget.png)
   
3. Click the `Create Budget` to continue

And now we have a budget setup

![](week0_files/4_budget.png)

## Create a Budget Alarm

1. Click the budget created, and then click the `edit`.
   
   ![](week0_files/5_alarm.png)
   
2. Leave the `Set your budget` as is for now and click `next`.

   ![](week0_files/6_alarm.png)

3. In the `Configure Alerts`, we can now set up the budget alarm. We can have different kinds of alarm set up here.
   
   ![](week0_files/7_alarm.png)

   ![](week0_files/8_alarm.png)

   ![](week0_files/9_alarm.png)

4. We can skip the `attach actions` for now and hit the `next` button.

5. Afterwards, we will review the created budget alarm and then hit `save` button