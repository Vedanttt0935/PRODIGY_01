# 🧪 Test Cases – Simple Calculator Application
## ✅ Valid Input Test Cases
### 🔹 TC01 – Add two positive integers
- **Test Case ID**: TC01  
- **Test Description**: Verify addition of two positive integers  
- **Preconditions**: Calculator is open and ready for input  
- **Test Steps**:
  1. Enter `8`
  2. Press `+`
  3. Enter `5`
  4. Press `=`
- **Expected Result**: Display shows `13`

---

### 🔹 TC02 – Subtract a smaller number from a larger number
- **Test Case ID**: TC02  
- **Test Description**: Verify subtraction of two positive integers  
- **Preconditions**: Calculator is open  
- **Test Steps**:
  1. Enter `20`
  2. Press `-`
  3. Enter `7`
  4. Press `=`
- **Expected Result**: Display shows `13`

---

### 🔹 TC03 – Multiply a negative and a positive number
- **Test Case ID**: TC03  
- **Test Description**: Verify multiplication of a negative and a positive number  
- **Preconditions**: Calculator is open  
- **Test Steps**:
  1. Enter `-4`
  2. Press `×`
  3. Enter `6`
  4. Press `=`
- **Expected Result**: Display shows `-24`

---

### 🔹 TC04 – Divide two positive numbers
- **Test Case ID**: TC04  
- **Test Description**: Verify division of two positive numbers  
- **Preconditions**: Calculator is open  
- **Test Steps**:
  1. Enter `25`
  2. Press `÷`
  3. Enter `5`
  4. Press `=`
- **Expected Result**: Display shows `5`

---

### 🔹 TC05 – Add two decimal numbers
- **Test Case ID**: TC05  
- **Test Description**: Verify addition of decimal numbers  
- **Preconditions**: Calculator is open  
- **Test Steps**:
  1. Enter `2.5`
  2. Press `+`
  3. Enter `3.75`
  4. Press `=`
- **Expected Result**: Display shows `6.25`

---

### 🔹 TC06 – Apply BODMAS rule
- **Test Case ID**: TC06  
- **Test Description**: Verify BODMAS rule is followed  
- **Preconditions**: Calculator supports order of operations  
- **Test Steps**:
  1. Enter `2 + 3 × 4`
  2. Press `=`
- **Expected Result**: Display shows `14`  
  _(`3×4 = 12`, then `2+12 = 14`)_

---

## ❌ Invalid Input Test Cases

### 🔹 TC07 – Divide by zero
- **Test Case ID**: TC07  
- **Test Description**: Division by zero should show an error  
- **Preconditions**: Calculator is open  
- **Test Steps**:
  1. Enter `9`
  2. Press `÷`
  3. Enter `0`
  4. Press `=`
- **Expected Result**: Display shows `"Cannot divide by zero"` or `"Infinity"`

---

### 🔹 TC08 – Input non-numeric characters
- **Test Case ID**: TC08  
- **Test Description**: Input of alphabets should be invalid  
- **Preconditions**: Calculator is open  
- **Test Steps**:
  1. Try entering `A`
- **Expected Result**: Input is rejected or error shown: `"Invalid input"`

---

### 🔹 TC09 – Multiple decimal points in a number
- **Test Case ID**: TC09  
- **Test Description**: Multiple decimal points should be restricted  
- **Preconditions**: Calculator is open  
- **Test Steps**:
  1. Enter `3.1.4`
- **Expected Result**: Show error or auto-correct to `3.14`

---

### 🔹 TC10 – Special characters as input
- **Test Case ID**: TC10  
- **Test Description**: Special characters should not be accepted  
- **Preconditions**: Calculator is open  
- **Test Steps**:
  1. Try entering `@` or `#`
- **Expected Result**: Display shows `"Invalid input"` or blocks the entry
Added test cases for calculator application
Add comment
