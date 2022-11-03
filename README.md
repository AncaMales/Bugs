# Bugs
In this repository are Defect Reports (Bugs) that I wrote while doing the course at Manual Tester Course (Coderslab-eJobs Group) and are imported from JIRA.
#
#### "Subscribe" field
**Description**  The "Subscribe" field is accepting false formats of email address ( example: abcdef@abcdef.com)

**Affected version:**  My store 2.0

**Environment:** https://courses-presta-prod.visuality.pl/index.php

**Steps to reproduce:**
1. Scroll down in the homepage until the "Subscribe" field is visible
2. Select the "Subscribe" field.
3. Introduce an invalid e-mail.

**Expected behaviour:** Display an error message that the address email is invalid.

**Actual behaviour:** The field accepts any combination of words that looks like an email.

**Priority:** P2

**Severity:** Medium

**Repro-rate:** 10/10

**Test data:** abcdef@abcdef.com

![Subscribe](https://user-images.githubusercontent.com/117184407/199756296-7ff4ab14-77ca-440c-812d-d33db5da5256.png)
