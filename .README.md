# Active Directory: Creating Organizational Units (OUs) for Departmental Structure

## 📌 Overview
This project demonstrates the creation and organization of Organizational Units (OUs) within Active Directory to represent different geographic regions and departmental structures.

---

## 🎯 Scenario
Design an Active Directory OU structure for a global organization with regions (USA, Europe, Asia) and standard departmental divisions (Users, Computers, Servers).

---

## 🧠 Step 1: Creating Regional Organizational Units
- Opened **Active Directory Users and Computers**
- Right-clicked the domain **directterm.local**
- Selected **New > Organizational Unit**
- Created the following OUs:
  - USA
  - Europe
  - Asia

<img width="1184" height="800" alt="Screenshot" src="https://github.com/user-attachments/assets/ba1cd134-77b0-4a06-bfc3-cae28f215edb" />

*Caption: Regional OUs created for geographic organization.*

---

## 🧠 Step 2: Creating Departmental Structure and Objects
- Within each regional OU (USA, Europe, Asia), created sub-OUs:
  - Computers
  - Users
  - Servers
- Navigated to **USA > Users**
- Created security groups:
  - DL-ITAdmins
  - IT
  - DL-AllEmployees
- Created a new user account and assigned a password

<img width="1197" height="803" alt="Screenshot" src="https://github.com/user-attachments/assets/9b74f97d-853e-4c60-a782-a29193b8ed6f" />

*Caption: Departmental OUs, groups, and user account created.*

---

## 🧠 Step 3: Results
- Confirmed groups and user account were successfully created within the appropriate OU

<img width="1172" height="802" alt="Screenshot" src="https://github.com/user-attachments/assets/9f67efde-e750-4ec2-adae-95c411185464" />

*Caption: Final OU structure with user and groups.*

---

## 🚀 Tools Used
- UTM Virtual Machine
- Windows Server 2022 
