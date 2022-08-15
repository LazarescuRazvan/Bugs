# Bugs Raports

Below are some Bugs raports that I wrote while working on previous projects.

------

**Priority & Severity:**

P1 - High

**Description:**

When you put more than maximum letters or characters in the “Name” field it’s allowed and name it’s displayed outside of the field and give us a visual bug(see the video).

**Steps to reproduce:**

1. Go to https://www.globalsqa.com/angularJs-protractor/BankingProject/#/manager

2. Go to  https://www.globalsqa.com/angularJs-protractor/BankingProject/#/manager/addCust

3. Write more than 30 characters in the “Name” field.

4. Go to https://www.globalsqa.com/angularJs-protractor/BankingProject/#/customer

5. Select the last account created in the list.

**Expected result:**

When you create a customer account the software doesn’t have to let you introduce more than the maximum characters allowed.

**Actual result:**

Software allow you to introduce more than the maximum characters allowed and that make a visual bug when you select that account.Our name content overlap with other content.
