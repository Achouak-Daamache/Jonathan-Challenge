# Jonathan Challenge – Historical Backdoor Attack Simulation

## Background

In 1999, NASA suffered a major intrusion carried out by Jonathan James, one of the earliest known cyberattacks performed by a teenager. The breach demonstrated how weak configurations and poor monitoring could lead to full system compromise.

This challenge recreates a simplified scenario and introduces several core cybersecurity concepts through a realistic attack simulation inspired by that incident, focusing on initial access and long-term persistence.

---

## Learning Objectives

- Perform basic network discovery and target identification  
- Identify vulnerable services and outdated software  
- Exploit Apache Tomcat Manager for remote code execution  
- Establish persistent access using multiple backdoor techniques  
- Understand how attackers maintain access even after mitigation attempts  
- Extract sensitive data through network sniffing  

---

## How to Run the VM

Follow these steps to set up the target machine:

1. Install VMware Workstation  
2. Download the `.ova` file of the target machine [here](https://tryhackme-vm-upload.s3.eu-west-1.amazonaws.com/target-1770044231675.ova?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=AKIA2YR2KKQMWLXEMXW4%2F20260222%2Feu-west-1%2Fs3%2Faws4_request&X-Amz-Date=20260222T110047Z&X-Amz-Expires=120&X-Amz-Signature=20eb10de6f7ffdd7af22469c91663656b2750c0781630a0aed83f24842a30a61&X-Amz-SignedHeaders=host&x-amz-checksum-mode=ENABLED&x-id=GetObject)
3. Open VMware Workstation and import the `.ova` file  
4. Start the machine  
5. Launch the exploit using your preferred attack box  

---

**Note:**
If you prefer guided mode over discovery mode, you can access Jonathan's private TryHackMe room [here](https://tryhackme.com/room/jonathan) here you can compete with others, gain extra THM points,share your write-up  