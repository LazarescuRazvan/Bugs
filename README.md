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

------


**Priority & Severity:**

P1 - High

**Description:**

When you open the console we have text left(see the photo) and map load error. In mobile mode we have design error when we try to search something that doesn’t exist,our content it’s not show properly.

**Steps to reproduce:**

1. Go to https://fieni.ro/wp-content/themes/education-base/assets/library/bootstrap/css/bootstrap.min.css.map

2. Go to Responsive Mode

3. Select Mobile Mode

**Expected result:*

Console should be clear without errors and text. Content should be displayed complete.

**Actual result:**

Content it’s not displayed complete and console isn’t clear.

![Desktop-screenshot (1) (2)](https://user-images.githubusercontent.com/102883633/184675781-8da1a59d-8bb9-4a75-80c5-e14fe2b91db7.png)

------

**Description:**

**Priority & Severity:**

P6 - Medium

**Description:**

When you use the coffee calculator, we have an image error in the right middle of the page. She stay right  there even when I’m gonna use the cigarette calculator and I have exceeded the daily maximum intake ,after i use firstly coffee calculator.

**Steps to reproduce:**

1. Go to https://www.globalsqa.com/angularJs-protractor/ConsumptionCalculator/

2. Try firstly coffee calculator

3. Look in the right middle of the page

4. Try cigarette calculator until you have exceeded the daily maximum intake

**Expected result:**

When you use coffee calculator you don’t want to see any image error or another visual bugs.

**Actual result:**

Image error are displayed when you use the coffee calculator.



https://user-images.githubusercontent.com/102883633/184676216-7635ac79-4e45-4716-9215-7ec1c4980dc3.mp4

------


**Priority & Severity:**

P1 - High

**Description:**

When you try to access the “Menu” button in mobile mode it’s so difficult because we have another button(“Help“ button) that overlap with “Menu button”. 

**Steps to reproduce:**

1. Go to https://fieni.ro/ 

2. Go to Responsive Mode

3. Select Mobile Mode

4. Try to access “Menu button“

**Expected result:**

“Menu“ button should be accessed easily without overlap with another button.

**Actual result:**

“Menu” button it’s not accessibile in the entire “Menu” area ,when you try to click the “Menu” icon it’s possible to open “Help” menu because it’s overlap with “Menu” button.


https://user-images.githubusercontent.com/102883633/184677091-67ffef5c-cf13-48a6-80e2-0debdd6dc97c.mp4

------


**Priority & Severity:**

P3 - High

**Description:**

When you select “cart” section on a phone,our navbar overlap with page content.

**Steps to reproduce:**

1. Go to https://www.demoblaze.com/cart.html

2. Go to Responsive Mode

3. Select Mobile Mode

**Expected result:**

The content of the navigation must remain fixed and not overlap with the rest of the page.

**Actual result:**

The content of the navigation overlap with the rest of the page and make a visual bug.

![STORE (1)](https://user-images.githubusercontent.com/102883633/184677905-a34186ae-7696-425d-a68a-6949594f450d.png)

