# Active Directory: User is not getting all the emails that are sent out to employees

## 📌 Overview
Adding a user who is not getting all the emails all employees are suppose to get into the correct group

---

## 🎯 Scenario
Adding a user who is not getting all the emails all employees are suppose to get into the correct group

---

## 🧠 Step 1: Locate the User Account
- Opened **Active Directory Users and Computers**
- Right-clicked the domain **directterm.local**
- Selected **Find**
- Chose **Users, Contacts, and Groups** from the search dropdown
- Entered the user’s name (**Michael**) and executed the search

<img width="1176" height="817" alt="Screenshot" src="https://github.com/user-attachments/assets/9616bf6f-1e32-46da-a3df-1eff4ff2f9d1" />

*Caption: Searching for user account within Active Directory.*

---

## 🧠 Step 2: Reset the User Password
- Right-clicked the user account and selected **Reset Password**
- Entered a temporary password
- Enabled:
  - **User must change password at next logon**
  - **Unlock the user’s account**
- Clicked **OK** to apply changes

<img width="1135" height="816" alt="Screenshot" src="https://github.com/user-attachments/assets/5f00bee8-46b5-4301-a2d3-78764a2483b2" />

*Caption: Resetting the user password and restoring account access.*

---

## ✅ Key Skills Demonstrated
- Active Directory User Management
- Password Reset & Account Recovery
- Identity and Access Management (IAM)
- Windows Server Administration

---

## 🧠 Outcome
Successfully reset the user’s password and restored account access while enforcing secure login practices.

---

## 🚀 Tools Used
- Windows Server 2022 (Virtual Machine)
- UTM Virtual Machine
