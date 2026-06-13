# Profile Management Bug Report

## Bug ID: E1AJHM-34

### Title

Profile Management accepts invalid LinkedIn URL and saves successfully

### Severity

Medium

### Priority

Medium

### Module

Profile Management

### Preconditions

* User is logged in.
* User is on Profile page.

### Steps to Reproduce

1. Enter `abc` in LinkedIn URL field.
2. Enter valid values in remaining fields.
3. Click **Save Changes**.

### Expected Result

System should display validation message and prevent save.

### Actual Result

Profile updated successfully message is displayed and data is saved.

### Status

Open

---

## Bug ID: E1AJHM-35

### Title

Profile Management accepts invalid external links and saves successfully

### Severity

Medium

### Priority

Medium

### Module

Profile Management

### Preconditions

* User is logged in.
* User is on Profile page.

### Steps to Reproduce

1. Enter invalid values in GitHub, Portfolio and LeetCode URL fields.
2. Click **Save Changes**.

### Expected Result

System should validate URLs and prevent save.

### Actual Result

Profile updated successfully message is displayed and invalid links are saved.

### Status

Open

---

## Bug ID: E1AJHM-36

### Title

Profile Management accepts whitespace-only external links and saves successfully

### Severity

High

### Priority

High

### Module

Profile Management

### Preconditions

* User is logged in.
* User is on Profile page.

### Steps to Reproduce

1. Enter only spaces in all external link fields.
2. Click **Save Changes**.

### Expected Result

System should display validation message and prevent save.

### Actual Result

Profile updated successfully message is displayed and whitespace-only values are accepted.

### Status

Open
