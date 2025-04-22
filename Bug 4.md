# 🐞 Bug Report: Rows Not Changing Color or Status After Configuration Validation

**Module Name:** Employee Central  
**Screen Name:** HRIS Sync 

---

## Title
Rows Not Changing Color or Status After Configuration Validation  

---

## 📄 Issue Summary  
After executing the configuration process, validation feedback in the sheet does not behave as expected:

- ❌ Rows with validation **errors do not turn red**.  
- ❌ Rows with **successful execution do not turn green**, and their status stays as **"Pending"** instead of changing to **"Processed"**.

---

## 📋 Steps to Reproduce  
1. Complete the configuration process.  
2. Introduce an error during validation.  
3. Observe the affected rows — no red highlight appears.  
4. Complete a successful configuration without errors.  
5. Observe that the row still doesn’t turn green and status remains "Pending".

---

## ✅ Expected Result  
- Rows should be highlighted in **red** if a validation error occurs.  
- Rows should be highlighted in **green**, and the status should update to **"Processed"** upon successful configuration.

---

## ❌ Actual Result  
- Rows do **not change color** (neither red nor green).  
- Status remains **"Pending"** even after successful configuration.

---

## 🔎 Severity & Priority  
- **Severity:** _Medium_  
- **Priority:** _low_

---

## 🧪 Environment  
  - **Stage:** Testing Environment  

---

## 📎 Attachments  
- **Successful Configuration Screenshot:**  
  ![Success](Bug%20Reporting%20Images/bug42.png)
  ![Success](Bug%20Reporting%20Images/bug41.png)

- **Failed Configuration Screenshot:**  
  ![Failure](Bug%20Reporting%20Images/bug43.png)

> **Note:** Please ignore the arrow in the screenshots.
