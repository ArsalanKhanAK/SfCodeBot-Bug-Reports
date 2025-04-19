# 🐞 Bug Report

**Module Name:** EC  
**Screen Name:** Message Definition  
**Issue Summary:**  
Red highlight appears in the **"text"** column of the *Message Definition* sheet, even though the data is successfully added to the instance.

---

## 📋 Steps to Reproduce
1. Navigate to the **Message Definition** screen under the **EC** module.  
2. Add data to the **"text"** column in the sheet.  
3. Start the Configuration/Automation process.  
4. Confirm that the data is successfully added to the instance.  
5. Recheck the sheet post-execution.

---

## ✅ Expected Result
- No red highlight should appear in the **"text"** column if the data is correctly added.

---

## ❌ Actual Result
- The data is successfully added to the instance.  
- However, the **"text"** column in the Message Definition sheet is highlighted in **red**, indicating a validation issue even when there is none.

---

## 🔎 Severity & Priority
- **Severity:** Medium  
- **Priority:** High  

---

## 📎 Attachments

- **Validation Issue in Sheet:**  
  ![Message Definition - Text Column Highlight in Red](Bug%201/bug 2 i 2.png)

- **Instance Confirmation Screenshot:**  
  ![Data Successfully Added to SAP](Bug%201/bug_2_img_1.png)
