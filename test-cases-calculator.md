# Calculator Application - Test Cases

## Test Case 1
- **Test Case ID:** TC_01
- **Test Description:** Verify addition of two positive numbers
- **Preconditions:** Calculator app is open
- **Test Steps:**
  1. Enter 5
  2. Click +
  3. Enter 3
  4. Click =
- **Expected Result:** Result should be 8

---

## Test Case 2
- **Test Case ID:** TC_02
- **Test Description:** Verify subtraction with negative result
- **Preconditions:** Calculator app is open
- **Test Steps:**
  1. Enter 3
  2. Click -
  3. Enter 5
  4. Click =
- **Expected Result:** Result should be -2

---

## Test Case 3
- **Test Case ID:** TC_03
- **Test Description:** Verify multiplication of decimal numbers
- **Preconditions:** Calculator app is open
- **Test Steps:**
  1. Enter 2.5
  2. Click ×
  3. Enter 2
  4. Click =
- **Expected Result:** Result should be 5.0

---

## Test Case 4
- **Test Case ID:** TC_04
- **Test Description:** Verify division of two numbers
- **Preconditions:** Calculator app is open
- **Test Steps:**
  1. Enter 10
  2. Click ÷
  3. Enter 2
  4. Click =
- **Expected Result:** Result should be 5

---

## Test Case 5
- **Test Case ID:** TC_05
- **Test Description:** Verify division by zero
- **Preconditions:** Calculator app is open
- **Test Steps:**
  1. Enter 10
  2. Click ÷
  3. Enter 0
  4. Click =
- **Expected Result:** Error message should be displayed

---

## Test Case 6
- **Test Case ID:** TC_06
- **Test Description:** Verify handling of non-numeric input
- **Preconditions:** Calculator app is open
- **Test Steps:**
  1. Enter 'a'
  2. Click +
  3. Enter 5
  4. Click =
- **Expected Result:** Error message should be displayed

---

## Test Case 7
- **Test Case ID:** TC_07
- **Test Description:** Verify BODMAS rule (Operator precedence)
- **Preconditions:** Calculator app is open
- **Test Steps:**
  1. Enter 2 + 3 × 4
  2. Click =
- **Expected Result:** Result should be 14

---

## Test Case 8
- **Test Case ID:** TC_08
- **Test Description:** Verify addition of negative numbers
- **Preconditions:** Calculator app is open
- **Test Steps:**
  1. Enter -5
  2. Click +
  3. Enter -3
  4. Click =
- **Expected Result:** Result should be -8

---
