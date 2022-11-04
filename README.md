# Bugs
In this repository are Defect Reports (Bugs) that I wrote while doing the course at Manual Tester Course (Coderslab-eJobs Group) and are imported from JIRA.
#
#### "Subscribe" field accepts invalid format of email address
**Description**  When the user introduces an invalid format of email address in the "Subscribe" field and clicks on the "Subscribe" button, the email address is accepted. (example: abcdef@abcdef.com)

**Affected version:**  My store 2.0

**Environment:** https://courses-presta-prod.visuality.pl/index.php

**Steps to reproduce:**
1. Scroll down in the homepage until the "Subscribe" field is visible.
2. Select the "Subscribe" field.
3. Introduce an invalid format of e-mail address.
4. Click on the "Subscribe" button.

**Expected behaviour:** The field displays an error message that the address email is invalid.

**Actual behaviour:** The field accepts any combination of words that looks like an email and displays the message "You have successfully subscribed to this newsletter."

**Priority:** P2

**Severity:** Medium

**Repro-rate:** 10/10

**Test data:** abcdef@abcdef.com

![Subscribe](https://user-images.githubusercontent.com/117184407/199756296-7ff4ab14-77ca-440c-812d-d33db5da5256.png)
#
#### Custom block text is in the Latin language
**Description**  The description of the "Custom text block" from the home page is in Latin language.

**Affected version:**  My store 2.0

**Environment:** https://courses-presta-prod.visuality.pl/index.php

**Steps to reproduce:**
1. On the My Store homepage, scroll down until the "Custom text block" banner is visible.

**Expected behaviour:** The title and the description are in the English language.

**Actual behaviour:** The title is in English language and the description is in the Latin language.

**Priority:** P2

**Severity:** Low

**Repro-rate:** 10/10
![Custom text block](https://user-images.githubusercontent.com/117184407/199785534-effe13c1-45f4-48c3-a360-4e38bba3c51f.png)
#
#### The "20% OFF on CLOTHES" banner doesn't show only the clothes with the reduced price
**Description**  When the user clicks on the "20% OFF ON CLOTHES" banner, it displays the popular products, not only the clothes with 20% off.

**Affected version:**  My store 2.0

**Environment:** https://courses-presta-prod.visuality.pl/index.php

**Steps to reproduce:**
1. On the My Store homepage, scroll down until the "20% OFF ON CLOTHES" banner is visible.
2. Click on the "20% OFF ON CLOTHES" banner

**Expected behaviour:** When it's clicked, the "20% OFF ON CLOTHES" banner displays only clothes with 20% OFF.

**Actual behaviour:** The "20% OFF ON CLOTHES" banner displays the popular products, not only the clothes with 20% off.

**Priority:** P2

**Severity:** Medium

**Repro-rate:** 10/10

![20 off banner](https://user-images.githubusercontent.com/117184407/199985750-b1b29040-56ce-4c9d-8f3f-a6aaf4897da8.png)
![20 off](https://user-images.githubusercontent.com/117184407/199985765-3ba37967-d353-449c-a600-98b99fda1f16.png)


