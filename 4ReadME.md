# Active Directory: Resolving Missing Company Emails (Group Membership Issue)

## 📌 Overview
This project demonstrates how to resolve an issue where a user is not receiving company-wide emails by adding them to the appropriate distribution group in Active Directory.

---

## 🎯 Scenario
A user reports they are not receiving emails that are sent to all employees. The issue is identified as missing group membership.

---

## 🧠 Step 1: Locate the User Account
- Opened **Active Directory Users and Computers**
- Right-clicked the domain **directterm.local**
- Selected **Find**
- Chose **Users, Contacts, and Groups**
- Entered the user’s name (**Michael**) and executed the search

<img width="1176" height="817" alt="Screenshot" src="https://github.com/user-attachments/assets/9616bf6f-1e32-46da-a3df-1eff4ff2f9d1" />

*Caption: Locating the user account in Active Directory.*

---

## 🧠 Step 2: Add User to Distribution Group
- Opened the user’s account properties
- Navigated to the **Member Of** tab
- Clicked **Add**
- Searched for and selected **DL-AllEmployees**
- Added the user to the group

<img width="1037" height="813" alt="Screenshot" src="https://github.com/user-attachments/assets/feea6222-c0b2-4516-be63-a2de90a448d3" />

*Caption: Adding user to the DL-AllEmployees distribution group.*

---

## 🧠 Step 3: Verify Group Membership
- Confirmed the user appears in the **Member Of** tab
- Clicked **Apply** to save changes

<img width="1118" height="818" alt="Screenshot" src="https://github.com/user-attachments/assets/3e3e5104-5ea0-4c0a-b204-15b96655b032" />

*Caption: Verifying the user has been successfully added to the group.*

---

## 🧠 Outcome
Resolved the issue by adding the user to the correct distribution group, ensuring they receive all company-wide communications.

---

## 🚀 Tools Used
- Windows Server 2022 (Virtual Machine)
- UTM Virtual Machine
