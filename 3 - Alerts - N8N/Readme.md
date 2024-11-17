# Alerts System for Property Management

This repository contains workflows for managing alerts in property management, focusing on high-frequency issues, contractor performance, and high-cost maintenance events. These alerts are designed to help property managers proactively address problems and optimize operations.

## **Global Workflow**


<img width="888" alt="Workflow" src="https://github.com/user-attachments/assets/56e22eb1-20a7-46fb-a095-36b1aa1c0263">

---

## 📌 **Alerts Overview**

### 1. **Detect recurring maintenance issues**
- **Description**: Monitors issue types that occur more than five times in a week, indicating recurring problems.
- **Trigger**: Sends an email alert to the property manager with preventive maintenance suggestions, derived from the various notes recorded during the resolution of the recurring issue.
- **Use Case**: Helps prevent recurring maintenance issues by identifying patterns early.

**Output Example**:  

![785f5432-15c9-4043-b681-63ccd2c8f37e](https://github.com/user-attachments/assets/8f56070b-a767-48ab-b26f-8296a627a1c2)

---

### 2. **Control maintenance costs**
- **Description**: Identifies maintenance issues with costs exceeding a predefined threshold.
- **Trigger**: Sends a notification to reevaluate budget allocation or consider alternate contractor options by suggesting the best contractor who specializes in the same issue and offers the lowest price.
- **Use Case**: Optimizes maintenance budgets by flagging unusually expensive issues for review.

**Output Example**:  

![becc7156-96a6-4647-990f-028f26df0297](https://github.com/user-attachments/assets/201e3ba3-30c0-4fe2-87b0-965279c89759)

---

### 3. **Monitor contractor performance**
- **Description**: Flags contractors whose average resolution time exceeds a set threshold (e.g., 48 hours).
- **Trigger**: Sends an alert to the property manager for review and suggests switching contractors for specific issues.
- **Use Case**: Ensures timely resolutions by monitoring contractor performance and addressing inefficiencies.

**Output Example**:  

![786bcc92-284b-4d8e-bcae-67be2458bb26](https://github.com/user-attachments/assets/8c586742-f577-4cb3-b5f7-c5df5a9e086b)

