# 🧰 Active Directory Lab Setup

This section documents the initial build and configuration of the Active Directory home lab environment.

The goal of this setup was to simulate a real-world enterprise network where users, computers, policies, and authentication services can be managed and supported.

---

## 🎯 Objectives

- Build a Windows domain environment
- Deploy a Domain Controller
- Configure DNS and networking
- Join a client machine to the domain
- Prepare the environment for identity and access management scenarios

---

## 🖥️ Lab Environment

### Virtualization Platform
- VMware Workstation Pro 25H2

### Servers
- Windows Server 2022 (Domain Controller)

### Clients
- Windows 10 / Windows 11 machine

---

## 🌐 Network Configuration

- Domain: `corp.local`
- Domain Controller IP: `192.168.1.10`
- DNS Server: Domain Controller

---

## ⚙️ Configuration Steps

### 1. Create Virtual Machines
- Provisioned server and client VMs
- Assigned RAM, CPU, and disk resources

📸 Screenshot:
![VM Setup](./screenshots/vm-created.png)

---

### 2. Install Windows Server
- Completed OS installation
- Applied updates
- Set administrator credentials

📸 Screenshot:
![Server Install](./screenshots/server-installed.png)

---

### 3. Configure Static IP
- Assigned fixed IP to server
- Configured DNS settings

📸 Screenshot:
![Static IP](./screenshots/static-ip.png)

---

### 4. Install Active Directory Domain Services (AD DS)
- Added AD DS role
- Prepared server for promotion

📸 Screenshot:
![ADDS Installed](./screenshots/adds-installed.png)

---

### 5. Promote to Domain Controller
- Created new forest
- Domain: `corp.local`

📸 Screenshot:
![Domain Created](./screenshots/domain-created.png)

---

### 6. Join Client to Domain
- Updated DNS to DC
- Successfully joined workstation to domain

📸 Screenshot:
![Client Joined](./screenshots/client-joined.png)

---

## ✅ Outcome

A fully functional domain environment is now available for:

- User & group administration  
- Password management  
- Group Policy configuration  
- Authentication troubleshooting  
- Security investigations  

---

## 🚀 Next Steps

Continue to:
- [User & Group Management](./User-Group-Management/)
- [Password & Account Lockout Management](./Password-Account-Management/)
- [Group Policy Basics](./Group-Policy/)
- [Access & Login Troubleshooting](./Access-Troubleshooting/)

