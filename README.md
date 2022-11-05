# Bugs
In this repository are some of the Defect Reports (Bugs) that I wrote while doing the course at Manual Tester Course (Coderslab-eJobs Group) and are imported from JIRA.
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
#
#### The Store Information section is incomplete
**Description**  The "Store Information" from the bottom-right of the home page doesn't have a complete address, it displays just the country.

**Affected version:**  My store 2.0

**Environment:** https://courses-presta-prod.visuality.pl/index.php

**Steps to reproduce:**
1. On the My Store homepage, scroll down until the "The "Store information" section is visible.

**Expected behaviour:** The "Store information" section displays the complete address.

**Actual behaviour:** The "Store information" section displays only the country.

**Priority:** P2

**Severity:** Medium

**Repro-rate:** 10/10

![store info](https://user-images.githubusercontent.com/117184407/199990077-9dd367ae-25ca-4dee-b4a1-de02dedf8813.png)
#
#### "Subject" field - the subject cannot be selected
**Description**  When the user clicks on the "Subject" field from the "Contact us" page, the drop down list doesn't open and the subject cannot be selected.

**Affected version:**  My store 2.0

**Environment:** https://courses-presta-prod.visuality.pl/index.php

**Steps to reproduce:**
1. Press on the "Contact us" button (top-left) from the My Store homepage.
2. Click on the "Subject" field.

**Expected behaviour:** When the user clicks on the "Subject" field it displays a drop down list and the subject can be selected successfully.

**Actual behaviour:** When the user clicks on the "Subject" field the drop down list doesn't open and the subject cannot be selected.

**Priority:** P2

**Severity:** Medium

**Repro-rate:** 10/10

![subject cannot be sel](https://user-images.githubusercontent.com/117184407/200003499-84b59689-1457-4e81-9a80-1e158144c837.png)
---

#### "Payment" is not functional
**Description**  In the "Payment" step from the "Proceed to checkout", there is no payment method available.

**Affected version:**  My store 2.0

**Environment:** https://courses-presta-prod.visuality.pl/index.php

**Steps to reproduce:**
1. Add one item in the cart.
2. Click on the "Proceed to checkout" button.
3. Repeat step 2.
4. Insert the email in the "Email" field and the password in the "Password" field.
5. Click on the "Continue" button. 
6. Repeat step 5.
7. Choose a shipping method.
8. Repeat step 5. 
9. The "Payment" step is displayed

**Expected behaviour:** In the "Payment" step from the "Proceed to checkout" are displayed payment methods. 

**Actual behaviour:** In the "Payment" step from the "Proceed to checkout", there is no payment method available and the user cannot make the payment.

**Priority:** P1

**Severity:** Major

**Repro-rate:** 10/10

![Payment method](https://user-images.githubusercontent.com/117184407/200046592-5eabf20b-0ae1-433e-b2e7-6c472049c750.png)
----
#### "Hummingbird Printed T-shirt" description product

**Description**  The first row from the "Hummingbird Printed T-shirt" product description is in a very light grey and it can't be read. 

**Affected version:**  My store 2.0

**Environment:** https://courses-presta-prod.visuality.pl/index.php

**Steps to reproduce:**
1. Click on the "Hummingbird Printed T-shirt" product from the "Popular Product" section (My Store homepage).
2. Scroll down until the "Description".

**Expected behaviour:** The description of the "Hummingbird Printed T-shirt" is in black color and it can be read. 

**Actual behaviour:** The "Hummingbird Printed T-shirt" product has the first row from the product description in a very light grey and it cannot be read.

**Priority:** P2

**Severity:** Medium

**Repro-rate:** 10/10

![Hummingbird Product description](https://user-images.githubusercontent.com/117184407/200056459-e5185bac-e3fb-4eb6-bb35-40b99194d2e0.png)
----

#### Logo is covering the description
**Description**  The t-shirt logo from the "Clothes" page's banner is covering the text from the banner.

**Affected version:**  My store 2.0

**Environment:** https://courses-presta-prod.visuality.pl/index.php

**Steps to reproduce:**
1. Click on the "Clothes" button from the homepage.

**Expected behaviour:** The t-shirt logo is not covering the text from the banner, all the elements are positioned as per bussiness requirements. 

**Actual behaviour:** The t-shirt logo from the "Clothes" page's banner is covering the text from the banner.

**Priority:** P3

**Severity:** Minor

**Repro-rate:** 10/10

![clothes banner site](https://user-images.githubusercontent.com/117184407/200107148-91507a35-66f7-4a5c-96a3-833d915caf80.png)

#### "Hummingbird Cushion" is displayed twice

**Description**  The "Hummingbird Cushion" product is displayed twice, the second one has the title "Copy of Hummingbird Cushion".

**Affected version:**  My store 2.0

**Environment:** https://courses-presta-prod.visuality.pl/index.php

**Steps to reproduce:**

1. Click on the "Accessories" button from the homepage
2. Scroll down to the the "Copy of the Hummingbird Cushion"

**Expected behaviour:** The "Hummingbird Cushion" product is displayed once.

**Actual behaviour:** The "Hummingbird Cushion" is displayed twice, the second one has the title "Copy of Hummingbird Cushion".

**Priority:** P2

**Severity:** Medium

**Repro-rate:** 10/10

![hummingbird twice](https://user-images.githubusercontent.com/117184407/200108405-7f620fcc-2c72-4f08-8219-941f2ccbf511.png)
-------------

#### "The best is yet to come" twitter button not functioning

**Description**  The twitter button from "The best is yet to come" framed poster is not functioning, when it's clicked it displays an unavailable page. 

**Affected version:**  My store 2.0

**Environment:** https://courses-presta-prod.visuality.pl/index.php

**Steps to reproduce:**

1. Click on the "Art" button from the homepage.
2. Click on the "The best is yet to come" framed poster.
3. Click on the "Twitter" button next to "Share".

**Expected behaviour:** The twitter button from "The best is yet to come" framed poster is functioning and the user can share the product on his twitter account.

**Actual behaviour:** The twitter button from "The best is yet to come" framed poster is not functioning, when it's clicked it displays an unavailable page. 

**Priority:** P2

**Severity:** Medium

**Repro-rate:** 10/10

![Twitter button](https://user-images.githubusercontent.com/117184407/200110032-ff2c87d4-902d-46f5-a579-c2d579c83bb4.png)

![Unavailable page](https://user-images.githubusercontent.com/117184407/200110037-6d579e1e-f953-42dd-9d24-e5a3019f96a7.png)





