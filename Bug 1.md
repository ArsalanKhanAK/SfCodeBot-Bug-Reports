# Bug Report

**Tracking Request ID:** 7f047d4a76-7824276  
**Group ID:** 7f047d4a76-G6397413  
**Module:** Employee Central  
**Sheet:** MDF Objects Fields

---

## Title
**Field Criteria not being applied in MDF Objects Fields during automation, and no validation or log error shown**

---

## Description
While setting Field Criteria in the MDF Objects Fields sheet and executing the automation/configuration through CodeBot, the field criteria is not being applied in the instance.  
Moreover, there is no error shown in the logs, and no validation feedback is provided in the sheet.  
The expected red highlight for failed rows is also missing. This makes it difficult to identify that the Field Criteria configuration has failed.

---

## Steps to Reproduce
1. Open the MDF Objects Fields sheet  
2. Insert data in Field Criteria Section for a field  
3. Run automation/configuration using CodeBot  
4. Observe the applied configuration in the instance and check the logs and validation status in the sheet  

---

## Expected Result
- Field Criteria should be correctly applied to the respective field in the instance  
  - The corresponding row in the sheet should be highlighted in **green** through validation  
- If the configuration fails:  
  - The corresponding row in the sheet should be highlighted in **red** through validation  
  - The log should capture the same error that appears on the instance in the CodeBot log  

---

## Actual Result
- Field Criteria is not applied in the instance  
- No error is shown in the logs  
- No red or green validation highlight in the Field Criteria row  

---

## Severity
**High**

---

- **Sheet Screenshot:**  
  ![Sheet Screenshot](bug%201/sheet.png)

- **Logs Screenshot:**  
  ![Logs Screenshot](bug%201/logs.png)

- **Field Criteria Not Added in Instance:**  
  ![Field Criteria Error](bug%201/criteria_not_added.png)

- **Expected Error Message in Logs:**  
  ![Expected Error in Logs](bug%201/expected_error.png)

> **Error In Text:**  
> `Cannot create the field criteria GOFieldCriteria{sourceFieldName='Position', destinationFieldValue='cust_tester8', defaultDestinationValue='cust_tester8'} for field cust_Arsalan1 in object definition cust_Arsalan_khan_Rechecking.`
