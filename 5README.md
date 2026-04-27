# Active Directory: Moving a User Between Organizational Units (USA → Europe)

## 📌 Overview
This project demonstrates how to move a user account between Organizational Units (OUs) in Active Directory to reflect a change in the user’s assigned region.

---

## 🎯 Scenario
A user has been transferred from the USA region to Europe and must be moved from the USA Organizational Unit to the Europe Organizational Unit in Active Directory.

---

## 🧠 Step 1: Locate the User Account
- Opened **Active Directory Users and Computers**
- Right-clicked the domain **directterm.local**
- Selected **Find**
- Chose **Users, Contacts, and Groups**
- Entered the user’s name (**David**) and executed the search

<img width="1070" height="805" alt="Screenshot" src="https://github.com/user-attachments/assets/29d1b90f-231b-4ada-b5e7-df6dc182e1cf" />

*Caption: Locating the user account in Active Directory.*

---

## 🧠 Step 2: Moving the User to a New OU
- Right-clicked the user account
- Selected **Move**
- Navigated to the **Europe OU**
- Selected the **Users** container
- Clicked **OK** to confirm the move

<img width="1073" height="812" alt="Screenshot" src="https://github.com/user-attachments/assets/392a555e-0336-4ee4-935e-f837ac8c6236" />

*Caption: Moving user from USA OU to Europe OU.*

---

## 🧠 Step 3: Verify User Location
- Navigated to the **Europe OU**
- Confirmed the user (**David Starryman**) is now located in the correct organizational unit

<img width="1078" height="818" alt="Screenshot" src="https://github.com/user-attachments/assets/5ed64064-e581-4d1d-ba85-f2510b650704" />

*Caption: User successfully moved to the Europe OU.*

---

## 🧠 Outcome
The user account was successfully relocated to the correct Organizational Unit, ensuring proper regional organization and policy application.

---

## 🚀 Tools Used
- Windows Server 2022 (Virtual Machine)
- UTM Virtual Machine
