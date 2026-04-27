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

## 🧠 Step 2: Adding User to the DL-AllEmployees Group
- Clicked on the name Michael Jackson then pressed the member of tab then clicked add and searched up the DL-AllEmployees group clicked on it and added the user 

<img width="1037" height="813" alt="Screenshot 2026-04-24 at 4 02 03 AM" src="https://github.com/user-attachments/assets/feea6222-c0b2-4516-be63-a2de90a448d3" />

---

## 🧠 Step 3:Making sure the user was added 
- Went back to the "memeber of" tab and clicked on apply to make sure user was added to the group
  
<img width="1118" height="818" alt="Screenshot 2026-04-24 at 4 05 03 AM" src="https://github.com/user-attachments/assets/3e3e5104-5ea0-4c0a-b204-15b96655b032" />

---

## 🚀 Tools Used
- Windows Server 2022 (Virtual Machine)
- UTM Virtual Machine
