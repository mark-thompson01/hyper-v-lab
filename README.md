# Hyper-V Virtualization Lab Environment  
A complete, hands-on Hyper-V lab designed for learning, documenting, and demonstrating virtualization concepts using Microsoft’s enterprise-grade Type-1 hypervisor. This project includes technical write-ups, guided walkthroughs, screenshots, administrative tasks, and VM setup demonstrations across multiple operating systems.

This lab is part of my long-term project to build a fully documented home-lab environment while strengthening my systems administration and virtualization skills.

---

## 📌 Table of Contents
- [Overview](#overview)
- [Objectives](#objectives)
- [Lab Modules](#lab-modules)
- [Technologies Used](#technologies-used)
- [Lab Structure](#lab-structure)
- [VM Operating Systems Included](#vm-operating-systems-included)
- [Virtualization Features Demonstrated](#virtualization-features-demonstrated)
- [Screenshots & Documentation](#screenshots--documentation)
- [Future Enhancements](#future-enhancements)
- [License](#license)

---

## 🔍 Overview
This repository documents the creation and configuration of a Hyper-V virtualization rig running on Windows 11 Professional on a Lenovo Thinkpad E16 2nd Gen as the Hyper-V host. The project walks through:

- Understanding how Hyper-V works internally  
- Enabling, configuring, and managing Hyper-V  
- Creating virtual machines  
- Installing full operating systems  
- Building virtual switches  
- Performing administrative tasks using GUI, PowerShell, and DISM  
- Using Hyper-V Manager effectively  
- Learning how Windows becomes a **root partition** when Hyper-V is enabled  
- Observing how Type-1 hypervisors manage compute resources  

All content is displayed through my GitHub Pages Portfolio with clean formatting, galleries, and guided explanations.

---

## 🎯 Objectives
This lab project was designed to:

- Build hands-on virtualization experience  
- Document Hyper-V concepts clearly and professionally  
- Strengthen practical skills used by system administrators  
- Provide educational content for others exploring Hyper-V  
- Showcase a real, structured lab environment for employers and recruiters  

---

## 📚 Lab Modules  
Each module is a standalone educational page available in the GitHub Pages site for this repository.

### **1️⃣ Hyper-V Overview**  
Explains what Hyper-V is, how the hypervisor layer works, partitions, and why Hyper-V is a true Type-1 hypervisor.

### **2️⃣ Hyper-V Setups & Hardware Specs**  
Detailed breakdown of hardware requirements, realistic laptop/desktop specs, and enterprise-grade server hardware used in production Hyper-V deployments.

### **3️⃣ Enabling Hyper-V in Windows 11**  
Three different methods:
- Using Programs and Features (Control Panel)  
- Using PowerShell (`Enable-WindowsOptionalFeature`)  
- Using DISM  

### **4️⃣ Hyper-V Manager**  
GUI overview, major components, and how the management OS interacts with the hypervisor.

### **5️⃣ Creating VMs & OS Installations**  
Full VM creation walkthrough for:
- Windows Server  
- Ubuntu Server  
- pfSense Firewall Appliance  

Includes complete image galleries of:
- VM setup  
- OS installation  
- Initial configuration  

### **6️⃣ Setting up a Virtual Switch — vSwitch**  
Covers:
- Internal, external, and private networks  
- Virtual NIC behavior  
- How Hyper-V abstracts network resources  
- Step-by-step vSwitch creation with screenshots  

### **7️⃣ Hyper-V Manager Administrative Tasks I & II**  
Two pages covering real sysadmin-level tasks such as:
- Checkpoints  
- VM import/export  
- vCPU & RAM tuning  
- Virtual disk expansion  
- Enhanced Session Mode  
- Resource management  
- Integration Services  
- Host and VM-level configuration  

---

## 🧰 / 🖥️ Tools & Technologies Used
- **Lenovo ThinkPad E15 Gen 2**
- **Windows 11 Professional**
- **Hyper-V (Microsoft Type-1 hypervisor)**  
- **Hyper-V Manager**
- **PowerShell**
- **DISM**
- **Windows Server**
- **Ubuntu Server**
- **pfSense Firewall**
- **Virtual Switch Manager**

---

## 🗂️ Lab Structure / Lab Modules
- **Hyper-V Overview**
- **Hyper-V Setups & Hardware SPecs**
- **Enahbling Hyper-V in Windows 11**
- **Hyper-V Manager**
- **Creating VMs & OS Installations**
- **Setting up a Virtual Switch - vSwitch**
- **Hyper-V Manager Administrative Tasks I**
- **Hyper-V Manager Administrative Tasks II**

---

## 📁 More from Me

Visit my full GitHub Pages portfolio to explore additional projects:

🔗 [MTPortfolio – Full Project Index](https://mark-thompson01.github.io/MTPortfolio/)


##

📄 **License**  
This content is licensed under the [Creative Commons Attribution 4.0 International (CC BY 4.0)](https://creativecommons.org/licenses/by/4.0/)

