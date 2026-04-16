# Login Test Cases

## TC-001 Valid login
**Precondition:** User is registered and active.

**Steps:**
1. Open login page
2. Enter valid username
3. Enter valid password
4. Click login

**Expected result:**
User is logged in successfully and redirected to dashboard.

---

## TC-002 Invalid password
**Precondition:** User exists.

**Steps:**
1. Open login page
2. Enter valid username
3. Enter incorrect password
4. Click login

**Expected result:**
Error message is displayed and user is not logged in.

---

## TC-003 Empty password
Steps:
1. Enter username
2. Leave password empty
3. Click login

Expected:
Validation error is shown

---

## TC-004 Empty username
Steps:
1. Leave username empty
2. Enter password
3. Click login

Expected:
Validation error is shown

---

## TC-005 Empty fields
Steps:
1. Leave username empty
2. Leave password empty
3. Click login

Expected:
System shows required field errors

---

## TC-006 Wrong username
Steps:
1. Enter invalid username
2. Enter password
3. Click login

Expected:
Login fails and error message is displayed